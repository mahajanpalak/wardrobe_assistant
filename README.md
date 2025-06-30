# 🧥 Wardrobe Recommender System

This project is a machine learning-based wardrobe recommender system built in **Python** using **scikit-learn** and **Google Colab**. It suggests outfits or items based on user feedback and maintains persistent state by storing files in **Google Drive**.

---

## 📌 Features

✅ Recommends clothing items based on previous user interactions  
✅ Saves user feedback (likes/dislikes) to improve recommendations  
✅ Loads and saves a trained ML model (`.pkl`)  
✅ Stores feedback data in CSV format on Google Drive  
✅ Supports interactive filtering and selection of items

---

## 🚀 Getting Started

This project is intended to be run in **Google Colab**.

### 1️ Open in Colab

---

### 2️ Mount Google Drive

The project stores:
- Model file: `wardrobe_recommender_model.pkl`
- Feedback CSV: `user_feedback.csv`
- Kaggle API key: `kaggle.json`

In the notebook, make sure to mount your Google Drive:

```python
from google.colab import drive
drive.mount('/content/drive')
