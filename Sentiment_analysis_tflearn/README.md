# Sentiment Analysis TFLearn project

This project builds and trains a network to classify English phrases into either positive or negative sentiment. It uses the TFLearn library on top of Tensorflow.

The technique used here is to convert the input sentence into a vectorized format corresponding to word counts for the most frequent 10000 words in the training set. (I.e., word order is neglected.) From those 10000 inputs, three fully connected layers result in a two-output softmax classifier. This simple approach yields a test accuracy of about 85%.
