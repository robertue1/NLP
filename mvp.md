# Topic Modeling of the #Wornwear hashtag. 


I... have done text-preprocessing, created a function ( _streamline(3, n_tweets= 5, n_words=10)_ ) that will take the number of topics, number of tweets and words to print out the folllowing output. 

<img width="992" alt="Screen Shot 2021-11-08 at 5 44 20 PM" src="https://user-images.githubusercontent.com/34829066/140830046-71d81816-445b-45ff-91be-50770d2b5ff4.png">

There are two more topics that won't fit in the image. So far... the only topic that I have been able to identify is the one related to 
peer to peer selling of Patagonia clothes on eBay. 

My workflow have been text-preprocessing, after the text is 'clean', I'm creating the corpus from that cleaned text, from there, appyling _tfidf_ and 
all of the processes for _NMF_. 

I have seen that I need to improve the text-preprocessing because those hyper-links that don't start with 'http' are 'passing' the processing, for example, 
links that start with 'youtube', 'instagram', 'bit', among others. 
After fixing that, I will like to implement lemmatization to see if it helps me improve my results and make sense out of my topics. 
When I get to this point, I'd like to create some visualizations and bring some insights. 
