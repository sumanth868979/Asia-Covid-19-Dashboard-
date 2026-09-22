![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-107C41?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power_Query-ETL-CC2927?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Data Visualization](https://img.shields.io/badge/Data_Visualization-Dashboard-3776AB?style=for-the-badge&logo=chartdotjs&logoColor=white)
![COVID-19 Analytics](https://img.shields.io/badge/COVID--19-Analytics-E63946?style=for-the-badge&logo=googleanalytics&logoColor=white)

# Asia-Covid-19-Dashboard

## 📸 Dashboard Preview

### Executive Overview
<img width="2208" height="1260" alt="dashboard" src="https://github.com/user-attachments/assets/14ceaa0a-9ff1-4de2-89fc-32288d5b6cbf" />


## Project Overview

The Asia **COVID**-19 Analytics Dashboard is an end-to-end data analytics project developed using Power BI. The project analyzes country-level **COVID**-19 data across Asian countries from **2020** to **2021**, covering total cases, new cases, deaths, testing, and vaccination indicators. The project follows a complete analytics workflow:

Data Cleaning → Data Validation → Data Modeling → **DAX** Measures → Dashboard Design → Business Insights

Power BI was used end-to-end for data cleaning, data modeling, **DAX**-based **KPI** calculation, and interactive visualization.

### Business Problem

The raw **COVID**-19 dataset contained a large number of records, missing values, and multiple types of health metrics, making it difficult to understand the pandemic situation across Asian countries.

This project analyzes Asian **COVID**-19 data to understand how cases, deaths, and vaccination progressed across the region, and which countries showed the highest reported impact.

The project focuses on questions such as:

How did **COVID**-19 cases change across Asia? Which Asian countries reported the highest cases? How did deaths change over time? How was vaccination progressing? Which countries had higher or lower reported **COVID**-19 impact? What major trends could be identified from the Asian data?

Note: This project identifies patterns and trends in the data. It does not establish causal relationships.

### Project Objectives

The main objectives of this project are:

Perform data cleaning and data validation. Check data types, duplicates, missing values, and unusual values. Convert the date column into the correct date format. Calculate the percentage of missing values for each column. Filter the dataset to Asian countries. Build the Power BI data model. Create **DAX** measures for key **COVID**-19 KPIs. Design an interactive dashboard with filters. Validate cumulative measures to avoid double-counting. Identify country-level and time-based **COVID**-19 trends. Generate business insights on cases, deaths, and vaccination. Tools & Technologies Power BI **DAX** (Data Analysis Expressions) ### Power Query ### Dataset Overview

The dataset contains country-level **COVID**-19 data for Asian countries, covering **2020** to **2021**.

### Dataset Details

| Region Covered | Asia | | Time Period | 2020 – 2021 | | Metrics Included | Total Cases, New Cases, Total Deaths, New Deaths, Testing, Vaccination |

### Project Workflow

Raw **COVID**-19 Data
        ↓
### Data Loading
        ↓
### Data Quality Checking
        ↓
### Data Cleaning
        ↓
### Missing Value Handling
        ↓
Filtering to Asian Countries
        ↓
Power BI Data Modeling
        ↓
**DAX** Measure Creation
        ↓
### Dashboard Design
        ↓
### Business Insights
Data Cleaning & Preparation

Power BI (Power Query) was used to prepare the raw **COVID**-19 dataset for analysis.

### Data Cleaning Steps

Loaded the raw dataset into Power BI. Checked data types across all columns. Checked for duplicate records. Checked missing values across the dataset. Calculated the percentage of missing values for each column. Converted the date column into the correct date format. Filtered the dataset to Asian countries only. Reviewed unusual or inconsistent values. Prepared the dataset for the data model and **DAX** measures. ### Important Data Handling Decision

**NULL** values were not automatically replaced with zero, because a missing value could mean the information was not reported, rather than that the actual value was zero. Testing, vaccination, and other health-indicator fields contained significant missing data, and this distinction was treated carefully throughout the analysis.

Data Modeling & **DAX** Measures

After cleaning, a Power BI data model was built and **DAX** measures were created for the core KPIs:

### Total Cases

### Total Deaths ### New Cases ### New Deaths

Cumulative measures were validated to ensure historical records were not incorrectly summed or double-counted.

### Dashboard Design

The dashboard was designed with the following components:

**KPI** cards (Total Deaths, Total Cases, New Cases, New Deaths) Top Asian countries by total cases Asia-adjusted new-case and new-death trend over time Vaccination analysis (total vaccinations vs. people vaccinated) Country-level comparison table (cases and deaths by country) Country and date range filters Business Analysis & Asia Insights ## Rising COVID-19 Cases Across Asia

**COVID**-19 cases increased significantly across Asia over the reporting period. The trend visual makes it possible to identify major waves and periods when reported cases accelerated or declined.

## Uneven Impact Across Countries

**COVID**-19 impact differed considerably between Asian countries. The country comparison shows that reported cases and deaths were not evenly distributed, allowing users to identify countries with substantially higher reported totals.

## Clear Periods of Rapid Growth

The case trend showed clear periods of rapid growth. Using the daily/smoothed case trend helps identify major waves without relying only on individual-day reporting fluctuations.

## Varying Vaccination Progress

Vaccination progress varied between Asian countries. The vaccination visual allows comparison of reported vaccination levels and highlights differences in vaccination coverage across countries.

## Data Availability as a Finding in Itself

Several healthcare, testing, and vaccination fields contained significant missing values. Because of this, **NULL** values were treated carefully instead of being assumed to represent zero — a decision that shaped how the KPIs and trends were interpreted throughout the project.

### Project Visualizations

(Add dashboard screenshots/image links here)

### Project Outcome

This project demonstrates a complete Power BI analytics workflow, starting from raw **COVID**-19 data and progressing through:

Data Cleaning → Data Modeling → **DAX** Measures → Dashboard Design → Business Insights

The analysis identified major **COVID**-19 trends across Asia, highlighted the uneven distribution of cases and deaths between countries, and compared vaccination progress across the region — while carefully handling missing data instead of assuming it represented zero impact.

### Skills Demonstrated

Power BI

---

## 👨‍💻 Author

**Sumanth Balaji**


- LinkedIn: https://www.linkedin.com/in/sumanth-palivela-7186b4346
