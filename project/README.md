
## Project Structure
Folder/File | Description
---| ---
data/ | this folder includes the data files prior to processing and post-processing.
pics/ |  includes pictures that were pulled out for the presentation
data_preparation | data wrangling and processing to prepare data for ML
get_stocks_data | get stocks data from yahoo-finance
model_all_models | evalaution of models including decision trees, logistic regression, SVM, AdaBoost includeing hyper parameter tuning
model_naivebayes | naive bayes model built on TF-IDF directly on the content of the tweets
model_nn_bert | bert pre-processing and bert trained model directly in the content of the tweets
model_nn_sentiments | neural network model tried on sentiments, Archived
model_svm | svm model initial build, Archived

## Models
- models_all_models.ipynb > Tweet > Sentiment > classification Algorithms
- text_model.ipynb > Tweet > Count Vectorizer > TFIDF > Classification Algorithms
- nn_model.ipynb - Tweet > BERT Tokenizer > NN
