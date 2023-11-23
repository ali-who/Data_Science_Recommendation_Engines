# Data Science Recommendation Engines

### Experimental Design Use in Business
Completing this project helped me understand the role that experiment design and testing can play in product design and development. It also provided me with a solid background in the different types of recommendations that can be provided, how recommendation engines work, and how I can evaluate the quality of a recommendation engine.

# Project Details

## Introduction
For this project, I will analyze users' interactions with articles on the IBM Watson Studio platform, and make recommendations to them about new articles I think they will like.

To determine which articles to show to each user, I will be performing a study of the data available on the IBM Watson Studio platform. I can create my account to become a part of their community and get a better understanding of their data by creating an account on the platform [here](https://eu-gb.dataplatform.cloud.ibm.com/login?preselect_region=true).

### Tasks
The project will be divided into the following tasks

I. Exploratory Data Analysis

Before making recommendations of any kind, I will need to explore the data I am working with for the project. Dive in to see what I can find. There are some basic, required questions to be answered about the data I am working with throughout the rest of the notebook.

II. Rank Based Recommendations

To get started in building recommendations, I will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

To build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to similar users. This would be a step in the right direction towards more personal recommendations for the users. I will implement this next.

IV. Content Based Recommendations

Given the amount of content available for each article, there are several different ways in which someone might choose to implement a content-based recommendations system. Using NLP skills, I might come up with some extremely creative ways to develop a content-based recommendation system.

V. Matrix Factorization

Finally, I will complete a machine-learning approach to building recommendations. Using the user-item interactions, I will build out a matrix decomposition. Using I decomposition, I will get an idea of how well I can predict new articles an individual might interact with (spoiler alert - it isn't great). I will finally discuss which methods I might use moving forward, and how I might test how well my recommendations work for engaging users.

This project was completed on: 10/10/23
