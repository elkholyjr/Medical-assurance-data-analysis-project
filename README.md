# Exploratory Medical assurance data Project

This project provides a hands-on approach to understanding and applying graphical techniques in **Exploratory Data Analysis (EDA)** using Python. It walks through various steps of examining and visualizing a dataset to uncover patterns, spot anomalies, test hypotheses, and check assumptions.

## Project Tasks

The EDA process is broken down into 5 main tasks:

### Task 1: Defining EDA
An overview of the concept and significance of exploratory data analysis, including the goals and methodology used in the project.

### Task 2: Importing Libraries & Exploring the Dataset
- Libraries used: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `scipy`, `sklearn`
- Dataset loaded: `insurance-data.csv`
- Initial exploration: structure, head of the data, and data types.

### Task 3: Handling Missing Values & Outliers
- Checked for missing values
- Identified outliers in the dataset

### Task 4: Visual Analysis
Created a variety of visualizations to better understand the data:
- Distribution plots
- Box plots
- Correlation heatmaps
- Categorical vs. numerical visual comparisons

### Task 5: Analyzing Trends and Relationships
In this final step, the analysis focuses on uncovering trends, relationships, and potential insights that can inform further modeling or business decisions.

---

## Dataset

The dataset used in this project is `insurance-data.csv`, which contains information on:
- Age
- Sex
- BMI
- Children
- Smoker status
- Region
- Insurance Charges

It includes **1338 instances** and **7 features**, with data types ranging across integers, floats, and strings.

---

## Technologies Used

- **Python 3**
- **Jupyter Notebook**
- **Pandas & NumPy** – data handling
- **Matplotlib & Seaborn** – data visualization
- **Statsmodels & Scipy** – statistical analysis
- **Scikit-learn** – preprocessing

---

## Results & Insights

The analysis highlighted key correlations, such as:
- Strong impact of smoking on insurance charges
- BMI and age as contributing factors to higher costs
- Regional and gender-based variations

---

## Getting Started

To run this notebook:

1. Clone the repo
2. Ensure you have the required libraries installed
3. Place `insurance-data.csv` in the working directory
4. Run the `EDAproject.ipynb` notebook
