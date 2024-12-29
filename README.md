# Discrimination_Lawsuit_using_R

🧮 Discrimination Lawsuit: Analyzing Expenditures by Ethnicity and Gender in California DDS

📝 Project Overview

This project investigates potential discriminatory practices in the allocation of funds by the California Department of Developmental Services (DDS). Using 📊 statistical analysis and 🤖 machine learning models, the study examines expenditure disparities across ethnicity, age, and gender. The findings aim to contribute evidence for assessing claims in a discrimination lawsuit.

📚 Table of Contents
	1.	🔍 Introduction
	2.	📂 Dataset
	3.	⚙️ Analysis Workflow
	4.	📈 Results
	5.	▶️ How to Run the Code
	6.	🛠 Dependencies
	7.	🤝 Acknowledgments

🔍 Introduction

This project analyzes expenditure data using:
	•	EDA: 📊 Boxplots and bar charts for data visualization.
	•	Statistical Methods: 📐 Descriptive statistics and random forest modeling.
	•	Objective: To identify systemic biases in resource allocation based on ethnicity, age, and gender.

📂 Dataset

Structure 📑

The dataset includes the following columns:
	•	🆔 ID: Unique identifier for each individual.
	•	👶 Age Group: Categorical (e.g., 0–5 years, 6–12 years).
	•	📅 Age: Numeric representation of age.
	•	👦👩 Gender: Categorical (Female or Male).
	•	💵 Expenditures: Funding allocated to individuals.
	•	🌎 Ethnicity: Categories include Native American, Asian, Hispanic, White Non-Hispanic, etc.

⚙️ Analysis Workflow
	1.	🔧 Data Preprocessing:
	•	Handled missing values.
	•	Encoded categorical variables as factors.
	2.	📊 Visualization:
	•	Side-by-side boxplots for expenditures by ethnicity and age groups.
	•	Bar charts for expenditures by gender and ethnicity.
	3.	🤖 Modeling:
	•	Applied Random Forest to identify variable importance.
	•	Extracted feature importance scores.
	4.	📐 Statistical Testing:
	•	Conducted correlation analysis and tested for group differences.

📈 Results
	•	Boxplots: Show significant disparities in expenditures by ethnicity and age groups.
	•	Bar Charts: Indicate potential gender-based inequities.
	•	Random Forest: Highlights age group and ethnicity as primary predictors of expenditure disparities.

▶️ How to Run the Code
	1.	📥 Download the Files: Ensure you have the project files, including the annotated PDF containing the R code.
	2.	🗂 Prepare the Dataset: Place the dataset California_DDS_Expenditures.csv in your working directory.
	3.	📜 Access the R Code:
	•	Open the provided PDF file and locate the R code in the appendix section.
	•	Copy the code into your preferred R script editor (e.g., RStudio).
	4.	🖥 Execute the Code: Run the script in sections as outlined:
	•	Data Preprocessing
	•	Visualization
	•	Modeling
	5.	📁 Save Outputs: The code will automatically generate and save plots, tables, and other outputs in your working directory.

🛠 Dependencies
	•	R Version: 4.0 or later
	•	Required Libraries:
	•	📊 ggplot2 for visualizations
	•	🧹 dplyr for data manipulation
	•	🌳 randomForest for modeling
	•	📦 caret for data partitioning

🤝 Acknowledgments

This project was conducted by Samanvay Gupta at the University of North Alabama (November 30, 2024). Special thanks to the 📂 California DDS dataset contributors for enabling this research.
