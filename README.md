# Predicting Contraceptive Choice by a Demographic and Socioeconomic Analysis
This repository presents a comprehensive study aimed at predicting the contraceptive method choices (No-use, Long-term, or Short-term) of women based on their demographic and socioeconomic characteristics. Using a dataset of 1,473 married women, this project employs exploratory data analysis (EDA) and a Random Forest Classifier to identify the primary drivers of family planning decisions.

# Key Research Questions
The analysis specifically answers:

Q1: How do age, parity, and education differ across method groups?

Q2: How do living standards and media exposure relate to choice?

Q3: Does employment status affect contraceptive autonomy?

Q4: Which factors emerge as the strongest predictors overall?

# 1. Contraceptive_data.xlsx
This is the raw dataset file containing 1,473 observations used for the entire analysis. It includes 10 specific demographic and socioeconomic columns:

-Demographic Data: Wife's age and the number of children ever born.

-Education Data: Educational attainment levels for both the wife and husband.

-Socioeconomic Data: Husband's occupation, wife's employment status, and the standard of living index.

-Contextual/Target Data: Wife's religion, media exposure, and the final contraceptive method choice (the target variable).

# 2. Mini_DSc_Project_Code.ipynb
This is the interactive Jupyter Notebook where the actual data science workflow is executed. It contains:

-Data Cleaning: Code for loading the Excel file, checking for missing values, and validating data types.

-Exploratory Data Analysis (EDA): Python code using matplotlib and seaborn to generate histograms, count plots, and box plots to visualize the data.

-Statistical Logic: Calculations for correlations and class distributions of the target variable.

-Machine Learning: The implementation of the Random Forest Classifier, including the 70/30 train-test split, model training, and performance evaluation.

# 3. Project_Code_DSc.pdf
This file is a static export of the completed analysis code and its results. It serves as a permanent record of the project's technical execution, featuring:

-Full Source Code: A chronological display of all Python input cells.

-Execution Outputs: All generated graphs, such as the "Distribution of Wife's Age" and "Feature Importance Ranking".

-Model Results: Final metrics, including the 56.56% accuracy score and the confusion matrix.

# 4. Project_Report_DSc.pdf
This file contains the analytical discussions and conclusions derived from the data. It translates the raw code into human-readable insights:


-Analysis of Findings: Written explanations of how factors like media exposure and education impact contraceptive choice.

-Research Question Answers: Specific sections dedicated to answering questions about demographic differences, socioeconomic impacts, and predictive factors.
-Predictor Insights: A deep dive into why wife's age and number of children were identified as the strongest predictors of choice.
