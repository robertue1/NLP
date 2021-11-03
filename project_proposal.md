# Analyzing users opinions on the Worn Wear hashtag in Twitter. 


## Need:

Patagonia is a brand that prides on their efforts towards being a sustainable company. As part of their 
strategy, they have implemented the program _Worn Wear_, with the idea of encouraging their users to give a 
longer lifespan to any Patagonia product. Initially, if your jacket or pants break, you will send it to Patagonia
to fix it for free, recently, the project evolve into an [online store](https://wornwear.patagonia.com) of used products. 

To understand which are the drivers for people to be part of the _Worn Wear_ project, more than 1500 tweets including the hashtag
will be analyzed, using NLP techniques to obtain the main topics of conversations. 


## Data Description:

For this project, I'll use **tweets**; Twitter API keys will be required, in conjuction with some other libraries like
_Tweepy and SNSCRAPE_. 

For each tweet, the data includes: _text, date and time, number of retweets and likes, userid_. Initially, my main goal is to work
with the text, to be able to determine which are the main topics present in the conversations. 


## Tools:

The libraries previously mentioned, as well as Numpy, Pandas, NLTK, SpaCy, and matplotlib and seaborn for visualizations. 

## MVP Goal:

Obtain an initial version of the topics discussed within the corpus of my tweets. 
