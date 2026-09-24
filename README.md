# IMDb Sentiment Analysis

## Overview

A Natural Language Processing project for classifying IMDb movie reviews as positive or negative.

## Dataset

IMDb Dataset containing 50,000 movie reviews.

The dataset is downloaded using KaggleHub.

## Technologies

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* WordCloud
* TF-IDF
* Logistic Regression
* Naive Bayes

## Preprocessing

The text was preprocessed using:

* Lowercasing
* HTML removal
* URL removal
* Removing non-alphabetic characters
* Stopword removal
* Lemmatization

## Feature Extraction

TF-IDF was used to convert the reviews into numerical feature vectors.

Both unigrams and bigrams were used.

## Models

### Logistic Regression

A Logistic Regression classifier was trained to classify reviews into:

* Positive
* Negative

### Naive Bayes

Multinomial Naive Bayes was also tested for comparison.

## Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

## Visualization

The project includes:

* Confusion Matrix
* Positive Word Cloud
* Negative Word Cloud
* Most important features

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then open:

`IMDb_Sentiment_Analysis.ipynb`

Run the notebook cells sequentially.

## Project Structure

```text
IMDb-Sentiment-Analysis/
│
├── IMDb_Sentiment_Analysis.ipynb
├── README.md
└── requirements.txt
```
