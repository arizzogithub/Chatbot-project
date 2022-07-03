# Chatbot-project

This is my implementation of chatbot, based on the methods that were mentioned in this article ⬇️

[Build Your First Python Chatbot Project](https://dzone.com/articles/python-chatbot-project-build-your-first-python-pro)

To implement the chatbot, I will be using **Keras** (which is a Deep Learning library), **NLTK** (which is a Natural Language Processing toolkit), and some helpful libraries. 
##
**Project File Structure:**

**Train_chatbot.py** — In this file, we will build and train the deep learning model that can classify and identify what the user is asking to the bot.

**Gui_Chatbot.py** — This file is where we will build a graphical user interface to chat with our trained chatbot.

**Intents.json** — The intents file has all the data that we will use to train the model. It contains a collection of tags with their corresponding patterns and responses.

**Chatbot_model.h5** — This is a hierarchical data format file in which we have stored the weights and the architecture of our trained model.

**Classes.pkl** — The pickle file can be used to store all the tag names to classify when we are predicting the message.

**Words.pkl** — The words.pkl pickle file contains all the unique words that are the vocabulary of our model.
