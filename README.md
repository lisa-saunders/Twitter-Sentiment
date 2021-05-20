# Twitter Sentiment Analysis: Climate Change

Lisa Saunders

Ironhack Final Project

DAFT REM MAR21

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-questions)
- [Dataset](#dataset)
- [Organization](#organization)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Workflow](#workflow)
- [Links](#links)

## Project Description



## Dataset

Included in the dataset are 108.293 tweets from May 30th, 2021 until May 17th, 2021 with the following contents:

- Climate change
- Global warming

filtered by:

- English language
- Without retweets
- Without replies

And 11.041 tweets with users located in the US from January 6th, 2019 to May 18th, 2021, with the following contents:

- Climate change
- Global warming
- Climate hoax

filtered by:

- English language
- Without retweets
- Without replies

The tweets are scraped from Twitter using snscrape - info on snscrape can be found here: https://github.com/JustAnotherArchivist/snscrape

## Organization

File Structure:

```
├── README.md            <- README to explain project motivation
├── Data                 <- Cleaned datasets
│
├── Notebooks            <- Jupyter notebooks
│
└── Figures             <- Important graphs and figures

```


## Cleaning

Cleaned the dataset from URLS, emojis and other special characters. Cleaned text for natural language processing using tokenization, lemmatization. Extracted popular hashtags and mentions.

## Analysis
* Sentiment analysis with the vader library
* Analysis for both world wide data and US data only
* Analysis by month, city and time for the US data
* Wordclouds for popular hashtags, mentions and common words
* Classifying tweets into popular topics using Non-Negative Matrix Factorization (NMF)

## Conclusion
* Sentiment overall mostly stable, with more neutral and positive sentiment than negative
* Very popular topic with high polarity and anger

## Future Work
* Classifying tweets into climate believers and deniers


## Links

[Repository](https://github.com/lisasaundersgit/Twitter-Sentiment)  
[Slides](https://www.canva.com/design/DAEfAU94HIc/wc6z_Ifg4ep6JGOrWhUeKA/view?utm_content=DAEfAU94HIc&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)  
[Organization on Notion](https://www.notion.so/Twitter-Climate-Change-Sentiment-641d64af5efb46acb311acc7c810e9f7)  
