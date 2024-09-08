**Cyberbullying Tweet Classifier**

This project classifies tweets into various categories of cyberbullying, leveraging NLP techniques and a custom-built neural network from scratch using only NumPy and Pandas.

The dataset consists of tweets, each labeled with the type of cyberbullying they're guilty of (e.g., hate speech, sexism, etc.). The tweets were cleaned extensively, using tokenization, lemmatization and a custom stop-words removal catered to twitter lingo,
and then vectorized using tf-idf vectorization. 

A 2-layer neural network was used for classification. It achieved a 74.254% accuracy, which is slightly higher than Scikit-Learn's SVM classifier. The architecture used was :
linear -> expit -> linear -> softmax. 
