# Simple Chatbot

In this project I have presented a chatbot that generates a dynamic response for online client's queries. The Proposed System is based on Artificial Intelligence-powered Chatbot. The web based platform provides a vast intelligent base that can help simulate problem- solving for humans. This proposed chatbot identifies the user context which triggers the particular intent for a response. Since it is responding dynamic response, the desired answer will be generated for the user. The proposed system used machine learning algorithms to learn the Chatbot by experiencing various user's responses and requests. Chat-bot is that it comes to use in numerous fields of our daily life. Nowadays chat-bot is started to becoming so robust because Artificial Intelligence aids the human touch in every conversation, chat-bot understand the user's query, and trigger an accurate response.


   ![image](https://github.com/Samridhi282/Chatbot/assets/146213252/a540bf9b-d516-423f-a8f7-c0073418ded7)


# METHODOLOGY:

We’ll take a step-by-step approach and eventually make our own chatbot:-

  ![image](https://github.com/Samridhi282/Chatbot/assets/146213252/83cd088c-5006-4463-a19e-6a35e311ca0f)



# Step 1.Install the Chatterbot and chatterbot corpus module :
The first and foremost step is to install the chatterbot library. You also need to install the chatterbot corpus library. Basically, Corpus means a bunch of words. The Chatterbot corpus contains a bunch of data that is included in the chatterbot module. The corpus is used by bots to train themselves.
# Step 2. Import the modules
we have to import two classes: Chatbot from chatterbot and List Trainer from chatterbot. Trainers.
List Trainer: Allows a chatbot to be trained using a list of strings where the list represents a conversation.
# Step 3. Name our Chatbot:
Now, we will give any name to the chatbot of our choice. Just create a Chatbot object. Here the chatbot is maned as “Bot” just to make it understandable.
# Step 4. Use of Logic Adapter:
The Logical Adapter regulates the logic behind the chatterbot that is, it picks responses for any input provided to it. This parameter contains a list of all the logical operators. When more than one logical adapter is put to use, the chatbot will calculate the confidence level, and the response with the highest calculated confidence will be returned as output.
Here we have used two logical adapters:
BestMatch: The BestMatchAdapter helps it to choose the best match from the list of responses already provided.
TimeLogicAdapter: The TimeLogicAdapter identifies statements in which a question about the current time is asked. If a matching question is detected, then a response containing the current time is returned.
# Step 5. Training, Communication, and Testing :
For the training process, you will need to pass in a list of statements where the order of each statement is based on its placement in a given conversation. We have to train the bot to improve its performance for this we need to call the train() method by passing a list of sentences. Training ensures that the bot has enough knowledge to get started with specific responses to specific inputs. After training, let’s check its communication skills. And the last step is to do testing

# Referance
https://www.geeksforgeeks.org/chat-bot-in-python-with-chatterbot-module/
