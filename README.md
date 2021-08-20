# Sample-Chatbot
Chatbot built on deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. 
Using a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.
Project requires some modules: TensorFlow, Keras, Pickle and Natural Language processing    
pip install tensorflow, keras, pickle, nltk
Intent.json -The data file which has predefined patterns and responses.
train_chatbot.py – A script to build the model and train the chatbot.
Words.pkl –  storing the words as Python object that contains a list of our vocabulary.
Classes.pkl – contains the list of categories.
Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.
Chatgui.py –  script for users who can easily interact with the bot.
