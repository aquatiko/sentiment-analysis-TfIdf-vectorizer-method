# Sentiment Analysis using TfIdf method(93.87% accuracy)
Used nltk's inbuit movie review dataset with 32938 positive and 32938 negative reviews.

Used sklearn's BernnoulliNB for classification(for optimum performance).

Used sklearn's TfIdf word vectorizer to convert reviews into trainable features for classifer by making word vectors.

Lemmatizing proved more useful than Stemming.

Made a function to plot most important features(word) based on vectorizer and classifier used.

Accuracy= 93.87%  Precision=94%   Recall=94%   f1-score=94%
