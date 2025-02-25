# spam-email-classification
A machine learning project focused on classifying emails as spam or ham using natural language processing (NLP) techniques such as tokenization, stemming, and various classification models.
Below is an updated README.md that reflects your project as an IPython Notebook file:

---

# Spam Classification Pipeline

This project classifies text messages as spam or ham using a Jupyter Notebook. The notebook demonstrates a complete machine learning pipeline—from data loading and NLP preprocessing (tokenization, stemming, lemmatization, and stopword removal) to TF-IDF feature extraction and classification with Logistic Regression and LinearSVC.

---

## Overview

- **Data Source:** `SPAM.csv` – contains text messages labeled as 'spam' or 'ham'.
- **Preprocessing Steps:**  
  - **Tokenization:** Splits messages into words.  
  - **Stemming:** Reduces words to their root form.  
  - **Lemmatization:** Converts words to their dictionary form.  
  - **Stopword Removal:** Eliminates common words that do not add significant meaning.
- **Feature Extraction:** Transforms text data into TF-IDF vectors.
- **Classification:** Uses Logistic Regression and LinearSVC, achieving an accuracy of 87.5%.

---

## Files

- **spam_classification.ipynb:** Main Jupyter Notebook containing the complete pipeline.
- **SPAM.csv:** Dataset file with the spam/ham messages.

---

## Setup & Usage

### Prerequisites

- **Python 3.x**
- **Jupyter Notebook**

### Installation

1. **Clone the Repository:**

   ```bash
  git clone https://github.com/FemiMartin2000/spam-email-classification.git
  cd spam-email-classification
   ```

2. **Install Required Packages:**

   ```bash
   pip install numpy pandas scikit-learn nltk

   ```





