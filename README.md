# movie-genre-classification
Machine Learning  model to predict movie genres from plot summaries

# 🎬 Movie Genre Classification (ML Project)

This project builds a machine learning model that predicts a movie's genre based on its plot summary. It's built using Python, Scikit-learn, and text vectorization techniques like TF-IDF.

---

## 📂 Files

- `movie_genre_classification.ipynb` – Main Google Colab notebook (code + output)
- `predicted_genres.zip` – Compressed CSV file of predicted genres (unzip to view full results)
- `test_data.txt`, `train_data.txt` – Source data files (from Kaggle)

---

## 🧠 What the Model Does

- Cleans and processes the training data
- Converts plots into numerical vectors using TF-IDF
- Trains a Logistic Regression model
- Evaluates model using accuracy and classification report
- Predicts genres for unseen movie descriptions

---

## 📊 Libraries Used

- `pandas`, `scikit-learn`, `nltk`, `re`
- Vectorization: `TfidfVectorizer`
- Model: `LogisticRegression`

---

## 📦 Dataset Source

- From Kaggle: [Genre Classification Dataset (IMDb)](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb)

---

## ✨ Output Preview

Example:

Movie: Ghost in the Mirror --> Predicted Genre: Horror
Movie: A Love Again --> Predicted Genre: Romance


## 🧳 How to Use

1. Clone or download the repo
2. Unzip `predicted_genres.zip` to view results
3. Open the `.ipynb` notebook to view full code and training steps
