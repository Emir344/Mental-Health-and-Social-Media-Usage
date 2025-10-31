Project Proposal

# Mental Health and Social Media Usage

DSA210 – Introduction to Data Science

Motivation:

Social media has become an indispensable aspect of everyday living in our century. However, excessive social media use has been connected to possible detrimental impacts on mental health, such as elevated levels of loneliness, anxiety, and depression.
The motivation of this study is to investigate whether there is a quantifiable correlation between the amount of time spent on social media and mental health indicators (such as anxiety or depression) in various nations.

Data Sources:

Mental Health Dataset (includes worldwide data on mental health conditions, such as substance abuse, anxiety, and depression):
Source1: https://ourworldindata.org/mental-health
Data file1: mental-health-and-substance-use.csv

Internet and Social Media Usage Dataset (contains annual statistics on the average daily use of social media, internet penetration, and smartphone ownership worldwide):
Source2: https://ourworldindata.org/social-media
Data file2: share-of-individuals-using-the-internet.csv or time-spent-on-social-media.csv

-Data Enrichment

The two datasets will be combined based on the nation and year variables to increase the project's scope.
The enhanced dataset will make it possible to compare patterns like:

How the frequency of anxiety or depression is correlated with the average amount of time spent on social media.

The association between social media and mental health differs by region.

-Analysis Plan

1-Data Collection, Cleaning & Omitting and Other Actions.
2-Import CSV files from OWID.
3-Consolidate datasets by country and year.
4-Manage missing values (NAs) and normalize percentage and time data.

Analysis Techniques:

1-Exploratory Data Analysis (EDA): For -Showing global patterns of mental health problems
                                       -Comparing social media use across countries in terms of choosen intervals(years)
                                       -Finding connections between social media time and mental health rates

2-Statistical Testing: -For Using t-tests and correlation tests to determine whether the                          
                        results are significant.

3-Modeling:  -Using social media and internet usage data, create simple or numerous linear 
              regression models to forecast mental health levels.


4-Visualization: -Build scatter plots with regression lines by continent.
                 -Make heatmaps to show how mental health changes with social media use.

-Tools & Environment: -Python and its specific libraries to analyse the data

Anticipated Results:

1-Identifying if inflated social media usage corresponds with higher depression or anxiety rates.
2-Comprehending which countries proclaims the strongest correlations.
3-Establishing a set of interactive visualizations and statistical summaries.

-Limitations & Future Work:

1-Bias may be introduced into the analysis due to missing or inconsistent data from certain countries.
2-We cannot claim that social media directly causes depression or anxiety because the project can only demonstrate correlation rather than causation.




