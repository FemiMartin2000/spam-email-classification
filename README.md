# spam-email-classification
A machine learning project focused on classifying emails as spam or ham using natural language processing (NLP) techniques such as tokenization, stemming, and various classification models.
Below is an updated README.md that reflects your project as an IPython Notebook file:

```markdown
# Spam Email Classification

This repository demonstrates a complete machine learning pipeline for classifying emails as spam or ham using a Jupyter Notebook. The project covers data preprocessing, feature extraction, and model evaluation using NLP techniques.

## Overview

The pipeline includes the following steps:

- **Data Loading:** Reads the dataset from `SPAM.csv` containing emails labeled as 'spam' or 'ham'.
- **Preprocessing:**  
  - **Tokenization:** Splits text messages into individual words.
  - **Stemming:** Uses NLTK’s Snowball Stemmer to reduce words to their root form.
  - **Lemmatization:** Applies WordNetLemmatizer to convert tokens to their base form.
  - **Stopword Removal:** Eliminates common stopwords to improve feature quality.
- **Feature Extraction:** Converts processed text into numerical features using TF-IDF.
- **Classification:**  
  - Trains and evaluates models using **Logistic Regression** and **LinearSVC**, both achieving an accuracy of 87.5% on the dataset.

## Files

- **spam_classification.ipynb:** The main Jupyter Notebook containing the full pipeline.
- **SPAM.csv:** The dataset file with spam and ham emails.

## Setup & Usage

### Prerequisites

- Python 3.x
- Jupyter Notebook

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

3. **Download NLTK Resources:**

   You can download the necessary NLTK resources by running the following commands in a Python shell or in a notebook cell:

   ```python
   import nltk
   nltk.download('stopwords')
   nltk.download('wordnet')
   ```

### Running the Notebook

1. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Open the `spam_classification.ipynb` file.
3. Run the cells sequentially to execute the pipeline.


