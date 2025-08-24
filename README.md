#  Tweet Sentiment Analysis

This project performs **sentiment analysis on tweets** using Natural Language Processing (NLP) and Machine Learning.  
It cleans raw tweet text, extracts features using **TF-IDF**, and trains a **Logistic Regression** classifier to predict sentiment.

---

##  Features
- Data preprocessing:
  - Lowercasing
  - Removing URLs, hashtags, mentions
  - Removing punctuation & stopwords
- Feature Extraction:
  - **TF-IDF Vectorizer**
  - CountVectorizer (for comparison)
- Model Training:
  - **Logistic Regression**
- Model Evaluation:
  - Accuracy score
  - Classification report (Precision, Recall, F1-score)

---

##  Tech Stack
- **Python**
- **Libraries**:
  - numpy
  - pandas
  - scikit-learn
  - nltk
  - re (regex)

---

##  Dataset
The dataset (`tweets.csv`) contains:
- **text** → tweet content  
- **label** → sentiment category (positive/negative or other classes depending on dataset)  

