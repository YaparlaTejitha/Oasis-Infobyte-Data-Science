# Oasis-Infobyte-Data-Science

This repository contains my submissions for the Oasis Infobyte Data Science Internship tasks. All analysis has been done using Python in Jupyter Notebooks.

---

## 🌸 Task 1: Iris Flower Classification

### 📌 Project Objective
The goal of this project is to build a machine learning classification model that can accurately predict the specific species of an Iris flower (`Iris-setosa`, `Iris-versicolor`, or `Iris-virginica`) based on its physical measurements:
* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

### 🛠️ Key Steps Followed
1. **Data Cleaning & Exploration:** Inspected the dataset for missing values and used scatter plots to see how flower species separate based on features.
2. **Data Preprocessing:** Split the dataset into training and testing sets for fair evaluation.
3. **Model Training:** Trained a classification machine learning algorithm to recognize patterns in measurements.
4. **Performance Evaluation:** Analyzed performance using a Confusion Matrix to ensure high precision across all three species.

### 💻 Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## 📉 Task 2: Unemployment Analysis in India (2020)

### 📌 Project Objective
Unemployment is measured by the unemployment rate, which is the number of people who are unemployed as a percentage of the total labor force. This project focuses on analyzing the economic shock and sharp increases in the unemployment rate across India caused by the COVID-19 pandemic in 2020.

### 📊 Key Visualizations & Discoveries
1. **Regional Lockdown Shock (Line Graph):** Grouped the data by months and macro-regions (North, South, East, West) to capture the timeline of the crisis. The chart shows a massive, uniform upward spike in April 2020, capturing the immediate economic impact of the strict nationwide lockdown.
2. **Top 10 Hardest-Hit States (Horizontal Bar Graph):** Aggregated the data by individual geographic states to rank the overall impact. The analysis reveals that states like **Haryana** and **Tripura** suffered the highest average unemployment rates during the pandemic.
3. **Urban vs. Rural Sector Analysis (Line Graph):** Dissected the dataset by worker demographics to contrast city vs. village labor dynamics. The urban sector experienced a significantly higher peak due to the total shutdown of private businesses, retail, and office spaces, whereas the rural sector recovered faster due to ongoing agricultural activity.

### 🛠️ Key Steps Followed
1. **Dataset Integration:** Safely handled and cleaned two separate data sources (`Unemployment_Rate_upto_11_2020[1].csv` and `Unemployment_in_India[1].csv`) to build a comprehensive view of the timeline.
2. **Data Wrangling:** Cleaned data structures, standardized column layouts, managed empty rows (`.dropna()`), and reformatted dates for clean time-series plotting.
3. **Visualization:** Generated professional, warning-free exploratory data plots using advanced charting parameters.

### 💻 Technologies Used
* **Language:** Python
* **Libraries:** Pandas, Matplotlib, Seaborn
