
# Restaurant-review-sentiment-analysis

# About the project

Sentiment analysis is the process of analyzing digital text to determine if the emotional tone of the message is positive, negative, or neutral. This model focuses on restaurant reviews and classify it into two categories satisfactory or unsatisfactory.


# Working 

# 1. Model Training phase

1. Importing the dataset
Using pandas the restaurant reviews dataset is imported and stored in dataset variable

2. Text cleaning
The text is cleaned by first dividing it into [tokens](https://nlp.stanford.edu/IR-book/html/htmledition/tokenization-1.html) then removing the [stopwords](https://www.geeksforgeeks.org/removing-stop-words-nltk-python/) and perform [stemming](https://www.geeksforgeeks.org/introduction-to-stemming/) and [lemmatization](https://www.geeksforgeeks.org/python-lemmatization-with-nltk/)

3. [Tfidf Vectorization](https://www.geeksforgeeks.org/understanding-tf-idf-term-frequency-inverse-document-frequency/)
Using the tfidf vectorizer create a matrix representation of the given textual data which will be an essential part of model creation.

4. Training the model
Use the train_test_split from scikit-learn library to split data into training and testing datasets.
Train the classification model using RandomForestClassifier.

# 2. Model Testing phase
1. Calculating the evalutaion metrics
Calculate the confusion matrix and accuracy score.

2. Make Prediction
Provide a sample review for prediction and check prediction accuracy.

# 3. Saving the model

Use the joblib libraryto save the weights of classification model and also save the weights of tfidf vectorizer

# Getting Started

# Dependencies




Numpy
```bash
  pip install numpy
```
Pandas
```bash
  pip install pandas
```
Matplotlib
```bash
  pip install matplotlib
```
Scikit-learn
```bash
  pip install scikit-learn
```
NLTK
```bash
  pip install nltk
```
Joblib
```bash
  pip install joblib
```

## Installation

1. Clone the repository
```bash
    git clone https://github.com/KaleAtharva/Restaurant-review-sentiment-analysis.git
```

## Frontend

Frontend implemented using ReactJS.

1. Link to the Frontend React repository.

```bash
    https://github.com/KaleAtharva/mini-project
```
## Flask API

API implemented using python flask.

1. Link to the Flask repository

```bash
    https://github.com/KaleAtharva/sentiment-analysis-flask-api
```
## Authors

- [@Atharva Kale](https://github.com/KaleAtharva)

