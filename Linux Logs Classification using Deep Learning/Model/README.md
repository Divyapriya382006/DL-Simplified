# Model

## Overview

This notebook demonstrates the complete workflow for classifying Linux system log events using an Artificial Neural Network (ANN).

The workflow includes preprocessing, feature encoding, model development, training, evaluation, and prediction.

---

## Notebook

```
linux-logs.ipynb
```

---

## Workflow

- Import Libraries
- Load Dataset
- Data Cleaning
- Label Encoding
- Feature Preparation
- Train-Test Split
- ANN Model Development
- Model Training
- Performance Evaluation
- Prediction

---

## Neural Network Architecture

The model consists of:

- Input Layer
- Dense Layer (128 neurons, ReLU)
- Dense Layer (64 neurons, ReLU)
- Dense Layer (32 neurons, ReLU)
- Output Layer (Softmax)

---

## Required Libraries

- numpy
- pandas
- matplotlib
- scikit-learn
- tensorflow
- jupyter

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## Running the Notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
linux-logs.ipynb
```

Run all cells sequentially.

---

## Applications

- Log Classification
- Security Monitoring
- Event Analysis
- System Diagnostics
- Infrastructure Monitoring

---

## Notes

This notebook demonstrates an end-to-end deep learning pipeline for multi-class Linux system log classification using TensorFlow and Keras.