# 🩺 Diabetes Progression Prediction using Decision Tree Regressor

## 📌 Project Overview

This machine learning project predicts diabetes disease progression using a Decision Tree Regressor. The project demonstrates regression modeling, evaluation metrics, tree visualization, and overfitting control techniques.

---

## 📂 Dataset

- Dataset: Diabetes Dataset (Scikit-Learn)
- Target Variable: Disease Progression Score

### Features
- Age
- Sex
- BMI
- Blood Pressure
- Six Blood Serum Measurements

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## ⚙️ Project Workflow

### 1. Dataset Loading
Loaded the Diabetes Dataset from Scikit-Learn.

### 2. Data Exploration
- Checked dataset dimensions
- Examined feature names
- Analyzed target variable

### 3. Train-Test Split
- 70% Training Data
- 30% Testing Data

### 4. Model Training
Implemented:

```python
DecisionTreeRegressor()
```

### 5. Hyperparameter Tuning
Experimented with:
- max_depth
- min_samples_split
- min_samples_leaf

to reduce overfitting.

### 6. Model Evaluation

Metrics used:

- R² Score
- Mean Squared Error (MSE)

### 7. Tree Visualization

Visualized the regression tree using:

```python
plot_tree()
```

---

## 📈 Results

The model successfully predicts diabetes progression scores and demonstrates the application of Decision Tree Regression for continuous-value prediction problems.

---

## 🎯 Learning Outcomes

- Regression Analysis
- Decision Tree Regressor
- Model Evaluation
- Hyperparameter Tuning
- Overfitting Reduction
- Tree Visualization

---

## 🚀 Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ Run the Project

```bash
jupyter notebook
```

Open:

```bash
decision_tree_regressor_on_diabetes_dataset.ipynb
```

---

## 🔮 Future Improvements

- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- Cross Validation
- GridSearchCV Hyperparameter Tuning

---

## 👨‍💻 Author

Ashutosh Mehta

Computer Engineering Student
