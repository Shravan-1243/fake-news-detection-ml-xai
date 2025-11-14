# Fake News Detection with Machine Learning & Explainable AI (XAI) 📰🤖

This project builds an end-to-end **Fake News Detection** pipeline using NLP, classical machine learning models, and **SHAP-based explainability**.  
It includes data preprocessing, model training, evaluation, and a **Streamlit web app** for real-time prediction.

---

## 🚀 Key Features

- Text cleaning, stopword removal, and stemming using **NLTK**
- TF-IDF feature extraction with **scikit-learn**
- Classical ML models for binary classification (Real vs Fake)
- **SHAP** visualisations to explain model decisions
- Interactive **Streamlit** UI for users to paste news text and see predictions
- Flask deployment experiment included (`flask app/`)

---

## 🧠 Tech Stack

- Python 3
- scikit-learn
- pandas, numpy
- NLTK
- SHAP
- Streamlit
- Flask (alternative deployment)

---

## 📁 Project Structure

```text
app/           # Streamlit app + trained model and vectorizer
data/          # Datasets (Fake/True news, train/test splits, Politifact data)
flask app/     # Flask-based deployment experiment
images/        # Plots and screenshots (used in README / documentation)
notebooks/     # Jupyter notebooks for exploration and model training
README.md
requirements.txt
