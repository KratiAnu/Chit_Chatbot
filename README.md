# Chit_Chatbot
A simple chatbot to answer frequently asked questions.
It is a rule-based chatbot, which can be operated for small talks.
The dataset over which the chatbot is trained is small, made for general talks purpose only.
The dataset consists of a JSON file where there are a bunch of messages that the user is likely to type in and are mapped into groups of appropriate responses. 
The tag on each dictionary in the file indicates the group that each message belongs to. 
With this data a neural network is trained to take a sentence of words and classify it as one of the tags in the file. 
Then a response is selected at random from those groups and displayed to the user. 
The more tags, responses, and patterns the more complex the dataset, the better, the chatbot.

The packages used are:
- numpy
- nltk
- tensorflow
- tflearn
