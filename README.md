# simple_chatbot
Simple chatbot
- [Theoretical introduction](introduction)
- [Model used and results](model)
# Introduction
This project is a simple chatbot in python using NLTK for text preprocessing, pickle for the files, Keras and Tensorflow for the model creation and tkinter for the GUI.
The preprocessing of sample text is based on a few NLP techniques such as lemmatizing, tokenizing, bag of words and intent classification.
# Model
The model used is a very simple Sequential neural network which is then called at inference time by the tkinter gui, which preprocess the user input text and predicts the intent, based on that the model chooses a appropriate answer.
