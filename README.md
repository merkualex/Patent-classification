# Patent-classification
Patent classification using open-source neural-network library Keras.

Description:
Patent classification based on "title" and "abstract" fields of USPTO patent application. 
As a classification marker used "The International Patent Classification (IPC)". 

Goal:
Create a NLP model using pre-trained word embeddings for patent class prediction.

1. Using GloVe as an unsupervised learning algorithm for obtaining vector representations for words.
2. Using ELMo as a deep contextualized word representation. 
 
 
Info:
1. Glove (https://nlp.stanford.edu/projects/glove/)
2. ELMO (https://tfhub.dev/google/elmo/3)
3. Keras (https://keras.io)

Platform for running and tests was Google Colaboratory (https://colab.research.google.com) 
