# Exploratory Data Analysis (EDA) for Healthcare Appointments

## Overview

This repository contains Python code for Exploratory Data Analysis (EDA) on a healthcare dataset related to patient appointments. The analysis aims to explore various factors influencing patient attendance at appointments.

## Dataset

The dataset used for this analysis is available in the file `data set for eda.csv`. It includes information about patient appointments, such as appointment dates, patient characteristics, and whether the patient showed up for the appointment (`NoShow`).

## Libraries Used

- pandas
- numpy
- datetime
- matplotlib
- seaborn

## Key Steps in the Analysis

1. **Data Loading and Initial Exploration:**
   - Loaded the dataset using `pandas`.
   - Checked the shape and information about the dataset.

2. **Data Preprocessing:**
   - Modified date and time columns into standard form.
   - Created new columns for weekday information.
   - Renamed and dropped columns for clarity.
   - Checked for missing values (none found).

3. **Data Visualization:**
   - Visualized the distribution of the target variable (`NoShow`).
   - Explored the percentage of appointments attended and missed.

4. **Data Cleaning:**
   - Checked for and handled any potential data cleaning requirements.
   - Created age groups for better analysis.

5. **Correlation Analysis:**
   - Explored the correlation of predictors with the target variable (`NoShow`).
   - Plotted a correlation matrix heatmap.

6. **Bivariate Analysis:**
   - Conducted bivariate analysis for specific columns like 'Hypertension' and 'Age_group'.
   - Explored the distribution of variables for both categories of the target variable (`NoShow`).

## Findings

1. Female patients have taken more appointments than male patients.
2. The show rate is almost equal for age groups, except Age 0 and Age 1, with an 80% show rate for each age group.
3. Each neighborhood has an almost 80% show rate.
4. Patients without a scholarship have a higher show rate (around 80%) compared to those with a scholarship (around 75%).
5. Patients without hypertension have a show rate of around 78%, while patients with hypertension have a higher show rate of around 85%.
6. Patients without diabetes have a show rate of around 80%, while patients with diabetes have a higher show rate of around 83%.
7. Patients who have not received an SMS have a higher show rate (around 84%) compared to those who have received an SMS (around 72%).
8. There are no appointments on Sundays, and appointments on Saturdays are significantly fewer than on other weekdays.

## Suggestions for Further Analysis

1. Time-series analysis to identify patterns in appointment attendance over time.
2. Feature engineering and additional data exploration for more insights.
3. Building predictive models to forecast appointment no-shows.

Feel free to explore the Jupyter notebook for a detailed step-by-step analysis.
