# Sentiment-Analysis-using-NLP
📊 Text Classification - SMS Spam Detection
This project implements a text classification pipeline to detect spam messages in SMS data using traditional machine learning models such as Naive Bayes and Random Forest.

📁 Dataset
The dataset used is SMSSpamCollection, a corpus of SMS messages labeled as ham (non-spam) or spam.
Format:

label: 'ham' or 'spam'

message: the SMS text

🧠 Models Implemented
Multinomial Naive Bayes

Random Forest Classifier

Both models are trained on text features extracted using:

Bag of Words

TF-IDF Vectorization

🧪 Evaluation Metrics
Models are evaluated using:

Accuracy

Confusion Matrix

Precision, Recall, F1-score

| Model         | Accuracy     | Notes                                   |
| ------------- | ------------ | --------------------------------------- |
| Naive Bayes   | \~98.7%      | Very high precision on spam class       |
| Random Forest | \~98.5–98.9% | Excellent balance of recall & precision |

🔄 Pipeline Overview
Text Preprocessing:
Lowercasing, removing punctuation, stemming, stopword removal.

Feature Extraction:

CountVectorizer

TfidfVectorizer

Train-Test Split

Model Training:

Naive Bayes

Random Forest

Evaluation & Reporting

🛠 Tech Stack
Python

Pandas

Scikit-learn

NLTK

Jupyter Notebook


Accuracy: 0.9865
Confusion Matrix:
[[947   8]
 [  7 153]]

Precision, Recall, F1:
spam     => precision: 0.95 | recall: 0.96 | f1: 0.95
non-spam => precision: 0.99 | recall: 0.99 | f1: 0.99

