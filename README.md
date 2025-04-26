# Duplicate-question-identification
Using NLP techniques we have build a classification algorithm to detect similar type of questions. 
This can be used to merge all the sentences which have same type of questions and map answers accordingly.

In preprocessing the texts we have dealt with signs, symbols, lowercasing the doc, html tags, punctuations, stopwords etc.

We have done feature engineering and added around 23 new feature to the dataset.

We have used in this text representation techniques like:
1. Bag of words
2. Tf_idf
3. Word2vec
   
We have used 4 classififcation algorithm in this project:
1. Logistic regression
2. Decision Tree
3. Random Forest
4. XG Boost classifier
5. 
We saw that for this dataset and type of problem the random forest classififer with the TF_IDF works as the best model
