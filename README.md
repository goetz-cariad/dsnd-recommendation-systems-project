# NLP Pipeline Project
A project from the [udacity Data Scientist nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025).  
We follow along a partially prepared Jupyter notebook, complete code and give answers to checks in between.

## Date created
March 25 2026

## Motivation / Scenario

For this project we analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they will like.


## Features
### I. Exploratory Data Analysis

Before making recommendations of any kind, we explore the data we are working with for the project.  
There were some basic, required questions to be answered about the data we were working with throughout the rest of the notebook. 

### II. Rank Based Recommendations

To get started in building recommendations, we first found the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

### IV. Content Based Recommendations

Since we are provided some content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, we'll come up with a simple method to cluster similar articles together so we can recommend related content that the user may have already interacted with.

### V. Matrix Factorization

Finally, we complete a machine learning approach to building recommendations. Using the user-item interactions, we built out a matrix decomposition. Using the decomposition, we got an idea of how well you can predict new articles an individual might interact with.  
Finally we discuss which methods we might use moving forward, and how we might test how well the recommendations are working for engaging users.


## Getting started
### Prerequisites
- Python >= 3.13.7
- (Jupyter) notebook
- pandas
- numpy
- scikit-learn
- matplotlib

(exact versions for packages to be found in requirements.txt)

### Installation
1. Clone the repo:
    ``` git clone <repository-url> ```
2. Install the requirements
    ``` pip install requirements.txt ```


## Files
- Recommendations_with_IBM.ipynb - The main Jupyter notebook containing all code and comments
- Recommendations_with_IBM.html - html export of the Jupyter notebook
- requirements.txt - necessary python libraries to install
- /data folder containg
    - raw data file (user-item-interactions.csv)
- top_5.p - solution file for recommendations, needed for test cells in notebook
- top_10.p - solution file for recommendations, needed for test cells in notebook
- top_20.p - solution file for recommendations, needed for test cells in notebook


## Acknoledgements
- Credits for setting up this challenge go to the [udacity](https://www.udacity.com/) team.
