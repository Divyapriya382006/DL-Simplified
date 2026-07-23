# Linux System Log Classification using ANN

## Overview

This project focuses on classifying Linux system log events using an Artificial Neural Network (ANN). System logs contain valuable information about operating system activities, errors, warnings, and events. Automating log classification helps identify system behavior, detect anomalies, and improve monitoring and troubleshooting.

The project covers data preprocessing, feature encoding, model training, evaluation, and prediction using a multi-class neural network.

---

## Project Structure

```
Linux System Log Classification using ANN/
│
├── Dataset/
│   ├── README.md
│
├── Images/
│
├── Model/
│   ├── linux-logs.ipynb
│   ├── README.md
│
├── README.md
└── requirements.txt
```

---

## Dataset

The dataset consists of Linux system log records containing event information collected from system logs.

- Structured log entries
- Multiple event categories
- Suitable for multi-class classification

Dataset details are available in the **Dataset** folder.

---

## Project Workflow

- Data Loading
- Data Cleaning
- Feature Encoding
- Exploratory Data Analysis
- Train-Test Split
- ANN Model Development
- Model Training
- Performance Evaluation
- Prediction

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

---

## Applications

- Log Analysis
- System Monitoring
- IT Operations
- Security Analytics
- Anomaly Detection

---

## How to Run

1. Install the required dependencies.

```bash
pip install -r requirements.txt
```

2. Launch Jupyter Notebook.

```bash
jupyter notebook
```

3. Open the notebook and run all cells.

---

## Author

Developed as part of **Deep Learning Simplified**.