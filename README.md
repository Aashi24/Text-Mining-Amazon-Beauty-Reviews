# Text-Mining-Amazon-Beauty-Reviews

## Problem  Statement

Online shopping is all over the internet. All our needs are just a click away. The biggest online shopping website is Amazon. Amazon is known not only for its variety of products but also for its strong recommendation system.

In our project we are taking into consideration the amazon review dataset for Beauty products. We are considering the reviews and ratings given by the user to different products as well as his/her reviews about his/her experience with the product(s).

Based on these input factors, sentiment analysis is performed and models are trained to predict the sentiment of the review, which is helpful in developing a recommender system.


## Project Tasks
I.   Data Extraction

II.  Data Preprocessing

III. Exploratory Data Analysis

IV.  Modeling and Prediction

        [ 1 ] CountVectorizer - Multinomial NB

        [ 2 ] TfidfVectorizer

                1. with Logistic Regression
                2. with Linear SVM by using SGD
                3. Pipeline and GridSearch
        [ 3 ] Word2Vec

               1. Random Forest
               2. Logistic Regression
        [ 4 ] LSTM

                1. Simple LSTM
                2. LSTM with Word2Vec
        [ 5 ] Clustering / Topic Modeling (NMF and LDA) with TF and TFIDF

V.   Conclusion

## Project Results
Pipleline and GridSearch CV with Logistic Regression has the highest accuarcy of 87% and works best for classifying sentiments of 12101 beauty products on Amazon
LSTM with Word2Vec is the second best with 86% Accuracy
Take away - Word embedding with TFIDF work best for our use case

For Topic Modelling:
Both NMF with tf and tfidf were about the same and performed quite well.
LDA with tf was the best. It had a lot of meaningful and unquie associations
LDA with tfidf primarily consisted of unassociated words. However - it did accuractely asscoiate a brand with product --> remington for hair styling
