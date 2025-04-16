# 💳 Credit Default Prediction using Artificial Neural Networks (ANN)

Can we predict whether a credit card customer will default next month?

This project uses an **Artificial Neural Network (ANN)** built with TensorFlow/Keras to predict the **probability of default (PD)** based on client financial behavior and credit history. The model was trained and evaluated on real-world data from 30,000 credit card clients.

---

## 🧠 Project Highlights

- 📂 Dataset: Credit card client default data (UCI repository)
- 🤖 Model: ANN with 2 hidden layers using TensorFlow & Keras
- 🎯 Target: Predict `default payment next month` (binary classification)
- 📈 Output: Both binary classification and probability of default
- ✅ Evaluation: Accuracy, Precision, Recall, AUC, Calibration

---

## 🧪 Features & Workflow

- Preprocessing: scaling, train-test split, data cleaning
- Model: Feedforward neural network with ReLU + sigmoid
- Evaluation: Confusion matrix, ROC-AUC, PD visualization
- Visualization: Easy-to-read plots for insight and interpretation

---

## 📊 Visual Results

### 🎯 ROC Curve
![ROC Curve](roc_curve.png)

### 🟩 Confusion Matrix
![Confusion Matrix](confusion_matrix.png)

### 📊 Distribution of Predicted Probability
![PD Distribution](distribution_of_predicted_probability_of_default.png)

### 🔍 PD Split by Actual Default Status
![PD by Actual Default](predicted_PD_by_actual_default.png)

### 📈 Training vs Validation Accuracy
![Training vs Validation Accuracy](training__validation_accuracy_over_epochs.png)

---

## 🧾 How to Run

### ⚙️ Install Dependencies
```bash
pip install -r requirements.txt
