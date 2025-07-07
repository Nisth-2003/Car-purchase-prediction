# 🚗 Car Purchase Amount Prediction

This project builds and trains a machine learning model to **predict the amount a customer is likely to spend on purchasing a car** based on personal and financial features.

---

## 📊 Dataset

- **File**: `Car_Purchasing_Data.csv`
- **Source**: Contains customer data including name, email, country, gender, age, annual salary, credit card debt, net worth, and car purchase amount.

### 🔑 Features Used:
- Age
- Annual Salary
- Credit Card Debt
- Net Worth

### 🎯 Target:
- Car Purchase Amount

---

## 🧠 Model Architecture

- **Tool Used**: Keras with TensorFlow backend
- **Model**: Simple Neural Network using `Sequential()` with:
  - Input layer with `input_dim=4`
  - Two hidden layers with `relu` activation
  - Output layer with `linear` activation (for regression)

### 📌 Activation Functions:
- `ReLU`: For non-linearity in hidden layers
- `Linear`: For continuous output in the regression task

---

## 🛠️ Technologies

- Python
- Pandas, NumPy
- TensorFlow / Keras
- Matplotlib / Seaborn (for visualization)
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/car-purchase-prediction.git
   cd car-purchase-prediction
