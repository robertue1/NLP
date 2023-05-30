# Analyzing tweets of the 'wornwear' campaign by Patagonia
NLP and Unsupervised Learning

# Abstract

By gathering more than 3000 tweets associated with the hashtag #WornWear, we identified latent topics in the conversation around the #WornWear campaign by Patagonia, obtaining insights about the topics that generated the most interactions and likes. From the findings, we could provide recommendations to increase focus on the aspects that resonate the most within the community. 

# Design

EDA was applied in a highly iterative way to achieve the project's goal. I initially built a base NMF model, generating the first topics and applying a more thorough approach in the preprocessing to improve the topics' quality. After the results from NMF seemed correct, I applied a semi-supervised approach with CorEx in order to dig deeper for some keywords I was interested in finding.  

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
