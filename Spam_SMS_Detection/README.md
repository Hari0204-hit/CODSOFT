# Spam SMS Detection 📩

## Project Overview

This project builds a Machine Learning model that detects whether an SMS message is **Spam** or **Legitimate (Ham)**.

Spam messages usually contain advertisements, scams, or phishing attempts. This model uses Natural Language Processing (NLP) techniques to classify messages automatically.

This project was developed as part of the **Machine Learning Internship at CODSOFT**.

---

## Dataset

The dataset contains SMS messages labeled as:

* **Ham** – Legitimate message
* **Spam** – Unwanted message

Example:

| Message                          | Label |
| -------------------------------- | ----- |
| Congratulations! You won a prize | Spam  |
| Hey, are we meeting today?       | Ham   |

---

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Natural Language Processing (NLP)

---

## Machine Learning Workflow

1. Load dataset
2. Text preprocessing
3. Convert text into numerical features using **TF-IDF**
4. Train/Test split
5. Train classification model
6. Evaluate model performance
7. Predict spam messages

---

## Model Used

**Multinomial Naive Bayes**

This algorithm works well for text classification tasks like spam detection.

---

## Example Prediction

Input message:

```
Congratulations! You won a free iPhone. Click the link now!
```

Prediction:

```
Spam Message
```

---

## Project Structure

```
Spam_SMS_Detection
 ├ spam_sms_detection.ipynb
 ├ spam_sms_model.pkl
 ├ sms_vectorizer.pkl
 └ README.md
```

---

## Author

Harikesh S
Machine Learning Internship – CODSOFT
