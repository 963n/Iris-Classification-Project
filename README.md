# 🌸 Iris Classification Project

An **interactive Machine Learning web application** built with **Streamlit**, designed to classify Iris flowers into **Setosa**, **Versicolor**, or **Virginica** from four simple measurements.  
Clean UI. Accurate predictions. Ready to use. 🌱

---

## 🔗 Quick Access

[![🚀 Launch App](https://img.shields.io/badge/Launch_App-Streamlit-brightgreen?style=for-the-badge&logo=streamlit)]((https://iris-ml-classification-project.streamlit.app/))
[![💻 Open Notebook in Colab](https://img.shields.io/badge/Open_in-Colab-orange?style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/github/963n/iris-classification/blob/main/iris.ipynb)
[![📂 View Repository](https://img.shields.io/badge/View_on-GitHub-black?style=for-the-badge&logo=github)](https://github.com/963n/iris-classification)

---

## 📸 App Preview


![Iris Classification App Screenshot](assets/app_preview.png)

---

## 🧠 How It Works

### 1) Dataset
We use the classic **Iris dataset** (150 samples; 3 species):
- **Features**
  - `sepal_length` (cm)  
  - `sepal_width`  (cm)  
  - `petal_length` (cm)  
  - `petal_width`  (cm)
- **Label**
  - `species` ∈ {`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`}

Dataset file: **`IRIS.csv`**

### 2) Model Training (in `iris.ipynb`)
- Train/test split: **80/20** (`random_state=2`)
- Classifier: **Gaussian Naive Bayes** (`sklearn.naive_bayes.GaussianNB`)
- Save the trained model to **`trained_model.sav`** (via `pickle.dump`)

### 3) App Logic (Streamlit)
- Sliders for the four measurements
- Click **Result** to run inference
- Shows prediction with emoji 🌱🌼🌸

---

## ✨ Features

- Minimal, responsive UI
- Fast, lightweight model
- Clear training pipeline in Jupyter Notebook
- Ready-to-deploy model file

---

## 🛠️ Tech Stack

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=fff)](#)
[![pandas](https://img.shields.io/badge/pandas-Data%20Frames-150458?logo=pandas&logoColor=fff)](#)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=fff)](#)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-EA3E5D?logo=streamlit&logoColor=fff)](#)
[![pickle](https://img.shields.io/badge/pickle-Model%20IO-555)](#)

---

## 📂 Project Structure

├── IRIS.csv
├── iris.ipynb
├── trained_model.sav
├── streamlit_app.py
├── requirements.txt
└── README.md

## 🔍 Notes & Tips

- Feature order: `[sepal_length, sepal_width, petal_length, petal_width]`
- After retraining, make sure the app loads the updated `trained_model.sav`
- Keep screenshot paths correct for GitHub display

---

## 📚 References

- Streamlit Docs — https://docs.streamlit.io/  
- scikit-learn Docs — https://scikit-learn.org/stable/  
- Iris Dataset (UCI) — https://archive.ics.uci.edu/ml/datasets/iris  

---

## ✍️ Author

**Mohammed Alawfi**  
[![GitHub](https://img.shields.io/badge/GitHub-Profile-000?logo=github&logoColor=fff)](https://github.com/yourusername)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=fff)](https://linkedin.com/in/yourlinkedin)

---

## 📜 License

This project is licensed under the **MIT License**. See `LICENSE` for details.
