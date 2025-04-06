# 💻 Laptop Price Prediction

This project uses machine learning to predict the prices of laptops based on their technical specifications. It walks through data preprocessing, feature engineering, model training, and evaluation.

---
## 📊 Dataset Overview

The dataset (`laptop_data.csv`) contains real-world specifications and prices for various laptops. Columns include:

- Brand
- Processor Type
- RAM (GB)
- Storage (HDD/SSD)
- Operating System
- GPU
- Display (inches)
- Weight (kg)
- Touchscreen (Yes/No)
- Price (Target)

---

## ⚙️ Workflow

1. **Data Cleaning**
   - Handling missing values
   - Removing duplicates
   - Converting units

2. **Feature Engineering**
   - One-hot encoding categorical columns
   - Extracting numerical values from strings

3. **Model Training**
   - Linear Regression

4. **Evaluation**
   - R² Score
   - MAE / RMSE

5. **Price Prediction Function**
   - Accepts user input specs and returns a predicted price

---

## 🛠️ Technologies Used

- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

