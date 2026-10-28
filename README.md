# IMDb Movie Review Sentiment Analysis using NLP

## 📌 Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning to classify IMDb movie reviews as positive or negative based on their text.

The project converts textual reviews into numerical features using TF-IDF vectorization and uses a K-Nearest Neighbors (KNN) classifier to predict sentiment.

## 🎯 Objectives

- Understand and process textual movie reviews.
- Convert text into numerical features using TF-IDF.
- Train a machine learning classification model.
- Predict the sentiment of new movie reviews.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- K-Nearest Neighbors (KNN)
- Jupyter Notebook

## 📂 Resource

```text
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?resource=download
```

## ⚙️ Project Workflow

1. Load the IMDb movie review dataset.
2. Explore and prepare the review text and sentiment labels.
3. Convert the reviews into numerical features using TF-IDF.
4. Split the data into training and testing sets.
5. Train the KNN classification model.
6. Predict sentiment for unseen reviews.
7. Test the model with a new movie review.

## 💻 Example

Input review:

`The movie is very nice`

Example output:

`Sentiment: Positive`

*The prediction depends on the trained model.*

## 📈 Future Improvements

- Experiment with Logistic Regression, Naive Bayes, and other classifiers.
- Evaluate performance using accuracy, precision, recall, and F1-score.
- Improve text preprocessing and feature selection.
- Build a simple web application for interactive sentiment prediction.

