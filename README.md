## ChatGPT Tweet Analysis
ChatGPT, developed by OpenAI, is a state-of-the-art conversational AI that leverages the GPT (Generative Pre-trained Transformer) architecture. It excels at understanding and generating human-like text, enabling it to assist in diverse tasks such as answering questions, drafting text, explaining concepts, and more. Worked on Twitter data to understand public sentiment and engagement around ChatGPT during January to March 2023. 
Here's an overview of the key components based on the analysis:

# Objective
The primary goal is to examine public perception, temporal trends, influential topics, and sentiment variations related to ChatGPT. 
The study also seeks to identify influential users and hashtags while understanding tweet dynamics like likes and retweets.

# Key Points in the Analysis
1. Data Understanding
Data sourced from Kaggle included tweets mentioning "ChatGPT."
Explored dataset structure, including key variables like timestamp, user details, hashtags, and sentiment scores.
2. Data Preprocessing
Cleaned data by removing duplicates, null values, and irrelevant content (e.g., links and non-English text).
Performed text normalization steps such as tokenization, stemming, and lemmatization.
Prepared structured data for sentiment analysis and visualization.
3. Exploratory Data Analysis (EDA)
Likes vs. Retweets: Analyzed the relationship between likes and retweets, identifying which tweets gained more traction and why.
Temporal Trends: Studied daily, weekly, and monthly tweet patterns, showing peaks in discussions around ChatGPT updates or controversies.
Top Hashtags and Usernames: Identified frequently used hashtags (e.g., #AI, #ChatGPT) and influential accounts driving the conversation.
Most Liked Tweets: Highlighted tweets with the highest likes, often promotional or humorous content.
Influential Users: Used metrics like follower count and engagement to pinpoint key users.
4. Sentiment Analysis
Overall Sentiment: Categorized tweets into positive, negative, and neutral using TextBlob and NLTK's Vader Sentiment Intensity Analyzer.
Sentiment on Topics and Accounts: Explored sentiment variations across popular topics (e.g., ethical concerns, technical advancements) and specific user accounts.
