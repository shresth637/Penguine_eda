# 🐧 Exploratory Data Analysis on Penguin Dataset

## 📖 Project Overview
This project performs a complete Exploratory Data Analysis (EDA) on the Penguins dataset available in Seaborn.  
The goal is to understand the structure, distribution, relationships, and patterns within the dataset before applying any machine learning models.

The dataset contains physical measurements of penguins from different species.

## 📊 Dataset Information

The dataset includes:
- Species (Adelie, Chinstrap, Gentoo)
- Island
- Bill Length (mm)
- Bill Depth (mm)
- Flipper Length (mm)
- Body Mass (g)
- Sex

Each row represents one penguin (cross-sectional data).

## 🔍 EDA Steps Performed

### 1️⃣ Data Inspection
- Checked dataset shape
- Reviewed data types
- Identified missing values
- Generated statistical summaries

### 2️⃣ Univariate Analysis
- Species distribution using countplot
- Body mass distribution using boxplot
- Numerical feature summaries

### 3️⃣ Missing Value Handling
- Filled missing numerical values using median
- Discussed impact of global vs group-wise imputation

### 4️⃣ Bivariate Analysis
- Body mass vs species comparison
- Correlation analysis between numerical features

## 📈 Key Insights
- The dataset is moderately imbalanced across species.
- Gentoo penguins tend to have higher body mass.
- Bill length and flipper length show strong correlation with body mass.
- Some numerical features contain missing values that required imputation.

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib



