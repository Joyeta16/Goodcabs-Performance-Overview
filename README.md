# 🚖 GoodCabs: Transportation Performance Analysis


## ![overview (1) (2)](https://github.com/user-attachments/assets/e81fcb5d-dffa-4698-be85-84ce874ceb84) Company Overview

GoodCabs, an imaginary company established two years ago, has quickly become a leading cab service provider in India's tier-II cities. Unlike traditional competitors, GoodCabs is driven by a mission to empower local drivers, helping them build sustainable livelihoods within their communities while providing passengers with exceptional service. Operating across 10 tier-II cities, GoodCabs combines a community-focused approach with a commitment to delivering a seamless travel experience. It aims to solidify its position as a trusted mobility partner in underserved markets.

## 🔎 Problem Statement

Goodcabs has been operating in tier-II cities for two years, but it is still far from reaching its market penetration goals. Despite establishing a solid presence in these areas, the company is struggling to meet its ambitious 2024 targets.  
To overcome this challenge, Goodcabs needs an in-depth analysis of key performance metrics. This analysis will help identify critical growth opportunities and resolve operational inefficiencies that are hindering progress.

## 🎯 Project Objective

The objective of this project is to conduct a comprehensive analysis of Goodcabs' performance across key metrics—such as trip volume, passenger satisfaction, retention rates, trip distribution, and the balance between new and repeat passengers. By evaluating these metrics, the project aims to identify critical growth opportunities, address operational inefficiencies, and provide actionable insights to help Goodcabs achieve its market penetration goals and meet its ambitious targets for 2024.  
The insights from this analysis will support strategic decision-making and drive the company’s growth in tier-2 cities.

## 🛢 Data Overview

Received two SQL databases and eight CSV files for analysis. However, I primarily worked with the SQL databases, using the CSV files for cross-verification purposes.

The two databases are as follows:

1. trips_db: Contains fact tables (fact_trips, fact_passenger_summary) and dimension tables (dim_date, dim_city, dim_repeat_trip_distribution).
2. targets_db: Contains city- and month-specific target tables (monthly_target_trips, monthly_target_new_passengers, city_target_passenger_rating).

The dataset spans from January 1, 2024, to June 30, 2024.

It is fully accessible on the Codebasics website and can be viewed via the following link:  
https://codebasics.io/challenge/codebasics-resume-project-challenge

## 🛠️ Tools

- Data Visualization: Power BI
- Data Analysis : MySQL, DAX

## 🧹️ Data Cleaning & Transformation:

- Used Power Query to clean and transform raw data.  
- Removed duplicates and unnecessary columns.  
- Applied the TRIM function to eliminate leading and trailing spaces.  
- Added conditional columns where necessary.  
- Created a dim_month table with unique months and their start dates.  
- Generated two additional tables in Power BI for filtering purposes:  
  - passenger_type: Contains a single column for passenger type (new/repeated).  
  - Set BM: Includes two columns—Benchmarks (vs Previous month/vs Target) and IDs.


## 📑 Report Inclusions

- [Ad-hoc Business Requests](https://github.com/Joyeta16/Goodcabs-Performance-Overview/blob/main/Ad-hoc%20Business_requests.sql)

### Power BI Report Overview  

This repository showcases a Power BI report hosted on the Power BI Service. Below are screenshots of the report for a quick preview:  
- [Landing Page](https://github.com/Joyeta16/Goodcabs-Performance-Overview/blob/main/Landing_page.png)
- [Finance View](https://github.com/Joyeta16/Goodcabs-Performance-Overview/blob/main/Finance_view.png)
- [Sales View](https://github.com/Joyeta16/Goodcabs-Performance-Overview/blob/main/Sales_view.png)
- [Marketing View](https://github.com/Joyeta16/Goodcabs-Performance-Overview/blob/main/Marketing_view.png)
- [Operations View](https://github.com/Joyeta16/Goodcabs-Performance-Overview/blob/main/Operations_view.png)
- [Executive View](https://github.com/Joyeta16/Goodcabs-Performance-Overview/blob/main/Executive_view.png)

For the full interactive experience, please contact me to request access to the report on Power BI Service.

## 💡 Insights

## 📝 Recommendations

## 🧠 Skills Gained
