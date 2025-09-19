# APR-assignment_linear-regression
# ⚡ Energy Consumption Prediction using Linear Regression

## 📌 Project Overview

This project implements a **Linear Regression model** to predict **energy consumption** using building and environmental features.

The model demonstrates **near-perfect accuracy**, making it a strong baseline for energy forecasting.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

* **Handling missing values**
* **One-hot encoding** categorical features:

  * **Building Type**
  * **Day of Week**
* **Scaling** numerical features:

  * **Square Footage**
  * **Number of Occupants**
  * **Appliances Used**
  * **Average Temperature**

---

## 📊 Model Performance

The trained model achieved:

* **Mean Squared Error (MSE):** `0.0002015`
* **R-squared Score (R²):** `0.9999999997`

✅ These metrics confirm that the model almost perfectly explains the variance in energy consumption.

---

## 📈 Visualization

* A scatter plot of **Actual vs. Predicted Energy Consumption** shows points closely aligned on the diagonal line.
* This indicates **extremely accurate predictions**.

---

## 🔍 Insights

* The chosen features are **highly predictive** of energy consumption.
* **Linear Regression** effectively captures the relationships in the dataset.
* **Future improvements** may include:

  * Examining **model coefficients** for feature importance
  * Applying **regularization techniques** (Ridge, Lasso)
  * Comparing with **non-linear models** such as Random Forest or Gradient Boosting

---

## 🚀 How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/energy-consumption-prediction.git
   cd energy-consumption-prediction
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the training script**

   ```bash
   python train_model.py
   ```

---

## 📂 Repository Structure

```
energy-consumption-prediction/
│── train_model.py       # Training & evaluation script
│── requirements.txt     # Python dependencies
│── README.md            # Project documentation
└── data/                # Training & testing datasets
```

---

## 👨‍💻 Author

created by sanidhya
Contributions, feedback, and pull requests are **always welcome**!
