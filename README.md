# Unit-12-Tales from the Crypto Homework
![sentimental](https://user-images.githubusercontent.com/105663954/185003766-57a574ac-e77c-4118-8462-e847b13dd190.jpeg)
Background
There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.
In this assignment, you will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. You will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.
Complete the following tasks:

Sentiment Analysis
Natural Language Processing
Named Entity Recognition



Files
Starter Notebook


Instructions

1 - Sentiment Analysis
Use the newsapi to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.
Use descriptive statistics to answer the following questions:

Which coin had the highest mean positive score?
Which coin had the highest negative score?
Which coin had the highest positive score?


2 - Natural Language Processing
In this section, you will use NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both coins.

Tokenize
Be sure to:

Lowercase each word.
Remove punctuation.
Remove stop words.


N-grams
Next, look at the ngrams and word frequency for each coin.

Use NLTK to produce the ngrams for N = 2.
List the top 10 words for each coin.


Word Clouds
Finally, generate word clouds for each coin to summarize the news for each coin.



![btc-word-cloud](https://user-images.githubusercontent.com/105663954/185004376-72c9972e-839c-4e12-af1d-0dae528e8ebc.png)

![btc-ner](https://user-images.githubusercontent.com/105663954/185004425-d6f0fff0-8d88-4c49-97e8-26ee8c66b2d3.png)

![eth-word-cloud](https://user-images.githubusercontent.com/105663954/185004225-0923b09e-f1ed-43bd-b651-c5bbc6e826c8.png)

![eth-ner](https://user-images.githubusercontent.com/105663954/185004283-10471927-251e-4f6b-ba9b-ee34bd96575c.png)




3 - Named Entity Recognition
In this section, you will build a named entity recognition model for both coins and visualize the tags using SpaCy.



Resources
Vader Sentiment Analysis

Hints and Considerations
The free developer version of the News API limits the total daily requests, so be careful not to exceed the free limits.

Submission


Use the starter Jupyter Notebook provided to conduct the NLP analysis and host the notebook in a GitHub repository.


In your GitHub repository, include a ReadMe file that uses Markdown to summarize your homework.


Submit the link to your GitHub project to Bootcamp Spot.




Requirements

Sentiment Analysis  (30 points)

To receive all points, your code must:

Determine the coin with Highest Mean Positive Score. (10 points)
Determine the coin with Highest Negative Score. (10 points)
Determine the coin with Highest Positive Score. (10 points)


Natural Language Processing  (30 points)

To receive all points, your code must:

Use NLTK to lower case words, remove punctuation and remove stopwords. (8 points)
Use NLTK to produce n-grams. (8 points)
List the top 10 words for each Coin. (7 points)
Generate a Word Cloud for each Coin summarizing the news for each Coin. (7 points)


Named Entity Recognition  (10 points)

To receive all points, your code must:

Build a Named Entity Recognition model for both coins - Bitcoin and Ethereum - and visualized the tags for each coin using SpaCy. (10 points)


Coding Conventions and Formatting (10 points)

To receive all points, your code must:

Place imports at the beginning of the file, just after any module comments and docstrings and before module globals and constants. (3 points)
Name functions and variables with lowercase characters and with words separated by underscores. (2 points)
Follow Don't Repeat Yourself (DRY) principles by creating maintainable and reusable code. (3 points)
Use concise logic and creative engineering where possible. (2 points)


Deployment and Submission (10 points)

To receive all points, you must:

Submit a link to a GitHub repository that???s cloned to your local machine and contains your files. (5 points)
Include appropriate commit messages in your files. (5 points)


Code Comments (10 points)

To receive all points, your code must:

Be well commented with concise, relevant notes that other developers can understand. (10 points)
