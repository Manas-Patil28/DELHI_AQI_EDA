📌 Delhi NCR AQI Analysis (2020–2025)
📊 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Delhi NCR Air Quality dataset (2020–2025) using SQL.

The objective of this project is to analyze air pollution trends, seasonal variations, pollutant impact, and weather relationships affecting AQI levels.

This analysis was performed using Snowflake for writing and executing SQL queries.

🛠 Tools Used

SQL

Snowflake

GitHub

📁 Dataset Details

200,000+ records

25 columns

Time range: 2020 – 2025

Includes:

AQI

PM2.5, PM10, NO2, SO2, CO, O3

Temperature

Wind Speed

Humidity

City

Station

Season

Hour

🔎 Analysis Performed
1️⃣ Basic Exploration

Date range analysis

Record count per city

Total stations

Minimum, Maximum, and Average AQI

2️⃣ Trend Analysis

Monthly AQI trend

Hourly pollution pattern

Seasonal pollution comparison

Weekend vs Weekday comparison

3️⃣ Station-Level Analysis

Most polluted stations

Worst pollution days

4️⃣ AQI Category Distribution

AQI was categorized into:

Good

Satisfactory

Moderate

Poor

Very Poor

Severe

5️⃣ Correlation Analysis

Measured relationship between AQI and:

PM2.5

PM10

NO2

CO

Wind Speed

Temperature

6️⃣ AQI Distribution

Used bucket grouping (FLOOR function) to analyze pollution ranges.

📈 Key Insights

Winter season shows higher average AQI levels.

PM2.5 has the strongest positive relationship with AQI.

Higher wind speed is associated with lower AQI.

Certain stations consistently report higher pollution levels.

Severe AQI days form a significant portion of total observations.
