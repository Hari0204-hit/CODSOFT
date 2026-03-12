# Credit Card Fraud Detection 💳

## Project Overview

This project builds a Machine Learning model that detects **fraudulent credit card transactions**.

Financial institutions use such systems to prevent fraud and protect customers from unauthorized transactions.

This project was completed as part of the **Machine Learning Internship at CODSOFT**.

---

## Dataset

The dataset contains anonymized credit card transaction features including:

* Transaction time
* Transaction amount
* PCA-transformed features (V1–V28)
* Transaction class

Where:

* **0 → Legitimate Transaction**
* **1 → Fraudulent Transaction**

---

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Machine Learning Classification

---

## Machine Learning Workflow

1. Load dataset
2. Data preprocessing
3. Feature and label separation
4. Train/Test split
5. Train machine learning model
6. Evaluate model accuracy
7. Detect fraudulent transactions

---

## Model Used

**Random Forest Classifier**

Random Forest is effective for fraud detection because it can handle complex patterns and large datasets.

---

## Example Output

```
Transaction Prediction: Fraudulent
```

or

```
Transaction Prediction: Legitimate
```

---

## Project Structure

```
Credit_Card_Fraud_Detection
 ├ credit_card_fraud_detection.ipynb
 ├ fraud_detection_model.pkl
 └ README.md
```

---

## Author

Harikesh S
Machine Learning Internship – CODSOFT
