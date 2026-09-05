# Job Market Data Scraping & Exploratory Analysis

## Project Overview

This project collects job-market data through **web scraping** and analyzes the collected data to identify trends in job roles, salaries, experience requirements, locations, companies, work modes, ratings, reviews, and in-demand skills.

The project demonstrates an end-to-end data workflow, starting from **data collection through web scraping**, followed by data cleaning, preprocessing, exploratory data analysis, and visualization.

## Objectives

* Collect job-market data through web scraping
* Build a structured dataset from scraped job listings
* Analyze job-market trends
* Identify high-paying job roles
* Understand the relationship between experience and salary
* Find locations with the most job opportunities
* Identify companies with the highest number of job postings
* Analyze popular work modes
* Identify the most in-demand skills
* Generate meaningful insights from the collected data

## Web Scraping

The job data was collected from a job-listing website using Python-based web scraping techniques.

The scraping process collects information such as:

* Job ID
* Job Role
* Company
* Experience
* Salary
* Location
* Rating
* Reviews
* Key Skills
* Job Link
* Company Link
* Work Mode
* Posted Date

The scraped data is stored in a structured CSV format and then used for further data cleaning and analysis.

> **Note:** Web scraping should be performed in accordance with the target website's terms of service, robots.txt directives, and applicable laws.

## Dataset Features

The dataset contains information about:

* Job ID
* Job Role
* Company
* Experience
* Salary
* Location
* Rating
* Reviews
* Key Skills
* Job Link
* Company Link
* Work Mode
* Posted Date

## Data Cleaning

The following preprocessing steps were performed:

* Removed/handled duplicate records
* Handled missing values
* Extracted minimum and maximum experience
* Extracted salary ranges
* Converted salary values into numeric format
* Processed job locations
* Processed work modes
* Cleaned ratings and reviews
* Prepared skills data for analysis

## Exploratory Data Analysis

The analysis covers:

1. Job-role distribution
2. Salary distribution
3. Salary vs experience
4. Salary by job role
5. Salary by work mode
6. Job distribution by location
7. Company-wise job postings
8. Rating vs salary
9. Reviews vs salary
10. In-demand skills
11. Correlation analysis

## Key Insights

The analysis identifies:

* The most frequently posted job roles
* The highest-paying job roles
* The most active hiring companies
* The locations with the highest number of opportunities
* The most common work modes
* The most demanded skills
* The relationship between experience and salary
* Relationships between salary, ratings, reviews, and other numerical variables

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Web Scraping
* CSV / Excel

## Project Workflow

```text
Job Listing Website
        ↓
   Web Scraping
        ↓
   Raw Job Data
        ↓
Data Cleaning & Preprocessing
        ↓
   Cleaned Dataset
        ↓
Exploratory Data Analysis
        ↓
 Data Visualization
        ↓
   Job Market Insights
```

## Project Structure

```text
Job-Market-Data-Scraping-Exploratory-Analysis/
│
│── linkedin_jobs_cleaned.csv
│── linkedin_jobs_final.csv
│── 01_data_collection.ipynb
│── 02_data_cleaning.ipynb
│── 02_eda.ipynb
│
│
├── README.md
└── .gitignore
```

## Conclusion

This project demonstrates an end-to-end data science workflow, starting with **web scraping and data collection** and continuing through data cleaning, exploratory data analysis, visualization, and insight generation.

The analysis provides useful insights into job-market demand, salary patterns, experience requirements, locations, work modes, companies, and in-demand skills.

The project demonstrates practical experience with **Python, web scraping, Pandas, data preprocessing, exploratory data analysis, and data visualization**.
