# Netflix-Data-Cleaning-EDA-Project

# Objective

Analyze Netflix content to understand:

Content distribution
Growth trends
Content types
Country-wise contribution

# Business Questions
# Q1. What is the distribution of Movies and TV Shows on Netflix?

Analysis

Movies: 6131
TV Shows: 2666

# Insight

Movies dominate the Netflix catalog, accounting for approximately 70% of the content. This suggests that Netflix has historically focused more on movie-based content than television series.
# Q2. How has Netflix's content library grown over time?

Analysis

2019 = 1999 titles
2020 = 1878 titles
2021 = 1498 titles

# Insight

Netflix experienced rapid growth between 2016 and 2019. Content additions peaked in 2019, indicating aggressive content expansion during this period.

# Q3. Which years saw the highest content additions?

# Insight

The highest number of titles were added in 2019. This may reflect Netflix's strategy to expand its global content library and strengthen market presence.

# Data Cleaning Performed
Missing Values
Column	Action
director	Filled with "Unknown"
cast	Filled with "Unknown"
country	Filled with "Unknown"
rating	Filled with "Not Rated"
duration	Filled with "Unknown"
date_added	Removed rows with missing values
Data Type Conversion
df['date_added'] = pd.to_datetime(df['date_added'])
Duplicate Check
df.duplicated().sum()

No duplicate records found.

# Skills Demonstrated
Python
Pandas
Data Cleaning
Missing Value Treatment
Datetime Handling
Exploratory Data Analysis (EDA)
Business Insights Generation
Data Visualization

# This project demonstrates end-to-end data cleaning and exploratory data analysis using Python and Pandas. The analysis focuses on identifying content trends, distribution patterns, and growth of Netflix's content catalog.

## Author
Preeti Raj

Aspiring Data Analyst | Python | SQL | Power BI

