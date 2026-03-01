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

## 📈 Results
Best model: <PUT YOUR BEST MODEL HERE>  
Accuracy: <PUT ACCURACY HERE>

## Dataset

The MHEALTH dataset is not included in this repository due to GitHub file size limitations.

You can download it from the official source:
https://archive.ics.uci.edu/ml/datasets/MHEALTH+Dataset

After downloading, place the file inside:
Data/

## ▶️ How to Run

```bash
pip install -r requirements.txt

