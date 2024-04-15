# CSCC Mentor Project 2023-24
A collaborative Machine Learning Project for CSCC Mentorship Program 2023-2024. In this project we will walk through several "real world" scenarios of what it is like to build an ML Project as an Machine Learning Engineer. Major goals of the project include: 1) Code Collaboration, 2) Learning to work with Python and 3) walking through the steps of building an ML Application. 4) A "case study" evaluating XGBoost.


## Learning Objectives
- Learn To Collaborate in a Repo
    - Submitting Code reviews
    - Completing new features
    - Merging code

- Learn to Work in Python
    - Setup an IDE
    - Setup an Environment
    - Work in a Notebook

- Complete Steps in a "real" ML Project
    - Data Gathering
    - Data Labeling
    - Data Cleaning
    - Model Training
    - Model Serving (HTTP API)
    - Model Evaluation
    - Bonus: UI App

## Project Overview
The ML App will take some text as an input and then make an estimate on the sentiment of the text. We will be using reviews from Yelp and out ML model will guess if the review is positive, neutral or negative. 

## Authors
Margo Riordan [margoriordan](https://github.com/margoriordan)

Weston Bassler [geekbass](https://github.com/geekbass)

## Case Study
Can XGBoost be used to classify sentiment of text?

## Evaluation and Results
Using <a href="https://www.kaggle.com/datasets/ilhamfp31/yelp-review-dataset">this dataset</a> as ground truth, a comparison was made against the trained model. 402490 out of 560000 matches were found, evaluating to just under 72% accuracy. While it would be possible to try for more favorable results through retraining the model with adjusted hyperperameters, results are expected to remain relatively similar. XGBoost may not be the best fit for sentiment analysis of text as the model does not consider overall context in the same fashion as deep learning can.
