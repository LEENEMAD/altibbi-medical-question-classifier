# altibbi-medical-question-classifier
# Arabic Medical Text Classification

This project focuses on classifying Arabic medical questions from the Altibbi platform into appropriate medical specialties using Natural Language Processing (NLP) techniques.

##  Project Overview
The goal of this project is to help automatically route patient questions to the correct medical specialty by analyzing the text of their queries.

This is a challenging task due to the complexity of the Arabic language and the variability in how users write medical questions.

##  Dataset
- Source: Altibbi medical questions
- Language: Arabic
- Type: Patient-written queries
- Task: Multi-class classification (medical specialties)

##  Preprocessing
Applied multiple preprocessing techniques to handle Arabic text:
- Normalization
- Removing punctuation and stop words
- Removing harakat (diacritics)
- Tokenization (NLTK)
- Lemmatization using CAMeL Tools

##  Models & Techniques
Tested multiple approaches:

### Word Representations
- TF-IDF
- Bag of Words (BoW)
- Word2Vec
- FastText

### Models
- Logistic Regression
- Decision Tree
- Naive Bayes
- RNN
- LSTM
- BERT
- GPT

##  Results
- Best Model: **BERT**
- Accuracy: **90%**
- Transformer models significantly outperformed traditional and deep learning models due to better contextual understanding.

##  Tech Stack
- Python
- Scikit-learn
- NLTK
- CAMeL Tools
- PyTorch / Transformers
- NumPy / Pandas

##  Future Work
- Improve performance with larger datasets
- Deploy as a web application
- Fine-tune transformer models further

