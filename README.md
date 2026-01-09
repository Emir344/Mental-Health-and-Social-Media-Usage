# Mental Health and Digital Media Usage  
**DSA 210 Term Project**

---

## Project Motivation

Digital media usage has increased throughout the recent decade because of the increasing utilization of technological tools like smartphones, computers, and other devices. Simultaneously, mental health disorders such as anxiety, depression, bipolar disorder, and schizophrenia have revealed an increasing public health concern.

My motivation of choosing this topic is to observe whether there is a noticeable correlation between digital media usage and mental health trends in the USA. Especially, this project’s main goal is to investigate whether changes in digital media consumption over time are related with changes in mental health prevalence.

This project includes data science techniques to explore trends, observe, predict patterns and at the end to make assumptions about research. We are making this by aggregating two datasets, mental health data and digital media usage data.

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
- Managed missing values  
- Merged datasets by year to create a whole dataset  

---

## Exploratory Data Analysis (EDA)
- Digital media usage increased rapidly over time  
- Mental health trends differ significantly across disorders  
- Bar plots were preferred due to the narrow yearly observations  

---

## Standardized Trend Analysis
- Mental health variables standardized using z-score normalization  
- Easy to compare mental disorders  
- Depression, anxiety, bipolar disorder, and schizophrenia have shown different patterns when observed  

---

## Statistical Analysis
- Spearman correlation analysis due to non-linearity and robustness  
- Hypothesis testing for better interpretation  
- Results revealed a substantial association between digital media usage and depression trends  

---

## Machine Learning Methods

ML techniques to predict depression prevalence using digital media usage and time as predictors.

### Models Used
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Leave-One-Out Cross-Validation  
- Root Mean Squared Error (RMSE)  

### ML Result
Depression prevalence trends can be estimated by using digital media usage and time. Ridge regression presented the most trustable outcomes because of its delicate standardization.

---

## Results
- Digital media usage increased frequently in time  
- Depression and bipolar disorder showed upward trends  
- Simple regression and ML models performed well  
- The relationship observed is predictive, not causal  

---

## Limitations and Future Work

### Limitations
- Sufficien but small sample size due to the specific years (2008–2017)  
- No causal inference can be made  

### Future Work
- Extending analysis to multiple countries could give us more general point of view  
- Include additional variables such as economic or demographic indicators more realistic outcomes  

---

## Conclusion

This project applied data science techniques to investigate the connection between digital media use and trends in mental health in the US. The aftermath suggests that changeovers in mental health trends, especially depression, are related to increased use of digital media. The strong predictive performance of ML models proved the utility of digital media usage as a predictor.

Consequently, this project demonstrates how datasets can be used to learn more about important social complications.

---

## References
- IHME, Global Burden of Disease (2024), processed by Our World in Data  
- BOND Internet Trends (2019), processed by Our World in Data  
- https://ourworldindata.org/mental-health
- https://ourworldindata.org/grapher/daily-hours-spent-with-digital-media-per-adult-user 
- https://www.bondcap.com/report/it19/#view/41  







