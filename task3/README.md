# 🧮 Task 3: Linear Regression — Predicting House Prices

---

## 🎯 Objective
Apply **simple and multiple linear regression** techniques to model and predict **house prices** based on key features. This task helps build intuition around regression modeling, evaluation metrics, and real-world data interpretation.

---

## 📂 Dataset
**House Prices Dataset**  
> 📎 [[Click here to download the dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)]

The dataset includes features such as:
- `GrLivArea`: Above-ground living area (sq. ft)
- `GarageArea`: Garage size
- `OverallQual`: Overall material/finish quality
- `SalePrice`: Target variable — final sale price

---

## ⚙️ Tools & Libraries Used

| Tool         | Purpose                    |
|--------------|-----------------------------|
| `pandas`     | Data loading & manipulation |
| `numpy`      | Numerical operations         |
| `matplotlib` | Static data visualizations   |
| `seaborn`    | Statistical plotting         |
| `scikit-learn` | Regression modeling & metrics |

---

## 🧭 Project Roadmap

### 🔹 Step 1: Data Loading & Preparation
- Loaded CSV using `pandas`
- Removed nulls and non-numeric fields
- Selected relevant features

### 🔹 Step 2: Train-Test Split
- Split data into `80%` training and `20%` testing using `train_test_split`

### 🔹 Step 3: Model Training
- Built a **Linear Regression** model using `sklearn.linear_model.LinearRegression`
- Trained on:
  - Simple model: `GrLivArea` → `SalePrice`
  - (Optional) Multiple regression with `GarageArea`, `OverallQual`, etc.

### 🔹 Step 4: Evaluation
Evaluated model using:
- ✅ **Mean Absolute Error (MAE)**
- ✅ **Mean Squared Error (MSE)**
- ✅ **R² Score** — how well features explain price variation

### 🔹 Step 5: Visualization
- **Regression Line Plot**: Actual vs Predicted
- Used `seaborn` to display linearity and residuals visually

---
### 📈 Interpretation:
- For every 1 sq. ft increase in living area, the price increases by ~$110
- The model explains ~72% of the variation in house prices.



