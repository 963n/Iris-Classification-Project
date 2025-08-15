# 🌸 Iris Classification Project

An **interactive Machine Learning web application** built with **Streamlit**, designed to classify Iris flowers into **Setosa**, **Versicolor**, or **Virginica** from four simple measurements.  
Clean UI. Accurate predictions. Ready to use. 🌱

---

## 🔗 Quick Access

[![🚀 Launch App](https://img.shields.io/badge/Launch_App-Streamlit-brightgreen?style=for-the-badge&logo=streamlit)](https://iris-ml-classification-project.streamlit.app/)
[![Open in Colab](https://img.shields.io/badge/Open%20in-Colab-orange?style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/github/963n/iris/blob/master/iris.ipynb)
[![📂 View Repository](https://img.shields.io/badge/View_on-GitHub-black?style=for-the-badge&logo=github)](https://github.com/963n/iris-classification-project)

---

## 📸 App Preview


![Iris Classification App Screenshot](https://github.com/963n/Iris-Classification-Project/blob/master/ST_UI_TEST.png)

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

- **Feature order:** Enter the values in this order → `[sepal_length, sepal_width, petal_length, petal_width]`
- **Units:** All measurements are in **centimeters (cm)**.
- **Value range:**  
  - Sepal Length: 4.3 – 7.9 cm  
  - Sepal Width: 2.0 – 4.4 cm  
  - Petal Length: 1.0 – 6.9 cm  
  - Petal Width: 0.1 – 2.5 cm  
- Use the sliders in the app to adjust values and see predictions instantly.
- No installation needed if you use the **Launch App** button — it runs in your browser.
- For offline use:  
  1. Download the repo.  
  2. Install requirements:  
     ```
     pip install -r requirements.txt
     ```  
  3. Run the app:  
     ```
     streamlit run streamlit_app.py
     ```
- Try slightly changing values to see how predictions switch between **Setosa**, **Versicolor**, and **Virginica**.

---

## 🚀 Future Usage & Improvements

This project can be extended and improved in several ways:

- **More datasets** – Allow users to choose from multiple datasets (e.g., other flower species).
- **Model selection** – Let users pick different ML algorithms (RandomForest, SVM, etc.) and compare results.
- **Accuracy display** – Show the model’s confidence score alongside predictions.
- **Data visualization** – Add scatter plots or histograms to visualize inputs vs. predictions.
- **Mobile optimization** – Improve the UI for mobile screens.
- **User input history** – Show a table of previous predictions during the same session.
- **Cloud deployment** – Host on Streamlit Cloud, Hugging Face Spaces, or AWS for broader access.

---

## 📚 References

- Streamlit Docs — https://docs.streamlit.io/  
- scikit-learn Docs — https://scikit-learn.org/stable/  
- Iris Dataset (UCI) — https://archive.ics.uci.edu/ml/datasets/iris  

---

## 🧑‍💻 Author

**Mohammed Alawfi**  

📍 Madinah, Saudi Arabia 

[![GitHub](https://img.shields.io/badge/GitHub-Profile-000?logo=github&logoColor=fff)](https://github.com/963n)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=fff)](https://www.linkedin.com/in/mohammed-alawfi-3913a5378?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)

---

## 📜 License

This project is licensed under the **MIT License**. See `LICENSE` for details.
