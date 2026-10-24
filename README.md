# Netflix-Content-Catalog-Analytics
Analyzed Netflix movies and TV shows using MySQL and data cleaning techniques. Created SQL queries and an interactive dashboard to explore content ratings, genres, countries, and release trends.


## 📌 Project Overview

Netflix Content Catalog Analytics is a data analytics project designed to
explore Netflix's movie and TV show catalog using data cleaning, SQL,
exploratory data analysis, and an interactive dashboard.

The project analyzes content distribution, ratings, release years,
countries, genres, and catalog additions to identify meaningful patterns
within the dataset.

The goal is to demonstrate practical data analytics skills and present
findings through SQL queries, data visualizations, and business insights.

## 🎯 Project Objectives

- Analyze the distribution of movies and TV shows.
- Identify countries contributing the most titles.
- Explore content ratings and genre categories.
- Examine release-year and catalog-addition trends.
- Identify and handle missing values and data-quality issues.
- Write SQL queries for business-oriented analysis.
- Build an interactive dashboard to explore the findings.
- Present data-driven insights in a GitHub portfolio project.

## 📂 Dataset Information

The dataset contains information about Netflix titles, including movies
and TV shows.

| Attribute | Details |
|---|---|
| Dataset | Netflix Titles |
| Total Records | 8,807 |
| Total Columns | 11 |
| Movies | 6,131 |
| TV Shows | 2,676 |
| Release-Year Range | 1925–2021 |
| Data Format | CSV |

## 🛠️ Tools & Technologies
- SQL (MySQL) — Data analysis , business queries,cleaning dataset,handling Duplicate value
- CSV — Dataset storage
- Power bi — Interactive dashboard interface
- <img width="1302" height="705" alt="Screenshot 2026-10-23 133114" src="https://github.com/user-attachments/assets/ac30a2f0-0967-435e-b32d-c487b7a150de" />

- GitHub — Version control and project documentation

## 🧹 Data Cleaning & Preparation

The dataset was reviewed and prepared for analysis.

Key data-quality tasks included:

- Checking for duplicate records.
- Identifying missing values.
- Reviewing missing director, cast, and country information.
- Handling missing values in ratings and catalog-addition dates.
- Correcting three records where duration values appeared in the
  rating column.
- Standardizing relevant fields for analysis.
- Preparing a cleaned CSV file for further exploration.

### Data Quality Summary

| Check | Result |
|---|---:|
| Total Records | 8,807 |
| Total Columns | 11 |
| Exact Duplicate Rows | 0 |
| Missing Directors | 2,634 |
| Missing Cast Values | 825 |
| Missing Country Values | 831 |
| Missing Date Added Values | 10 |
| Missing Rating Values | 4 |
| Missing Duration Values | 3 |

Missing values were reviewed as part of data preparation rather than
assuming that every missing value should be replaced with zero.

## 📊 SQL Analysis

The project includes 40 MySQL queries organized into analytical topics.

### Topics Covered

1. Basic data exploration
2. Movie and TV show distribution
3. Content ratings analysis
4. Country-wise content analysis
5. Genre and category analysis
6. Release-year analysis
7. Catalog-addition trends
8. Data-quality checks
9. Advanced analytical queries


