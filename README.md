# NLP-Homework

#### Background

In this assignment, natural language processing has been used to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. Also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

#### Analysis Steps:

- Sentiment Analysis
- Natural Language Processing
- Named Entity Recognition

#### Sentiment Analysis:

Used the newsapi to pull the latest news articles for Bitcoin and Ethereum and created a DataFrame of sentiment scores using vader sentiment analysis for each coin. Used descriptive statistics to answer following question:

Q: Which coin had the highest mean positive score?

A: Bitcoin's mean positive score (0.058200) is higher than Ethereum's mean positive score (0.053050)

Q: Which coin had the highest compound score?

A: Ethereum's max compound score (0.757900) is higher than Bitcoin's mean positive score (0.680800)

Q. Which coin had the highest positive score?

A: Ethereum's max positive score (0.21700) is higher than Bitcoin's max positive score (0.185000)

#### Natural Language Processing:

In this section, used NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both coins.

- Tokenize

  - Lowercase each word.
  - Remove punctuation.
  - Remove stop words.

- N-grams: Next, looked at the ngrams and word frequency for each coin.

  - Used NLTK to produce the ngrams for N = 2
  - Listed the top 10 words for each coin

- Word Clouds
Finally, generated word clouds for each coin to summarize the news for each coin.

#### Named Entity Recognition (NER)

In this section, built a named entity recognition model for both coins and visualize the tags using SpaCy.

