# 2401730086_EDA_project_Sem3
# 🍷 Wine Reviews Exploratory Data Analysis (EDA)

This project performs a complete **Exploratory Data Analysis (EDA)** on the [Wine Reviews Dataset](https://www.kaggle.com/zynicide/wine-reviews), as part of my Data Science learning journey.  
The goal is to explore the relationship between wine **price**, **rating (points)**, and **variety**, and uncover patterns that affect wine quality and consumer preferences.

---

## 🧭 Project Objectives
1. Perform a **complete EDA** using Python and pandas.
2. Clean and preprocess the dataset by handling **missing values**, **duplicates**, and **outliers**.
3. Conduct **univariate** and **bivariate** analysis to identify trends and correlations.
4. Visualize relationships using **Matplotlib** and **Seaborn**.
5. Draw meaningful **insights** and conclusions.

---

## 📊 Dataset Overview
- **Source:** Kaggle – *Wine Reviews Dataset*  
- **Rows:** ~130,000 wine reviews  
- **Columns:**  
  - `country`: Country of origin  
  - `province`: Region within the country  
  - `variety`: Grape type  
  - `price`: Retail price of the wine  
  - `points`: Quality score (1–100)  
  - `winery`, `designation`, and textual `description`  

---

## ⚙️ Technologies Used
- Python 🐍  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- SciPy (for statistical measures)  
- Jupyter Notebook  

---

## 📈 Key Steps
1. **Data Loading & Inspection:** Understanding data structure using `info()` and `describe()`.  
2. **Data Cleaning:**  
   - Missing value treatment (`fillna`, `dropna`)  
   - Removing duplicates  
   - Handling outliers using the IQR method  
3. **Univariate Analysis:**  
   - Central tendency (mean, median, trimmed mean)  
   - Variability (variance, standard deviation, range)  
   - Frequency counts for categorical columns  
4. **Bivariate Analysis:**  
   - Correlation matrix & heatmap  
   - Scatter plot (Price vs. Points)  
   - Boxplots (Points by Variety)  
5. **Visualization:**  
   Created clean, intuitive visualizations using `seaborn` to support data storytelling.  

---

## 💡 Key Insights
- Higher-priced wines generally receive higher quality scores, but the relationship is not perfectly linear.
- Certain grape varieties (e.g., **Pinot Noir**, **Cabernet Sauvignon**) tend to have higher average scores.
- Wine ratings vary significantly across regions — e.g., wines from **California** and **Italy** dominate top ratings.
- Price outliers were capped using the 1st and 99th percentiles to prevent skewing visualizations.

---

## 📂 Folder Structure

