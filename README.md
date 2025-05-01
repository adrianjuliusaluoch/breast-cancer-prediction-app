# Breast Cancer Prediction Web Application



![cancer logo](https://github.com/user-attachments/assets/c22d7a87-7efd-431c-9bc5-eeb0c0774222)

<p align="center">
  🚀 <strong>Live App:</strong> 
  <a href="https://breast-cancer-prediction-app-by-rudra.streamlit.app/" target="_blank">
    breast-cancer-prediction-app-by-rudra.streamlit.app
  </a>
</p>

---

<p align="center">
  <a href="https://github.com/Rudra-G-23">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/>
  </a>
  <a href="https://www.linkedin.com/in/rudra-prasad-bhuyan-44a388235">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://www.kaggle.com/rudraprasadbhuyan">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle Badge"/>
  </a>
</p>

<p align="center">
  <a href="https://pypi.org/project/numpy/">
    <img src="https://img.shields.io/badge/numpy-2.2.4-blue?style=for-the-badge&logo=numpy" alt="numpy">
  </a>
  <a href="https://pypi.org/project/pandas/">
    <img src="https://img.shields.io/badge/pandas-2.2.3-yellow?style=for-the-badge&logo=pandas" alt="pandas">
  </a>
  <a href="https://pypi.org/project/plotly/">
    <img src="https://img.shields.io/badge/plotly-6.0.1-orange?style=for-the-badge&logo=plotly" alt="plotly">
  </a>
  <a href="https://pypi.org/project/scikit-learn/">
    <img src="https://img.shields.io/badge/scikit--learn-1.6.1-green?style=for-the-badge&logo=scikit-learn" alt="scikit-learn">
  </a>
  <a href="https://pypi.org/project/streamlit/">
    <img src="https://img.shields.io/badge/streamlit-1.44.1-red?style=for-the-badge&logo=streamlit" alt="streamlit">
  </a>
</p>

---

## 📌 Overview

This is a Streamlit-based web application that predicts whether a breast tumor is **benign** or **malignant** using a trained logistic regression model. Built using the **Breast Cancer Wisconsin Diagnostic Dataset**, this project demonstrates the complete data science lifecycle — from problem definition to model deployment.

> 🎯 Objective: Build a reliable, interactive, and modular diagnostic tool that aids in early breast cancer detection using medical imaging features.

---

## ⭐ Project Highlights 

- ✅ Demonstrates end-to-end ML workflow
- ✅ Real-time prediction app with deployed UI
- ✅ Modular, readable, and scalable Python code
- ✅ Excellent use case for health tech/AI in diagnostics


---

## 🧠 Key Features

- Predict tumor type (Benign or Malignant)
- Real-time probability scores
- User-friendly UI with input sliders
- Modular codebase for easy scalability
- Live deployment on Streamlit Cloud

---

## 🗂️ Project Architecture

```
├── assets/                # Visual assets (e.g., logos, screenshots)
├── data/                 # Dataset and derived files
├── model/                # Trained model (Pickle file)
├── notebooks/            # Exploratory and preprocessing notebooks
│   ├── p1-understand-the-data.ipynb
│   ├── p2-eda.ipynb
│   └── p3-outliers.ipynb
├── utils/                # Custom modules for charts, sidebar, data
│   ├── charts.py
│   ├── data_model.py
│   ├── sidebar.py
├── streamlit_app.py      # Main app entry point
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## 📊 Features Used for Prediction

The model uses 30 key measurements from cell nuclei obtained via digitized images, including:

- **Mean**: Radius, Texture, Perimeter, Area, Smoothness
- **Standard Error**: Radius SE, Perimeter SE, Concavity SE, etc.
- **Worst (largest)**: Texture worst, Area worst, Symmetry worst, etc.

Each of these is captured using an intuitive sidebar interface in the app.

---

## 🧪 Model Details

- **Algorithm**: Logistic Regression
- **Library**: `scikit-learn`
- **Training Dataset**: [UCI Breast Cancer Diagnostic Data](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Model File**: Saved as `model.pkl` for production use

**Note**: The pickle file is version-sensitive. Please ensure compatible `scikit-learn` versions (1.6.1 recommended) for loading the model.

---

## 📌 Step-by-Step Workflow

This project was developed following an end-to-end data science pipeline:

1. **Problem Definition**
2. **Data Collection & Cleaning**
3. **Exploratory Data Analysis (EDA)**
4. **Outlier Handling & Feature Engineering**
5. **Model Building & Evaluation**
6. **Prediction Pipeline Creation**
7. **Web App Development using Streamlit**
8. **Deployment on Streamlit Cloud**

---

## 🧰 Tech Stack

| Tool/Library      | Usage                            |
|------------------|----------------------------------|
| Python            | Core programming language        |
| Pandas / NumPy    | Data manipulation                |
| Matplotlib / Seaborn | Data visualization           |
| Plotly            | Interactive Data visualization   |
| Scikit-learn      | Model building & evaluation      |
| Streamlit         | Web interface & deployment       |
| Pickle            | Model serialization              |


---

## 📷 App Interface

> Example inputs include cell features like radius, area, smoothness, etc.  
> The prediction result is shown instantly with confidence levels.


https://github.com/user-attachments/assets/b97376d0-1609-484d-bce3-1aa08c5430f1


---

## 🧪 Run the App Locally

- Clone the repository
    ```bash
    git clone https://github.com/Rudra-G-23/breast-cancer-prediction-app.git
    cd breast-cancer-prediction-app
    ```

- Install dependencies
    ```bash
    pip install -r requirements.txt
    ```

- Launch the app
    ```bash
    streamlit run streamlit_app.py
    ```

---

## 📚 References

- [📘 Streamlit Deployment Guide](https://docs.streamlit.io/)
- [📊 Kaggle Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- [🔬 Feature Engineering Notebook](https://www.kaggle.com/code/kanncaa1/feature-selection-and-data-visualization)
- [📈 Modeling Example](https://www.kaggle.com/code/anandhuh/breast-cancer-prediction-accuracy-98-24)
- [🎥 Inspiration](https://youtu.be/NfwfiyMi1lk?si=scRd-q5N8xkPJUoY)

---

## 🙋‍♂️ Author

**Rudra Prasad Bhuyan**  
📧 rudraprasadbhuyan000@gmail.com  
🔗 [GitHub](https://github.com/Rudra-G-23) | [LinkedIn](https://www.linkedin.com/in/rudra-prasad-bhuyan-44a388235) | [Kaggle](https://www.kaggle.com/rudraprasadbhuyan)

---
