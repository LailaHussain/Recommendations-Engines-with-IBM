# Recommendations Engines with IBM
Data Scientist Nanodegree

## Introduction
For this project I will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like.<br>

## Tasks
My project will be divided into the following tasks

### I. Exploratory Data Analysis

Before making recommendations of any kind, I will need to explore the data I am working with for the project. Dive in to see what I can find. There are some basic, required questions to be answered about the data I am working with throughout the rest of the notebook.

### II. Rank Based Recommendations

To get started in building recommendations, I will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. I will implement this next.

### IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. I am encouraged to complete a content based recommendation system, but not required to do so to complete this project.

### V. Matrix Factorization

Finally, I will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, I will get an idea of how well I can predict new articles an individual might interact with (spoiler alert - it isn't great). i will finally discuss which methods i might use moving forward, and how I might test how well my recommendations are working for engaging users.
