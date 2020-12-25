# Text-Mining-Amazon-Beauty-Reviews


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
