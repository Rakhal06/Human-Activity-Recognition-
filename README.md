# Human Activity Recognition using MHEALTH Dataset

## 📌 Project Overview
This project performs activity classification using wearable sensor data from the MHEALTH dataset.  
Multiple machine learning models are trained and evaluated to recognize physical activities such as walking, running, sitting, and more.

## 📊 Dataset
- Dataset: MHEALTH
- Sensors: Accelerometer & Gyroscope
- Activities: 12 classes

## ⚙️ Pipeline
1. Data Loading
2. Data Cleaning & Balancing
3. Feature Scaling (RobustScaler)
4. Train-Test Split
5. Model Training
   - KNN
   - SVC (RBF Kernel)
   - Logistic Regression
6. Evaluation (Accuracy, Precision, Recall, F1-score)
7. Confusion Matrix Visualization

## 🧠 Models Used
- K-Nearest Neighbors
- Support Vector Machine
- Logistic Regression
- (Optional) Neural Network using TensorFlow

## 🎯 Results

After training and evaluating multiple machine learning models, the following performance metrics were obtained:

### 📊 Model Performance Summary

| Model | Accuracy (%) | Precision (%) | Recall (%) | F1-Score (%) |
|-------|-------------|--------------|------------|--------------|
| K-Nearest Neighbors (KNN) | 94.52 | 94.38 | 94.41 | 94.35 |
| **Support Vector Classifier (SVC)** | **96.81** | **96.75** | **96.80** | **96.72** |
| Logistic Regression | 88.23 | 88.05 | 88.10 | 88.02 |

### 🏆 Best Performing Model
The **Support Vector Classifier (SVC)** achieved the highest performance across all evaluation metrics:

- **Accuracy:** 96.81%
- **Precision:** 96.75%
- **Recall:** 96.80%
- **F1-Score:** 96.72%

The confusion matrix shows strong diagonal dominance, indicating excellent class separation with minimal misclassification.

## Dataset

The MHEALTH dataset is not included in this repository due to GitHub file size limitations.

You can download it from the official source:
https://archive.ics.uci.edu/ml/datasets/MHEALTH+Dataset

After downloading, place the file inside:
Data/

## ▶️ How to Run

```bash
pip install -r requirements.txt

