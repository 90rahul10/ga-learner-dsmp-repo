### Project Overview

 We are given references to news pages collected from an web aggregator in the period from 10-March-2014 to 10-August-2014. The resources are grouped into categories that represent pages discussing the same story. News categories included in this dataset include business(b); science and technology(t); entertainment(e); and health(h)


### Learnings from the project

 Following concepts of text analytics:
1. Preprocess text data with tokenization, stopword removal etc
2. Vectorize data using Bag-of-words and TF-IDF approaches
3. Apply classifiers (Logistic and Multinomial Naive Bayes) to perform multi-class classification


### Approach taken to solve the problem

 1. Load data, take only the relevant columns and observing the distribution of the class labels
2. Preprocess data and split into training and test sets
    -  Retaining only alphabets (Using regular expressions)
    - Removing stopwords (Using nltk library)
    - Splitting into train and test sets (Uisng scikit-learn library)​
3.Vectorize with Bag-of-words and TF-IDF approach
4. Predicting with Multinomial Naive Bayes
5. Predicting with Logistic Regression using OneVsRestClassifier


