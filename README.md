This project included:
- Extracting synonymous words to create a network
- Extracting tweets from the London area
- Training a topic modelling algorithm on these tweets
- Analysing similarity of tweets for whole dataset and within topics
- Using the network of synonyms in conjunction with topic model to bring additional insight to similarity analysis

The code is briefly explained below:

Words.ipynb : Reads in synonyms csv taken from Kaggle. Cleans this data and creates a new file with edges from synonymous words.
Network_analysis.ipynb : Performs analysis of network of synyonms created using file with edges from previous code.
twitter analysis.ipynb : Extracts tweets using Twitter API from the London area and applies Topic Modelling algorithm. Similarity of Tweets analysis is performed here.
