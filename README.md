# Mental Health and Digital Media Usage  
**DSA 210 Term Project**

---

## Project Motivation

Digital media usage has increased throughout the recent decade because of the increasing utilization of technological tools like smartphones, computers, and other devices. Simultaneously, mental health disorders such as anxiety, depression, bipolar disorder, and schizophrenia have revealed an increasing public health concern.

My motivation of choosing this topic is to observe whether there is a noticeable correlation between digital media usage and mental health trends in the USA. Especially, this project’s main goal is to investigate whether changes in digital media consumption over time are related with changes in mental health prevalence.

This project includes data science techniques to explore trends, observe, predict patterns and make assumptions about outcomes. We are doing this by aggregating two datasets, mental health data and digital media usage data.

---

## Data Sources

This project uses two datasets from Our World in Data.

### 1. Mental Health Data
- **Source:** Our World in Data – Mental Health  
- **Variables:** Anxiety disorders, Depression, Bipolar disorder, Schizophrenia  
- **Description:** Annual prevalence (%) of mental health disorders by country  
- **Time Period:** 2008–2017  
- **Geographic Focus:** USA  
- **Link:** •	https://ourworldindata.org/mental-health

### 2. Digital Media Usage Data
- **Source:** Our World in Data (BOND Internet Trends, 2019)  
- **Variables:** Daily hours spent on mobile, desktop/laptop, and other connected devices  
- **Description:** Average daily digital media usage per adult  
- **Time Period:** 2008–2017  
- **Geographic Focus:** United States  
- **Link:** https://ourworldindata.org/grapher/daily-hours-spent-with-digital-media-per-adult-user 

---

## Data Preparation
- Filtered datasets by country (USA) and year (2008–2017)  
- Combined digital media usage across device types into a one variable  
- Handled missing values  
- Merged datasets by year to create a whole dataset  

---

## Data Analysis
- Perform exploratory data analysis (EDA) to identify critical trends.
- Use bar plots and standardized visualizations to compare mental health disorders.
- Apply correlation analysis such as spearman to analyze relationship between digital media usage and mental health trends.

---

### Modeling
- Apply machine learning regression models to predict the distribution.
- Regression models: Linear Regression, Ridge Regression, Lasso Regression  
- Evaluate models using Leave-One-Out Cross-Validation.
- Compare model achievement by using Root Mean Squared Error (RMSE).

---

### Instruments and Libraries
- **pandas** and **NumPy** for data manipulation
- **Matplotlib** and **Seaborn** for data visualization
- **scikit-learn** for machine learning models and evaluation

---


 









