# Kay Brata - Data Analyst Portfolio
## About
Hi, I'm Kay! Motivated and analytical aspiring Data Analyst seeking an internship to apply and expand my skills in SQL, Excel, Tableau, and Python. Certified in Google Data Analytics and Sololearn, with hands-on experience in data cleaning, visualization, and insights generation through projects. Passionate about leveraging data to drive business decisions and eager to gain practical experience in a professional setting.

My CV in

This is a repository to showcase skills, share projects and track my progress in Data Analytics related topics.

## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.
Analyzing Smart Device Usage Trends for Bellabeat

### Analyzing Smart Device Usage Trends for Bellabeat

**Description:** This project focuses on analyzing a dataset containing smart device usage data to understand user behavior and trends. The dataset includes information on daily activity, steps, heart rate, and sleep monitoring. The project involves data cleaning, exploratory data analysis (EDA), and statistical analysis to derive meaningful insights. The final recommendations are aimed at helping Bellabeat improve its marketing strategies based on user behavior patterns.

**Skills:**  Data cleaning, data analysis, correlation matrices, hypothesis testing, data visualization.

**Technology:** Python, Pandas, Numpy, Seaborn, Matplotlib, SQL.

**Result:** Using Python functions and SQL queries, the analysis revealed that users tend to have higher activity levels in the morning and evening, while weekends show lower engagement. Sleep tracking is a crucial feature used consistently. The findings suggest marketing strategies should target peak activity hours and emphasize wellness tracking features.

**Process**

  ## 1. Business Task (ask)
   **objective:** Understand how consumers use smart devices and apply insights to improve Bellabeat’s marketing strategy. 
     **key question:** 
       objective: Analyzing smart device usage trends to inform Bellabeat’s marketing strategy.
      
 ## 2. Data Collection & Preparation (Prepare)
- [Fitbit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit) (Public Domain)
- Includes daily activity, steps, sleep, and heart rate data.
  
  **Tasks:**
- Download the dataset and store it in an organized folder.
-  Understand the dataset structure – Identify column names, data types, and relationships.
 ## 3. Data Cleaning  (Process)
- Im using sql because the data is big
- I fix the data integrity using this code for :

  1. Minute sleep merge
     
     [SQL Querry](https://console.cloud.google.com/bigquery?sq=1039618084538:4cff56f03da34c1e828733829052eba6) 
     
  2. Heartrate seconds merge
     
[SQL Querry](https://console.cloud.google.com/bigquery?sq=1039618084538:6769cb38275846f083c1b96e98c1612e)

## 4. Perform Analysis (Analyze)
1. Activity Trends
Analyze average steps, calories, and activity minutes per user.

[SQL Querry](https://console.cloud.google.com/bigquery?sq=1039618084538:68c7ac8950e64c8ea423357782c530ee)

2. Sleep Patterns
Find average sleep duration per user.

[SQL Querry](https://console.cloud.google.com/bigquery?sq=1039618084538:f60664bd0d754d3aaf2ba5ca0d703b1b)

3. Correlation Between Sleep and Activity
Check if people who sleep more are more active.

