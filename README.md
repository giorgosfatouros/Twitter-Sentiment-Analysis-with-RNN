# Twitter-Sentiment-Analysis
Twitter Sentiment Analysis using RNNs and fasttext pretrained word embeddings.

* Compare a  BiGRU + MLP model with a Bi-LSTM + deep self-attention + MLP model

* Fine- tune the best of them

* Data Source: https://www.kaggle.com/kazanova/sentiment140

This is the sentiment140 dataset. It contains 1,600,000 tweets extracted using the twitter api . The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment.

Content

* It contains the following 6 fields:

* target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
* ids: The id of the tweet ( 2087)
* date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
* flag: The query (lyx). If there is no query, then this value is NO_QUERY.
* user: the user that tweeted (robotickilldozr)
* text: the text of the tweet (Lyx is cool)
