
# Project Title

Price Prediction Challenge — A Real World Case Study Using Machine Learning


## Business problem

With thousands of tweets circulating per second in the Twitter(a social media platform where people share their opinions in text format), it is really hard to tell whether the sentiment behind the specific tweet will impact the world related to that tweet. Capturing sentiment in these times is very important because it changes the whole dimensions and decisions that are to be made. But what words actually leads to the sentiment description? If we somehow find those words,then when a tweet is about to be tweeted,we can check for these words and remove these words as per our required sentiment.In a way we are supposed to control the consequences before hand by adding or removing specific words from the tweet.
## Machine learning problem
we will be extracting the phrase from an given tweet that reflect the sentiment given for that sentence(tweet).For example:

sentence: ‘I really love her so much’

sentiment: positive : ‘love her so much’

sentence: ‘my teacher is bullying me’

sentiment: negative : ‘bullying me’

We have to extract phrases that contain the‘love’ and ‘bullying’ words from the given sentence based on the sentiment given.Here input to the machine learning model is a sentence and output is also a sentence,which is a part of input sentence.
## Business Constraints

Maximize the jaccard score by correctly predicting the words.

Try to provide some interpretability.

## Steps followed

1. Data description
2. Exploratory Data Analysis : univariate and multi variate Analysis
3. Modelling Approches
4. Encoding
5. Models:
    1. LSTM character level
    2. LSTM word level
    3. Fine tuning Roberta
    4. Many many LSTM
6. Error Analysis
## References

https://www.kaggle.com/c/tweet-sentiment-extraction

https://arxiv.org/pdf/1810.04805.pdf

https://huggingface.co/

https://www.kaggle.com/c/tweet-sentiment-extraction/discussion