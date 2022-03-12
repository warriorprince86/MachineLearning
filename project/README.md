# Classification of Tweets and modeling of Stock/Cryptocurrency Price

# References
https://matheo.uliege.be/bitstream/2268.2/1323/4/Erratum.pdf


## What is the data about?
Text twitter from Elon Musk account, ~500 tweets from 01/01/2022 to Present
We will collect the end of day stock price for final regression during the same time.
The data is text and financial information
The data is being collected through twitter API and through yahoo finance
Sentiment analysis of tweets from Elon Musk and model it to predict if the stock price is increasing or decreasing.

## Why is it important/significant?
The product that we have in mind is to use twitter information and inform the user about buy/sell recommendations. Important with day traders and self-directed investments.

## Hypothesis
The hypothesis is that a positive sentiment should drive the stock price higher and that we should be able to use NLP and regression to model this information.

## Communications
### Response from Xuan
Hi Sarthak, the data size is small. How do you plan tune and to evaluate the model?

### Response from Sarthak
Hi Xuan,
We can try to increase the dataset.
The evaluation criteria would be the classification accuracy measures. The output of the model would be either a prediction of price increase or decrease.

The plan is to average out the tweet sentiment scores per day and use the closing price of the stock to see if there was an increase or decrease in price from last day closing price.

### Response from Xuan
Hi Sarthak, for the term project, we usually recommend 10k+ training samples.
Please see if you can gather more tweets and also study the stock price trend at a finer level (e.g., hourly instead of daily).
If you think you can do this, I approve your project.
Also, when training ML model on time series, make sure that you don't shuffle your data (because you could leak future information into the past that way). You will need to train the model on a portion of historical data and evaluate it on another section of more recent data.

### Response from Sarthak
Hi Xuan,
Thanks for your comments.

We were able to get about 7k tweets, would this meet your requirements on
the training data set?
Secondly, it would be challenging for us to do the analysis hourly as there
may be times that we don't have any tweets or tweets are made when the
markets are closed. We can try increasing the frequency to twice a day or
something.

### Response from Xuan
Hi Sarthak, you can model the response of the stock market after a tweet has been posted. It doesn't have to be a fixed time interval.
But yes I approve your project. I'm curious to see your results!
Xuan

### Response from Sarthak
Thanks Xuan!
Yeah, even we are curious as social media has started to impact the stock
markets and Musk is quite a sensation on Twitter.