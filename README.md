# Mental Health and Social Media Usage  
**Project Proposal**  

---

## Motivation  
Social media has become an indispensable aspect of everyday living in our century. However, excessive social media use has been connected to possible detrimental impacts on mental health, such as elevated levels of loneliness, anxiety, and depression. The motivation of this study is to investigate whether there is a quantifiable correlation between the amount of time spent on social media and mental health indicators (such as anxiety or depression) in various nations.

---

## Data Sources  

### 1. Mental Health Dataset  
- **Description:** Includes USA data on mental health conditions such as substance abuse, anxiety, and depression.  
- **Source:** https://www.kaggle.com/datasets/thedevastator/global-mental-health-disorders?resource=download&select=Mental+health+Depression+disorder+Data.csv
- **Data file:** `mental-health-and-substance-use.csv`  

### 2. Internet and Social Media Usage Dataset  
- **Description:** Contains annual statistics on average daily social media use, internet penetration in USA. 
- **Source:** https://ourworldindata.org/grapher/daily-hours-spent-with-digital-media-per-adult-user 
- **Data file:** `share-of-individuals-using-the-internet.csv` or `time-spent-on-social-media.csv`  

---

## Data Enrichment  
The two datasets will be merged using **country** and **year** to expand the analysis.  
This enriched dataset will allow comparisons such as:  
-How the frequency of anxiety or depression is correlated with the average time spent on social media.  
-How the relationship between social media use and mental health differs across countries.  

---

## Analysis Plan  

### 1. Data Collection & Cleaning  

1-Data Collection, Cleaning & Omitting and Other Actions.  
2-Import CSV files from OWID.  
3-Consolidate datasets by country and year.  
4-Manage missing values (NAs) and normalize percentage and time data.


### 2. Analysis Techniques  

#### • Exploratory Data Analysis (EDA)  
- Show global patterns of mental health problems.  
- Compare social media use across countries and years.  
- Find connections between social media time and mental health rates.  

#### • Statistical Testing  
- Use t-tests and correlation tests to determine if relationships are paramount.  

#### • Modeling  
- Use social media and internet usage data, create simple or numerous linear regression models to forecast mental health levels.  

#### • Visualization  
- Build scatter plots with regression lines by continent.
- Make heatmaps to show how mental health changes with social media use.  

---

## Tools & Environment  
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels
  
---

## Anticipated Results  
- Identify whether increased social media use is linked to higher anxiety or depression rates.  
- Comprehend which countries proclaims the strongest correlations.  
- Create visual and statistical summaries that highlight global mental health trends.  

---

## Limitations & Future Work  
- Bias may be introduced into the analysis due to missing or inconsistent data from certain countries.  
- The analysis only shows **correlation**, not **causation** , social media may not directly cause mental health issues.  

---






