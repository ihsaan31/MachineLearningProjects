 Sentiment Analysis on Indonesian Insurance-Related Tweets
 
This is one of my Projects in PFI mega life, This is a Jupyter notebook created on Colab that demonstrates sentiment analysis on tweets related to Indonesian insurance. The notebook shows how to collect tweets using snscrape, preprocess text data, tokenize tweets, and remove stop words.

Data Collection
The code collects tweets related to Indonesian insurance from Twitter using the snscrape package. The query parameter is set to filter tweets between 2020-01-01 and 2023-02-26, with a limit of 5000 tweets.

Preprocessing Text Data
The preprocessing steps include replacing usernames, URLs, hashtags, and numbers with an empty string, converting text to lowercase, and replacing emojis with their text equivalents.

Tokenization
The tokenization process uses the nltk package to tokenize the tweets. The code then removes stop words from the tweets.

Note: The model used for sentiment analysis is not included in the code as it is not necessary for the preprocessing and tokenization steps.
