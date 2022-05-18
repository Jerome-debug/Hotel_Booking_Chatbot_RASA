# Hotel_Booking_Chatbot_RASA

This is a basic Chatbot for hotel bookings using python

# Customization of RASA Chatbot

##1.NLU.md file

Here we add the intent,and describe a sample way of saying the intent(Describing all the possible ways of coming up with the sentence)

##2.Domain.yml

After adding the intent on the nlu file,you define the intent file on the domain and add a response as well as define the entities.
Also declaring of the action name that we do in action.py

##3.Action.py

Define custom action or business logic thats responded to the user

Either we use API call or logic of call

##.4.Stories.md

Define the intent and response flow of particular conversations in stories.md file

##.5.Credentials.yml

Add a secret key to access token to access the bot from other applicationn platforms i.e messenger,slack
