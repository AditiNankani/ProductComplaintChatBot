# ProductComplaintChatBot
Amazon lex oriented product complaint chatbot using aws

Terminologies:
--->Intent: An intent performs an action in response to natural language user input
--->Utterances: Spoken or typed phrases that invoke your intent
--->Slots: are input data required to fulfill the intent
--->Fulfillment: mechanism for your intent


->Aws console ->Amazon Lex->Get started->Create Bot

Step-1: CREATING BOT
1)Bot Name: ComplaintManagement
2)IAM Permissions: Create a role with basic Amazon Lex permissions.
3)Language :English


Step-2: INTENTS & UTTERANCES
1)Intent name: RegisterComplaint
2)Description: This bot helps in registering product complaints
3)Utterances:
Hi
Hello
Hey,I have issues with my product
Hey,I have problem with my product
I want to report a problem with my order
etc...


Step-3: Toggling
1)Toggle confirmation prompts to active
2)Toggle   closing responses to active
Save Intent

Step-4: Slot Types
Intent gets fulfilled only when slots are fulfilled, slots are like placeholders for intents
1)1st slot:ProductName
![image](https://github.com/user-attachments/assets/33fdc269-34c9-4430-8a30-e21a58f718af)







