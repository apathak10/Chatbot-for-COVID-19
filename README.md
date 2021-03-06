# Chatbot-for-COVID-19

As Covid-19 has been declared a pandemic on 11 March 2020 by WHO (World Health Organization), this chatbot has been an effort to contribute in fighting this disease by building a husky chatbot using AI (Artificial Intelligence). In this project, queries and sentiments of user is handled using:
1.	Socket Programming: In this project, it contains a server and client script which has the capability to handle multiple client or user who can connect to the server at the same time.
2.	Topic Identification: It has been implemented using newly introduced tensorflow libraries by Google, along with handling multiple languages.
3.	Sentiment Analysis: It is the method of understanding the sentiment of user using vader_lexicon library of NLTK to identify Positive, Negative and Neutral feelings of users.
4.	Quarantine Recommendations: Based on the sentiments of the user, chatbot will be asking for further options to choose from like play a game, workout videos, and many more.

While building this chatbot, we faced the following challenges and resolved at the end:
1.	Using cosine similarity, we can match the similar words in two different sentences, but we cannot find the similarity in the intent of the two. Hence, we used tensorflow_text library
2.	After merging the separate codes for topic identification, cosine similarity and sentiment analysis in socket programming, integration failed at many instances
By incorporating the important resources in an excel sheet, this chatbot has feature of being highly flexible and configurable. As far as drawback are concerned, chatbot can be made much faster in response from user and excel sheets needs to be regularly updated to provide constantly changing situations of COVID-19. As sky is the limit while building a chatbot, therefore many scopes exists for building a chatbot like very attractive front-end, more classification of sentiment analysis and more sophisticated system to give recommendations to user.

Execution of project:
To run the provided script of Server.py and Client.py, view the document file named Project_Chatbot_Working_Demo.

Refer link to view presentation of project:
https://www.youtube.com/watch?v=R0PgcOl-Vhc&feature=youtu.be
