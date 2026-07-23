# Sonar Rock vs Mine Classification

## 📌 Overview

This project focuses on classifying sonar signals as either **Rock (R)** or **Mine (M)** using Machine Learning techniques. Sonar signals are commonly used in underwater navigation and object detection, where correctly identifying mines is critical for maritime safety.

The project performs exploratory data analysis (EDA), data preprocessing, feature analysis, model training, and evaluation using the Sonar Dataset.

---

## 📂 Project Structure

```
Sonar Rock vs Mine Classification/
│
├── Dataset/
│   ├── README.md
│
├── Images/
│   ├── correlation_heatmap.png
│   ├── class_distribution.png
│   ├── feature_visualization.png
│
├── Model/
│   ├── sonar_data_analysis.ipynb
│   ├── README.md
│
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

The Sonar Dataset consists of sonar signal measurements reflected from either rocks or metal cylinders (mines).

- Total Samples: **208**
- Features: **60 numerical attributes**
- Target Classes:
  - Rock (R)
  - Mine (M)

Dataset details are available inside the **Dataset** folder.

---

## 🚀 Project Workflow

- Data Loading
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Analysis
- Model Training
- Model Evaluation
- Prediction

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Results

The trained machine learning model successfully classifies sonar signals into **Rock** and **Mine** categories with high accuracy after preprocessing and training.

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone <repository-url>
```

2. Install dependencies.

```bash
pip install -r requirements.txt
```

3. Open the notebook.

```bash
jupyter notebook
```

4. Run all cells sequentially.

---

## 📚 Applications

- Naval Mine Detection
- Underwater Object Identification
- Marine Research
- Sonar Signal Classification

---

## 👨‍💻 Author

Developed as part of **Deep Learning Simplified**.