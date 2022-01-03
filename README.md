# Analyzing tweets of the 'wornwear' campaign by Patagonia
NLP and Unsupervised Learning

# Abstract

By gathering more than 3000 tweets associated to the hashtag #WornWear, I was able to identify latent topics in the conversation around the #WornWear campaign by Patagonia, obtaining insights about what were the topics that generated the most interactions and likes. From the results of the findings, recommendations were made to increase the reach and efforts within the main topics. 

# Design

To achieve the goal of the project, EDA was applied in a highly iterative way. After building a base NMF model, obataining some initial topics, and applying a more throught approach in the preprocessing in order to improve the quality of the topics. When the results from NMF made sense, I applied a semi-supervised approach with CorEx in order to dig deeper for some key words I was interest in finding. 

# Data

Data set contains 3700 data points (tweets), including: username, bio, content of the tweets and the interactivity measures (retweets, likes, replies). 

# Algorithms

Data Acquisition: Initially used Tweepy to get the tweets, but after running into some limitations, I had to use the SNScrape as the tool for the tweets acquisition. 

Algorithms and techniques used for the topic modeling were Non-negative Matrix Factorization and CorEx. 


Numpy and Pandas for data manipulation
Scikit-learn for modeling
Matplotlib and Seaborn for plotting


# Communication

Submitted PDF slides and 5 minutes presentation.
