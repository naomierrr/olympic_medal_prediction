# olympic_medal_prediction
# 🏅 Olympic Medal Prediction (Beginner ML Project)

This project predicts how many Olympic medals a country/team will win using a simple machine learning model.

I built this as a beginner project to practice the full ML workflow:
data cleaning → baseline → model training → evaluation → visualization.

---

## 🎯 Goal
Predict **`medals`** using:
- **`athletes`** (number of athletes)
- **`prev_medals`** (medals from the previous Olympics)

---

## 📦 Dataset
The dataset contains country/team Olympic performance by year.  
Main columns used:
- `team`
- `year`
- `athletes`
- `prev_medals`
- `medals` (target)

---

## ✅ What I implemented
### 1) Baseline model
Before training ML, I created a baseline to check if the model is actually useful.

- **Baseline prediction:** use the **median medals** from the training set  
- Compare baseline MAE vs model MAE(error)

This answers: *“Is my model better than a simple guess?”*

### 2) Linear Regression model
I trained a **Linear Regression** model using the training set and predicted medals on the test set.

### 3) Evaluation
I evaluated performance using:
- **Mean Absolute Error (MAE)**

### 4) Visualization
I plotted **Actual vs Predicted medals** to visually inspect model performance.

---

## 🧠 Key Learning
- How to split data into train/test
- Why a baseline matters
- How linear regression learns relationships between variables
- How MAE measures prediction error
- How to visualize predictions vs reality

---

## 🛠 Tools Used
- Python
- pandas
- scikit-learn
- seaborn
- matplotlib

---

## ▶️ How to run
1. Clone this repository or download it as a ZIP
2. Install dependencies
3. Open the notebook and run all cells
