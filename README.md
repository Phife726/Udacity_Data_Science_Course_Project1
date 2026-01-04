## Udacity Data Science Course Project #1
This project analyzes historical development indicators to determine how economic and infrastructure factors drive human longevity.

## Analyzing Global Development Drivers
Summary: This project uses the CRISP-DM framework to analyze over 200 countries' historical data, finding that electric power consumption is a stronger predictor of life expectancy than traditional economic metrics like GDP growth. A Random Forest model achieved an R² of 0.61, and simulations suggest a 50% increase in power infrastructure correlates with a +1.03 year gain in life expectancy.

## 1. Project Motivation
This project applies the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework to identify which infrastructure and economic factors are the most potent predictors of human longevity. By analyzing historical data for over 200 countries, the project seeks to determine if foundational infrastructure (like electricity) provides more predictive leverage for national health outcomes than traditional economic growth metrics.

## 2. Project Deliverables

Project_1.ipynb: A comprehensive Jupyter Notebook documenting the six phases of the data science process: Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Findings.
World_Economic_Data_Indicator_List_Final_v2.csv: The source dataset containing historical World Bank indicators from 2000–2024.
README.md: Technical documentation providing an overview of the project scope and results.

## 3. Libraries Used
The following Python stack was utilized to complete the analysis:

Pandas: For data manipulation and cleaning.
Numpy: For numerical operations.
Scikit-learn: For the machine learning pipeline and regression modeling.
Matplotlib & Seaborn: For exploratory data analysis and results visualization.

## 4. Technical Summary of Results

Indicators Analyzed: GDP Growth, Life Expectancy, Trade (% of GDP), Electric Power Consumption, FDI Inflows, and CO2 Emissions.
Feature Engineering: Implemented 1–5 year lagged variables for all predictors to capture temporal development trends.
Model Performance:

Baseline Model: Used as a benchmark (Training Mean).
Linear Regression: Achieved an R² of 0.13.
Random Forest Regressor: Achieved a superior R² of 0.61, proving the non-linear nature of development data.


Key Finding: Electric Power Consumption emerged as the primary predictor of health outcomes, outweighing annual GDP growth rates.
Scenario Insight: A simulation demonstrated that a 50% increase in power infrastructure predicts a gain of +1.03 years in global life expectancy.

## 5. Acknowledgments

Data provided by the World Bank Databank.
Project guidelines and rubric provided by the Udacity Data Scientist Nanodegree program.
