# 📩 SMS Spam Classifier Web App

This project is a **machine learning-based web application** that classifies **SMS messages as Spam or Not Spam**, helping users filter unwanted texts effectively.

---

## ✅ Key Features

- 📝 **Text Preprocessing**  
  - Lowercasing  
  - Punctuation removal  
  - Stopwords removal  
  - Stemming using NLTK

- 🔢 **Vectorization**  
  - **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert text into numerical features

- 🧠 **Model**  
  - Trained **Naive Bayes classifier (MultinomialNB)** for accurate spam detection

- 🌐 **Web Interface**  
  - **Frontend**: HTML & CSS  
  - **Backend**: Flask application to handle user input and display predictions

---

## 📂 Tech Stack

- **Languages & Libraries**: Python, NLTK, Scikit-learn, Flask  
- **Frontend**: HTML, CSS  
- **Persistence**: Pickle for saving/loading the model and vectorizer
