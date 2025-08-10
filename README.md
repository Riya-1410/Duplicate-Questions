# 📝 Quora Duplicate Question Pairs – NLP Starter

A simple, beginner-friendly project to check if two Quora questions mean the same thing using **Natural Language Processing (NLP)** and **Machine Learning**.

---

## 🚀 What it does
- Cleans question text (lowercase, remove punctuation & stopwords)  
- Converts text to numbers using **TF-IDF**  
- Trains a **Logistic Regression** model  
- Predicts if two questions are **duplicates** or **not**  

---

## 📂 How to use
1. Download `train.csv` from [Kaggle](https://www.kaggle.com/c/quora-question-pairs)  
2. Place it in the same folder as the notebook  
3. Open the notebook and run all cells in order  
4. Test with your own question pairs!  

---

## 📦 Requirements
```bash
pip install pandas numpy scikit-learn nltk scipy
