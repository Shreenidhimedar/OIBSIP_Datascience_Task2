# OIBSIP_Datascience_Task2
Unemployment Analysis with Python

1. Project Overview

This project focuses on analysing unemployment data from India using Exploratory Data Analysis (EDA) techniques. The analysis studies regional and time-based trends in unemployment, with special attention to the impact of the COVID-19 pandemic.

2. Project Objective

The main objective is to explore unemployment data to understand how unemployment rates differ across states and over time, and to compare unemployment before and after the COVID-19 lockdown.

3. Dataset Description

The project uses the "Unemployment in India" dataset from Kaggle. It contains monthly, state-wise records with the following information:

	•	Region (State)
	•	Date
	•	Estimated Unemployment Rate (%)
	•	Estimated Employed
	•	Estimated Labour Participation Rate (%)

4. Technologies Used

	•	Python
	•	Jupyter Notebook
	•	Pandas
	•	NumPy
	•	Matplotlib
	•	Seaborn

5. Data Preprocessing

The dataset was examined to understand its structure, data types and data quality. Column names were cleaned, null values and duplicate rows were checked, and the date column was converted to a proper date format. Additional time-based features were created for the analysis.

6. Exploratory Data Analysis

Exploratory Data Analysis was performed to understand regional and monthly patterns in unemployment.

Visualizations were used to identify trends and differences across states, including:

	•	Region-wise average unemployment rates
	•	Month-wise unemployment trends
	•	Time-series line chart for selected major states
	•	Bar chart of the top 10 states with the highest average unemployment rate
	•	Correlation heatmap of unemployment rate, employment and labour participation rate

7. Pre-COVID vs Post-COVID Comparison

The data was split at the start of the nationwide COVID-19 lockdown (25 March 2020). Average unemployment rates were calculated and compared for the period before and after the lockdown, both overall and state-wise.

8. Observations

Written observations were added after each chart to explain what the data shows. The limitations of the analysis, such as the short time window and the unweighted state averages, are also discussed in the notebook.

9. Conclusion

This project demonstrates how data analysis and visualization techniques can be used to understand unemployment trends and the impact of the COVID-19 pandemic.

It provided practical experience in data cleaning, exploratory data analysis, time-series visualization and drawing insights from real-world data.

10. Internship

Organization: Oasis Infobyte

Domain: Data Science

Task: Unemployment Analysis with Python
