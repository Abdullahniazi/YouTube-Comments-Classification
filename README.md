# YouTube-Comments-Classification
**This project was made as our final year project group members being me and https://github.com/abulaalafareh**

## Introduction:
This project is youtube comment classification. In this project we scrape and classify youtube comments into different categories based on their sentiments total sentiments being 16. We decided to get of the bubble of only positive, negative and neutral Sentiment and decided to increase the horizons for sentiment analysis. This can help YouTubers get insights into viewers perception, leading to informed decisions on how to improve viewer experience.

## Categories:

  * Appreciation
  * Recommendation
  * Sad
  * Hate
  * Greeting
  * Blessing
  * Quotation
  * Wish
  * Question
  * Love
  * Excitement
  * Request
  * Links
  * Others
  * Positive
  * Negative

## Working steps:

  * Scrape YouTube Save them to database
  * Perform Sentiment Analysis on each comment and save to database
  * Show in tabels

## Models:
We used different ML and DL models including Logistic Regression, SVM, KNN, Random Forest Classifier and BERT. Every model had accuracy around 75%-80% but the one which performed best on real time data was BERT. Total dataset was around 4700 which was mostly manually labeled as we could not find most of the categories data on the internet. Current BERT model was trained on a single epoch.

The model which is present in this repository is a logistic Regression Model because we did not find it feasible to upload BERT model as it was around 1.2gb. Instead Logistic Regression model is uploaded. Logistic Regression predictions cannot be compared to that of BERT but still are quite good.

## Requirments Libraries:

    pip install Tkinter
    pip install Joblib
    pip install functools
    pip install operator
    pip install string
    pip install sqlite3
    pip install pandas
    pip install --upgrade google-api-python-client
