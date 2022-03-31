# Machine Learning Jan-April 2022
## University of Toronto
This repository includes the final project done as part of the Machine Leanrning Course at Univery of Toronto.

## Project Structure
All files for the project are under project/src/

## Classification of Tweets and modeling of Stock/Cryptocurrency Price
Twitter Content & Sentiment Analysis to Predict Crypto Currency (Bitcoin) Movement.
This algorithm can be expanded to other tweets as well as other stocks/indices. 

## Introduction / Motivation / Hypothesis
Influence of Social media on stocks was quite visible for GME prices. An announcement, opinion, or remark can be enough launch a news story or directly influence the market.

Hypothesis is that if a company has positive sentiment, it will lead its stock price to increase in the near future. 

Problem Statement: Use twitter information to derive the sentiments (positive, neutral or negative) and predict the direction of stock movement (increase or decrease) to inform the user about buy/sell recommendations.

## Discussion & Conclusion
1. Two ways of predicting cryptocurrency movements in 15 minute interval is implemented successfully. 
    - Sentiment Analysis is not conclusive in prediction of stock movement. Perhaps inclusion of other features like tweet likes etc. may be evaluated as features
    - Analysis of direct tweet content is also not conclusive in prediction of stock movement. 
3. The twitter handles must be handpicked to study the impact of a particular index, commodity, cryptocurrency.
4. The stock data also limits how much information can be used as intial dataset.
5. Perhaps the assumption that the information from social media is able to impact the markets within 15 minutes is not correct.

## Future Work
1. More research on userhandles and the commodity that needs to be predicted to ensure relevant information is gathered.
2. Data gathering of 15-minute stock data over a long period of time.
3. Expand the data by including other social media platforms like reddit, discord etc.

## References
https://matheo.uliege.be/bitstream/2268.2/1323/4/Erratum.pdf

https://etd.auburn.edu/bitstream/handle/10415/5759/Using%20Tweets%20Sentiment%20Analysis%20to%20Predict%20Stock%20Market%20Movement.pdf?sequence=2

https://www.researchgate.net/publication/354308107_Stock_Market_Prediction_Using_Twitter_Sentiment_Analysis/fulltext/6130813a0360302a007377f2/Stock-Market-Prediction-Using-Twitter-Sentiment-Analysis.pdf?origin=publication_detail
