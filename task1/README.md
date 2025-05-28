# 🧹 Task 1: Data Cleaning & Preprocessing

### 🎯 Objective:
Prepare raw Titanic dataset for machine learning by cleaning and transforming it into a usable format.

---

## 📦 Dataset
We used the [Titanic Dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv), a classic dataset used for binary classification (survival prediction).

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 🔍 Steps Performed

### 1️⃣ Load & Explore Data
- Loaded dataset using `pandas`
- Viewed data types, shape, and basic stats
- Checked for missing values

### 2️⃣ Handle Missing Values
- Replaced missing `Age` values with **mean**
- Replaced missing `Embarked` values with **mode**
- Dropped the `Cabin` column due to excessive missing data

### 3️⃣ Encode Categorical Features
- Converted Sex to numeric (0: male, 1: female)
- Applied one-hot encoding to Embarked

### 4️⃣ Normalize Numerical Features
- Standardized Age and Fare columns using StandardScaler

### 5️⃣ Detect and Handle Outliers
- Visualized Age and Fare using boxplots
- Removed outliers using the IQR method

### ✅ Final Cleaned Data Preview
- Cleaned, imputed, encoded, and standardized dataset ready for analysis or modeling.
- No missing values or extreme outliers.
- Balanced and consistent feature set.

### 📌 Notes
- Mean imputation is suitable for normally distributed numeric data.
- For skewed distributions, median imputation may be better.
- Cabin was dropped due to over 75% missing data.
- Use .copy() when modifying slices in real projects to avoid warnings.
