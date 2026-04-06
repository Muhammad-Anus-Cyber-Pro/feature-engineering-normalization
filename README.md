# 📊 Feature Engineering: Normalization on Social Network Ads Dataset

## 📖 Overview
This project focuses on applying Normalization (Min-Max Scaling) on the Social Network Ads dataset.

Normalization rescales feature values to a fixed range, usually between 0 and 1, making it useful for machine learning algorithms that depend on magnitude and distance.

---

## ⚙️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 🧠 Concepts Covered
- Feature Engineering  
- Feature Transformation  
- Normalization (Min-Max Scaling)  
- Data Preprocessing  

---

## 🔄 What is Normalization?
Normalization transforms features using the formula:
X_normalized = (X - X_min) / (X_max - X_min)


After transformation:
- Values range between 0 and 1  

---

## 📊 Why Normalization?

- Scales features to a fixed range (0–1)  
- Useful for distance-based algorithms (KNN, Neural Networks)  
- Prevents large-value features from dominating  
- Helps in faster convergence  

---

## 🚀 Implementation Steps

1. Loaded the dataset  
2. Split data into training and testing sets  
3. Applied MinMaxScaler:
   - Fit on training data  
   - Transform both training and testing data  
4. Observed scaled feature values  

---

## 🔍 Key Insights

- All features were successfully scaled between 0 and 1  
- Useful when data does not follow a normal distribution  
- Improves performance in certain ML models  

---

## ⚖️ Standardization vs Normalization

| Technique        | Output Range | Best Use Case |
|------------------|-------------|--------------|
| Standardization  | Mean = 0, Std = 1 | Gaussian data, Linear Models |
| Normalization    | 0 to 1      | Distance-based models |

---

## 📌 Next Step

- Apply both techniques on the same dataset  
- Compare model performance  

---

## 🔗 How to Run

```bash
pip install numpy pandas matplotlib scikit-learn

Normalization transforms features using the formula:
