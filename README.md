# Oasis Infobyte Data Science Internship

This repository contains my final submissions for the Oasis Infobyte Data Science Internship tasks. All machine learning models, data cleaning, and visualizations have been built using Python in Jupyter Notebooks.

---

## 🚨 Internship Verification Note
To the Oasis Infobyte Review Team, please note the following structure regarding my task submissions:
* **GitHub Portfolio (5/5 Tasks):** This repository contains the complete codebase, datasets, and Jupyter Notebooks for all **5 assigned internship tasks**. 
* **LinkedIn Video Demonstrations (3/5 Tasks):** As per the program's flexible guidelines, I have selected my top **3 core projects** to showcase via working video demonstrations on my LinkedIn profile (**Task 1: Iris Flower Classification**, **Task 2: Unemployment Analysis**, and **Task 3:Car Price Prediction with Machine Learning**). 

---

## 🌸 Task 1: Iris Flower Classification
*🎥 Video Demonstration Posted on LinkedIn*

### 📌 Project Objective
The goal of this project is to build a machine learning classification model that can accurately predict the specific species of an Iris flower (`Iris-setosa`, `Iris-versicolor`, or `Iris-virginica`) based on its physical measurements: Sepal Length, Sepal Width, Petal Length, and Petal Width.

### 🛠️ Key Steps Followed
1. **Data Cleaning & Exploration:** Inspected the dataset for missing values and used scatter plots to see how flower species separate based on features.
2. **Data Preprocessing:** Split the dataset into training and testing sets for fair evaluation.
3. **Model Training:** Trained a classification machine learning algorithm to recognize patterns in measurements.
4. **Performance Evaluation:** Analyzed performance using a Confusion Matrix to ensure high precision across all three species.

### 💻 Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## 📉 Task 2: Unemployment Analysis with Python
*🎥 Video Demonstration Posted on LinkedIn*

### 📌 Project Objective
Unemployment is measured by the unemployment rate, which is the number of people who are unemployed as a percentage of the total labor force. This project focuses on analyzing the economic shock and sharp increases in the unemployment rate across India caused by the COVID-19 pandemic in 2020.

### 📊 Key Visualizations & Discoveries
1. **Regional Lockdown Shock (Line Graph):** Captured the timeline of the crisis across macro-regions. The chart shows a massive, uniform upward spike in April 2020, capturing the immediate economic impact of the strict nationwide lockdown.
2. **Top 10 Hardest-Hit States (Horizontal Bar Graph):** Aggregated the data by individual geographic states to rank the overall impact. The analysis reveals that states like **Haryana** and **Tripura** suffered the highest average unemployment rates during the pandemic.
3. **Urban vs. Rural Sector Analysis (Line Graph):** Dissected the dataset by worker demographics. The urban sector experienced a significantly higher peak due to the total shutdown of private businesses, retail, and office spaces, whereas the rural sector recovered faster due to ongoing agricultural activity.

### 💻 Technologies Used
* **Language:** Python
* **Libraries:** Pandas, Matplotlib, Seaborn

---

## 🚗 Task 3: Car Price Prediction with Machine Learning
*🎥 Video Demonstration Posted on LinkedIn*

### 📌 Project Objective
The valuation of a vehicle depends on several real-world factors. This project focuses on building a predictive machine learning system capable of estimating the actual selling price of a car based on structural attributes, mechanical power, and market demand.

### 📊 Model Performance & Insights
* **Model Accuracy (R-squared):** **84.89%**, indicating a strong mathematical relationship between the vehicle attributes and the final pricing.
* **Mean Absolute Error (MAE):** **1.22 Lakhs**, showing that the model's price estimates deviate from actual prices by a remarkably low margin on average.
* **Prediction Visuals (Scatter Plot):** Generated a custom regression evaluation chart tracking Actual vs. Predicted values. The model demonstrates high precision in the 0–10 Lakh consumer car bracket, with natural variance appearing on rarer high-end luxury outliers.

### 🛠️ Key Steps Followed
1. **Feature Encoding:** Used `pd.get_dummies` to transform text categories (`Fuel_Type`, `Selling_type`, `Transmission`) into binary numbers (0s and 1s) for the model matrix.
2. **Data Splitting:** Allocated an 80/20 partition (240 training records, 61 test verification records).
3. **Regression Training:** Fitted a Linear Regression model from Scikit-learn to map out the pricing equations.

### 💻 Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

---

## 📧 Task 4: Email Spam Detection with Machine Learning
*💻 Code & Notebook Exclusive to GitHub*

### 📌 Project Objective
With the rising volume of phishing attempts and junk mail, automated text filtering is essential. This project focuses on building an intelligent Natural Language Processing (NLP) system capable of reading raw text email messages and classifying them as either `Ham (Safe)` or `Spam`.

### 📊 Model Performance & Insights
* **Algorithm Choice:** Multinomial Naive Bayes (optimized for text classification and word-frequency vectors).
* **Feature Extraction:** Implemented `TfidfVectorizer` to scale down the weight of common English stop-words while amplifying distinctive spam-indicative keywords.
* **High Precision Filtering:** The system achieved an exceptional zero false-positive rate inside the test matrix, ensuring that no safe consumer emails are accidentally misclassified or lost in the spam folder.

### 🛠️ Key Steps Followed
1. **Data Selection & Correction:** Cleaned structural anomalies from the Kaggle text dataset by isolating raw classifications and removing redundant unmapped columns.
2. **Text Processing:** Tokenized, lower-cased, and converted text strings into numerical matrix coordinates using Term Frequency-Inverse Document Frequency (TF-IDF).
3. **Model Evaluation:** Visualized performance metrics through a polished Confusion Matrix Heatmap to analyze precise category partitions across 1,115 test samples.

### 💻 Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn (TfidfVectorizer, MultinomialNB), Matplotlib, Seaborn

---

## 📈 Task 5: Sales Prediction Using Python
*💻 Code & Notebook Exclusive to GitHub*

### 📌 Project Objective
Predicting consumer demand is a fundamental requirement for optimizing corporate marketing strategies. This project focuses on building a predictive multiple linear regression machine learning model to accurately estimate overall product sales based on advertising resource allocations across TV, Radio, and Newspaper mediums.

### 📊 Model Performance & Insights
* **Algorithm Implemented:** Multiple Linear Regression.
* **Feature Importance:** Analyzed how multi-channel marketing budgets act as direct numerical indicators for forecasting commercial revenue trends.
* **Strong Line of Best Fit:** The generated evaluation scatter plot shows data clusters tightening close along the prediction trajectory, indicating high variance capture and reliable real-world forecasting capability.

### 🛠️ Key Steps Followed
1. **Data Preprocessing:** Handled structural indexing anomalies by removing redundant ID markers (`Unnamed: 0`) to isolate clean modeling dimensions.
2. **Regression Modeling:** Engineered an 80/20 data split to feed localized marketing spends into a predictive Scikit-Learn linear regression equation.
3. **Advanced Data Visualization:** Constructed a highly stylized regression fit plot mapping actual versus predicted sales values alongside a translucent statistical confidence band.

### 💻 Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn (LinearRegression), Matplotlib, Seaborn

### 💻 Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn (LinearRegression), Matplotlib, Seaborn
