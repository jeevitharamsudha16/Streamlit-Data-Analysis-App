# 📊 Streamlit Data Analysis App

An interactive and user-friendly Streamlit web application for performing **Univariate**, **Bivariate**, and **Multivariate** analysis on any uploaded CSV dataset.

## 🎯 Objective

To build an interactive Streamlit web application that enables users to perform comprehensive data analysis — including **Univariate**, **Bivariate**, and **Multivariate** visualizations — on any uploaded CSV dataset without writing code.


## ⚙️ Key Tasks Performed

### 1. 📁 Dataset Upload & Handling
- Created a sidebar for users to **upload CSV files**.
- Used Pandas to load and display data dynamically.
- Automatically detected **numeric** and **categorical** columns.

### 2. 📊 Univariate Analysis
- Enabled selection of a **single variable** for visual inspection.
- Visualizations included:
  - Histogram (Numerical)
  - Countplot (Categorical)
  - Pie Chart (Top 5 categories)
  - Boxplot (Outlier detection)

### 3. 📈 Bivariate Analysis
- Explored relationships between **two variables**.
- Visualizations included:
  - Line Plot (Numeric vs Numeric)
  - Scatter Plot (Numeric vs Numeric)
  - Bar Plot (Categorical vs Numeric)
  - Boxplot (Categorical vs Numeric)

### 4. 🔬 Multivariate Analysis
- Explored multiple-variable relationships.
- Visualizations included:
  - Pairplot (selected numeric columns)
  - Correlation Heatmap (all numeric columns)

### 5. 🧼 UI & Experience
- Integrated with **Streamlit sidebar navigation**.
- Added custom plot titles, axis labels, and layout formatting.
- Used **Seaborn** and **Matplotlib** for clean, publication-quality plots.



## ✅ Outcomes

- Built a **fully interactive web app** for exploratory data analysis (EDA).
- Enabled **code-free insights** for data practitioners, students, and non-programmers.
- Created a **modular and scalable UI** that can be extended with new features like statistical summaries, data filtering, or export options.


## 📦 Technologies Used

- **Python**
- **Streamlit** – Web framework
- **Pandas** – Data handling
- **Seaborn** & **Matplotlib** – Data visualization
