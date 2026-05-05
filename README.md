# Heartbeat to Heatmap — Data Mining Assignment

## 📌 Project Overview

This project implements machine learning models for heart disease prediction and handwritten digit recognition as part of DS-3002 Data Mining (FAST-NUCES).

It covers:

* Unsupervised Learning (K-Means, Hierarchical Clustering)
* Ensemble Methods (Random Forest, XGBoost)
* Neural Networks (SLP, MLP)
* CNN for MNIST digit classification
* Interactive frontend dashboard for predictions

---

## 📂 Project Structure

* `notebooks/` → All Jupyter notebooks (Parts A–D)
* `app/` → Streamlit app for prediction
* `report/` → Final report (PDF/DOCX)
* `data/` → Dataset files

---

## 📊 Dataset

### Heart Disease Dataset

Download from:
https://archive.ics.uci.edu/dataset/45/heart+disease

Place file:
processed.cleveland.data → inside `/data`

### MNIST Dataset

Loaded automatically using TensorFlow:

```python
from tensorflow.keras.datasets import mnist
```

---

## ⚙️ Setup Instructions

Install dependencies:

```
pip install -r requirements.txt
```

---

## ▶️ Run Notebooks

```
jupyter notebook
```

Open files from `/notebooks/`

---

## 🚀 Run App (Frontend Dashboard)

```
streamlit run app/app.py
```

---

## 📌 Requirements

All dependencies are listed in `requirements.txt`

---

## 👨‍⚕️ Objective

Build fast, interpretable models suitable for clinical decision support on low-resource machines.
