# chatbot
chatbot that is able to understand what the user is talking about and give an appropriate response.
To implement the chatbot, we will be using Keras, which is a Deep Learning library, NLTK, which is a Natural Language Processing toolkit, and some helpful libraries. 


Running the Chatbot
Now we have two separate files, one is the train_chatbot.py, which we will use first to train the model.

python train_chatbot.py 

Interacting With the Chatbot
Our model is ready to chat, so now let’s create a nice graphical user interface for our chatbot in a new file. You can name the file as gui_chatbot.py

In our GUI file, we will be using the Tkinter module to build the structure of the desktop application and then we will capture the user message and again perform some preprocessing before we input the message into our trained model.

The model will then predict the tag of the user’s message, and we will randomly select the response from the list of responses in our intents file.
