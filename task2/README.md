# 📊 Task 2: Exploratory Data Analysis (EDA)

### 🎯 Objective:
Explore and understand the Titanic dataset using statistical summaries and visualizations. The goal is to uncover hidden patterns, trends, and relationships between features and the survival outcome.

---

## 📦 Dataset
**Titanic Dataset**: [Download here](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

## 🛠️ Tools Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 🔍 Steps Performed

### 1️⃣ Summary Statistics
- Generated basic stats: mean, median, std, min, max
- Checked data types and distributions
### 2️⃣ Visualize Distributions
- Histograms and boxplots for numeric features (Age, Fare)
- Detected skewness and outliers

### 3️⃣ Feature Relationships
- Survival vs Gender (Sex)
- Survival vs Class (Pclass)
- Survival vs Age and Fare
- Embarkation Port and survival (Embarked)

### 4️⃣ Correlation Matrix
- Used .corr() and sns.heatmap to find linear relationships
- Identified strong negative correlation between Sex and Survived

### 📌 Pattern Observations (Inferred from Visuals)
- Survival by Age: Infants and young children had higher survival rates.
- Survival by Sex: Clear preference for females surviving.

## 🔎 Summary of Insights:
- 🧍‍♀️ Women had a significantly higher survival rate than men.
- 🎫 1st class passengers were more likely to survive than 2nd and 3rd.
- 👶 Children and young adults were prioritized during evacuation.
- 💰 Higher fares were associated with better survival chances.
- 🛳️ Passengers from Cherbourg (Embarked = C) had the highest survival rate.

