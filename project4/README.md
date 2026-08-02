# NLP Sentiment Analysis Using Machine Learning

## Project Description

This project is based on **Natural Language Processing (NLP)** and **Machine Learning**. The main objective is to classify Amazon product reviews into **Positive** and **Negative** sentiments. The review text is first cleaned using NLP techniques, then converted into numerical features using **TF-IDF Vectorization**, and finally classified using the **Multinomial Naive Bayes** algorithm.

---

## Objectives

- Perform text preprocessing using NLP techniques.
- Convert text into numerical features using TF-IDF.
- Train a Machine Learning model for sentiment classification.
- Predict whether a review is Positive or Negative.
- Evaluate the model using different performance metrics.

---

## Dataset

**Dataset Name:** Amazon Fine Food Reviews

**Columns Used:**

- Text
- Score

### Sentiment Labels

| Score | Sentiment |
|-------|-----------|
| 1–2 | Negative |
| 3 | Neutral (Removed) |
| 4–5 | Positive |

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

---

## Libraries

```python
pandas
numpy
nltk
matplotlib
seaborn
scikit-learn
re
string
```

---

## Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Explore the dataset.
4. Create sentiment labels from review scores.
5. Clean and preprocess the review text.
6. Remove punctuation and stop words.
7. Perform tokenization and lemmatization.
8. Convert text into TF-IDF vectors.
9. Split the dataset into training and testing sets.
10. Train the Multinomial Naive Bayes model.
11. Predict sentiments for test reviews.
12. Evaluate the model.
13. Test the model using custom reviews.

---

## Text Preprocessing

The following preprocessing techniques are applied:

- Convert text to lowercase
- Remove punctuation
- Tokenization
- Remove stop words
- Lemmatization

---

## Feature Extraction

TF-IDF (Term Frequency–Inverse Document Frequency) is used to convert text into numerical vectors that can be processed by the machine learning model.

---

## Machine Learning Model

**Algorithm Used**

- Multinomial Naive Bayes

---

## Evaluation Metrics

The model is evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Sample Prediction

**Input Review**

```
This product is amazing and works perfectly.
```

**Predicted Output**

```
Positive
```

---

## Features

- Data preprocessing
- Sentiment label creation
- Text cleaning
- TF-IDF Vectorization
- Machine Learning classification
- Sentiment prediction
- Model evaluation
- Confusion Matrix visualization

---

## Applications

- Product review analysis
- Customer feedback analysis
- Business intelligence
- E-commerce platforms
- Opinion mining
- Social media sentiment analysis

---

## Future Improvements

- Use Support Vector Machine (SVM) for comparison.
- Implement Deep Learning models such as LSTM.
- Build a web application using Flask or Streamlit.
- Add multi-class sentiment prediction.
- Deploy the model for real-time predictions.

---

## Conclusion

This project demonstrates how Natural Language Processing and Machine Learning can be combined to automatically classify customer reviews into Positive and Negative sentiments. The complete NLP pipeline, including text preprocessing, TF-IDF vectorization, model training, and evaluation, provides an efficient solution for sentiment analysis on textual data.

---

## Author

**Name:** Zainab Sarfraz
