
# Packaged Foods India — Data Analysis & Tableau Dashboard

## 📌 Project Overview

This project analyzes a dataset of packaged food products in India to understand product categories, brands, pricing, nutritional composition, and overall product characteristics.

The analysis was performed using **Python in Google Colab** for data cleaning and Exploratory Data Analysis (EDA), followed by **Tableau** for interactive visualization and dashboard development.

The goal of this project is to transform raw packaged-food data into meaningful insights that can help understand product distribution, pricing patterns, nutritional characteristics, and category-level trends.

---

## 🎯 Project Objectives

* Clean and prepare the packaged food dataset.
* Identify and handle missing values.
* Detect and inspect potential outliers.
* Perform Exploratory Data Analysis (EDA).
* Analyze product and brand distribution.
* Compare nutritional values across categories.
* Identify relationships between nutritional variables.
* Build an interactive Tableau dashboard.
* Generate meaningful analytical insights from the dataset.

---

## 🛠️ Tools & Technologies

* **Python**
* **Google Colab**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Tableau**
* **GitHub**

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Understanding & Inspection
     ↓
Data Cleaning
     ↓
Missing Value Treatment
     ↓
Duplicate Check
     ↓
Outlier Detection & Inspection
     ↓
Exploratory Data Analysis
     ↓
Statistical & Visual Analysis
     ↓
Clean Dataset
     ↓
Tableau Dashboard
     ↓
Insights & Conclusions
```

---

## 🧹 Data Cleaning

The dataset was examined and prepared before analysis.

The cleaning process included:

* Checking dataset structure and data types
* Identifying missing values
* Handling remaining missing values
* Checking duplicate records
* Identifying numerical and categorical variables
* Detecting potential outliers using the IQR method
* Inspecting extreme values before deciding whether to retain or remove them
* Converting variables into appropriate data types

Outliers were not automatically removed. Potential extreme values were inspected to determine whether they represented genuine product variations or possible data-quality issues.

---

## 🔎 Exploratory Data Analysis

EDA was performed to understand the characteristics and patterns within the dataset.

### Numerical Analysis

The distribution of important nutritional variables was examined using histograms and KDE curves, including:

* Energy (kcal)
* Protein (g)
* Fat (g)
* Carbohydrates (g)
* Sugars (g)
* Sodium (mg)

### Categorical Analysis

Product distribution was analyzed across:

* Categories
* Brands
* Other relevant categorical variables

### Category-Level Analysis

Average nutritional values were compared across food categories, including:

* Average Energy
* Average Sugar
* Average Fat
* Average Protein

### Correlation Analysis

A correlation heatmap was created to examine relationships between numerical nutritional variables.

### Relationship Analysis

Scatter plots were used to investigate relationships such as:

* Fat vs Energy
* Sugar vs Energy
* Protein vs Energy

---

## 📊 Tableau Dashboard

An interactive Tableau dashboard was created to present the analysis in an easy-to-understand format.

### Key Performance Indicators

The dashboard includes KPIs such as:

* **Total Products**
* **Total Brands**
* **Total Categories**
* **Average Price**
* **Average Calories**

---

## 💡 Key Analytical Questions

The project focuses on questions such as:

1. Which food categories contain the most products?
2. Which brands have the largest product presence?
3. Which categories have the highest average calorie content?
4. Which categories have higher average sugar levels?
5. Which categories have higher average fat content?
6. Which categories have higher average protein content?
7. How are nutritional variables distributed?
8. What relationships exist between calories, fat, sugar, and protein?
9. How does product pricing vary across categories and brands?

---

## 📁 Project Structure

```text
Packaged-Foods-India-Analysis/
│
├── data/
│   ├── packaged_foods_india.csv
│   └── packaged_foods_cleaned.csv
│
├── notebooks/
│   └── packaged_foods_analysis.ipynb
│
├── tableau/
│   └── packaged_foods_dashboard.twbx
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

## 📈 Project Outcome

The project demonstrates an end-to-end data analytics workflow:

**Data Cleaning → EDA → Statistical Analysis → Visualization → Dashboard → Insights**

It showcases practical skills in **Python, Pandas, data cleaning, outlier analysis, exploratory data analysis, data visualization, Tableau, KPI development, and interactive dashboard design**.

---

## 👩‍💻 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Outlier Detection
* Statistical Analysis
* Data Visualization
* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Tableau
* Dashboard Development
* KPI Tracking
* Business Insights

---

## 📌 Conclusion

This project converts packaged-food data into a structured analytical solution by combining Python-based data preparation and EDA with Tableau-based interactive visualization.

The analysis provides a clearer understanding of **product distribution, brand presence, pricing, and nutritional characteristics**, while the Tableau dashboard enables users to explore these insights interactively.
