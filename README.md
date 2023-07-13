# Sentiment-Analysis using Twitter data

### Description
Sentiment analysis is an automated process of identifying and classifying subjective information in text data. This might be an opinion, a judgment, or a feeling about a particular topic or product feature.
This article reports on the exploration and preprocessing of data, transforming data into a proper input format and classify the user’s perspective via tweets into positive and negative.

### Objective:
To build a classification model that will help to identify the tweets which is classified into positive and negative tweets.

### Data
train.csv

test.csv

### Data Cleaning & Preprocessing
Removing the columns which are not relevent for the analysis.
Some preprocessing task involves :
  lowering case - convert the text column to lower case.
  removing special characters.
  tokenise the text column - the text is split into list of words.
  removing stopwords - These are the commonly used words and are removed from the text as they do not add any value to the analysis.
  Stemming - transforms the word into base form by removing the suffix.
  Lemmatization - transforms the word into the semantic base thus making it interpretable.
  
### Model - Naive Bayes Classifier

#### Using Count Vectorization 
It uses the counting of the set of words used in the document.
#### Using TF IDF (Term Frequency–Inverse Document Frequency)
It gives a way to associate each word in a document with a number that represents how relevant each word is in that document. 
  
