# The Mental Health Support Chatbot

##### *Final Project - Ironhack Bootcamp*

*DAFT - Amsterdam*  
*July 20 Cohort*  
Sarah Busson  

## Content

- [Project Description](#project-description)
- [Data](#data)
- [Workflow](#workflow)
- [Index](#index)
- [Links](#Links)

## Project Description

*For a visual and more detailed explanation, see the file 'HOA_pres' : https://github.com/sarah-busson/mentalhealth-support-chatbot/blob/gh-pages/HOA_pres.pdf*  

Let me introduce you to HOA: a chatbot made to detect and help people with mental health issues.
This subject makes sense to me, as mental health is a field still misunderstood (by science, but even by ourselves) and I know by experience that having a chatbot ready to give me some insights on my mental health could have been helpful and could have pushed me in the right direction.

The name HOA as well is not random: it is a reference to the amazing time I had when I used to live in New Zealand, as 'hoa' means 'friend' in Maori.

Disclaimer : HOA is not supposed to act like a therapist or as a replacement but instead is used as an intermediate, to help people have a better understanding of their health and provide them with a solution: a helpline, the right specialist ...
Its goal is to detect, through a conversation, a mental health disorder in order to adapt its answer.

## Data

Chatbot :
I used a dialogue corpus to train the chatbot to converse with the user.

Deep Learning - Topic Recognizer:
I used dialogue from an online forum that links therapist to clients : https://counselchat.com/

API Connection:
Some of the response come from a medical website, using an API request : https://developer.infermedica.com/

## Workflow

The Chatbot was developped using the chatterbot library on python.
The DL-Topic Recognizer showed a 77% accuracy on the test set, based on 18 different topics. It is a Tensorflow Sequential Model, trained with 3000 conversations (though it is not enough for a DL model).
The Infermedica API requires an authentification key, available upon request through their website.

## Index

- Data: contains all dataset used to train the chatbot and the DL model.
- Code: contains jupyter notebook files used during this project. 'HOA_Chatbot is the final one, https://github.com/sarah-busson/mentalhealth-support-chatbot/blob/gh-pages/code/HOA_Chatbot.ipynb
- Images: contains wordcloud, Tableau graph and screenshot of a test on HOA.

## Links

[Trello Board](https://trello.com/b/RLEPS6Ge/ironhack-final-project)
