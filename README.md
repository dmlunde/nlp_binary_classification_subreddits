### README.md

### Problem Statement
Accurately predicting the subreddit of a submission based on its title and self text by building a machine learning NLP model.

### Our Dataset
We have 6,000 total submissions from 2 different subreddits. There is text within the submissions found in the title and selftext.

### Data Hyperlinks to Subreddits:
- https://www.reddit.com/r/PoliticalDiscussion/
- https://www.reddit.com/r/NeutralPolitics/

### EDA
To begin I webscraped the data using the PushShift API. I then pre-processed the data using Tokenization, adding Stopwords, Stemming and Lemmatization. Now that the data was clean I was able to more accurately visualize, analyze and explore the data.

### Modeling
Logistic Regression was my initial model but I also used a Multinomial Naive Bayes and experimented with Support Vector Classifiers among others. Every model I designed was tested with Count & TFIDF Vectorized data so I could compare the differences between the Vectorizers. Each model and Vectorizer was also run through Grid Searches and Pipelines to efficiently test multiple hyper parameters.

### Conclusion:
I successfully created a model that could accurately predict which of the 2 subreddits any given post came from with a 95+% accuracy. Due to the political nature of the content, the most popular words and strongest coefficients were Donald Trump and the various combinations and iterations of the name. Also popular were other Presidential candidate's names and other topics such as impeachment, war, iran, the economy etc.


### Project 3 Executive Summary

You have 2 similar subreddits and want to be able to predict which of the 2 any random submission comes from based solely on its title and selftext huh? Well, hire me then, because I just did that.

Reddit is a mixed bag full of hits and misses when it comes to audience and content, but if you can filter your feed wisely it truly is a treasure trove. Natural Language Processing is an intuitive way to analyze the bountiful text contained within Reddit. You have many subreddits that are quite alike in purpose and content. It'd save you a lot of time and energy if you could automate a process that classifies which subreddit out of the similar subreddits any random post came from. I specifically used NLP to do that on two popular subreddits whose purposes are to facilitate polite discussion about politics using empirical facts and neutrality. Political Discussion and Neutral Politics were my targets and I successfully built a powerful model to predict which subreddit a random submission came from solely based on its title and selftext with a 95+% accuracy rate.

I love working with smart companies with extensive datasets and text that need analyzing. If you're ready to increase your profits, effectiveness and efficiency, I'm ready to take you there. This project shows what I am capable of. Hit me up for your next NLP/Data Science project my future client!
