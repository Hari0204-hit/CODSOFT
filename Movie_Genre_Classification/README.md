# Movie Genre Classification 🎬

## Project Overview

This project builds a Machine Learning model that predicts the **genre of a movie based on its plot summary** using Natural Language Processing (NLP).

The system converts movie plots into numerical features using **TF-IDF vectorization** and then trains a classification model to predict genres such as **Action, Comedy, Crime, Drama, Horror, Romance, Thriller, and Western**.

This project was developed as part of the **Machine Learning Internship Task at CODSOFT**.

---

## Dataset

Dataset used: **Wikipedia Movie Plots Dataset**

The dataset contains:

* Movie titles
* Plot summaries
* Genres
* Other metadata

For this project, only the following columns were used:

* **Plot** – Movie storyline
* **Genre** – Movie category

---

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Machine Learning Classification

---

## Machine Learning Workflow

The project follows the standard ML pipeline:

1. Dataset Download
2. Data Cleaning
3. Genre Label Processing
4. Dataset Balancing
5. Text Vectorization using TF-IDF
6. Train/Test Split
7. Model Training
8. Model Evaluation
9. Genre Prediction

---

## Model Used

The project uses a **Multinomial Naive Bayes classifier**, which is commonly used for text classification problems.

---

## Example Prediction

Example input:

Movie Plot:
A detective investigates a brutal murder in a small town.

Predicted Genre:
Crime

---

## Project Structure

```
CODSOFT
 └── Movie_Genre_Classification
      ├ movie_genre_classification.ipynb
      ├ movie_genre_model.pkl
      ├ tfidf_vectorizer.pkl
      └ README.md
```

---

## How to Run the Project

1. Clone the repository
2. Install required libraries

```
pip install pandas scikit-learn kagglehub
```

3. Run the notebook:

```
movie_genre_classification.ipynb
```

---

## Author

Harikesh S

Machine Learning Internship – CODSOFT
