# 🕵️‍♂️ Fake Profile Detection using Machine Learning & NLP

## 📄 Overview
As social media platforms continue to grow, so does the prevalence of fake profiles—used for spreading misinformation, scams, and manipulating public sentiment. This project introduces a machine learning-based system to identify fake profiles using behavioral and profile-based data.

The goal is to accurately classify social media accounts as real or fake using supervised learning models, while providing a simple and interactive interface for real-time predictions.

---

## 🎯 Objectives
- Train a machine learning model to classify profiles as either real or fake.
- Extract and engineer meaningful features that highlight suspicious account behavior.
- Build an intuitive web-based interface using Streamlit for user interaction.
- Evaluate model performance using accuracy, precision, recall, and F1-score.

---

## 🛠️ Tech Stack

| Tool / Library        | Purpose                               |
|-----------------------|----------------------------------------|
| Python                | Core development language              |
| Scikit-learn          | Machine learning algorithms            |
| Pandas, NumPy         | Data processing and analysis           |
| Matplotlib, Seaborn   | Data visualization                     |
| Google Colab          | Development and experimentation        |
| Streamlit             | Web-based frontend for live testing    |

---

## 📁 Project Structure


Fake-Profile-Detection/
├── app.py                # Streamlit frontend
├── model.pkl             # Trained machine learning model
├── fake_profile_data.csv # Dataset used for training/testing
├── requirements.txt      # Dependencies
├── README.md             # Project documentation
└── notebooks/
    └── Fake_Profile_Model.ipynb # Development notebook
