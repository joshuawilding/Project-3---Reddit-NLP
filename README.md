# Project 3: Reddit NLP

This project utilized two newly acquired data science tools: web scraping and Natural Language Processing. The goal was to use Reddit's API to gather posts from two different subreddits, then train an NLP  classification model to determine whcih subreddit each post came from.

For my project, I used a wrapper for Reddit's API called [PRAW](https://praw.readthedocs.io/en/latest/getting_started/quick_start.html) to gather my text data. This proved easier and more reliable than "manually" scraping Reddit, which I spent hours fruitlessly trying.

At this point in the course, I had learned a wide variety of different classifiers, including decision trees, logistic regression, and K-nearest neighbors. My approach was to throw all of theat my data and see what gave the highest score. We had also just learned about NLP tools, so I enjoyed experimenting with different wordcount vectorizers, lemmatizers, stemmers, and stop-words.

The presentation for this project was geared toward a technical audience, so it was more code heavy than prior projects.
