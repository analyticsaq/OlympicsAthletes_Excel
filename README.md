# 📊 Olympic Athlete Data Analysis using Excel
![Logo](https://github.com/analyticsaq/OlympicsAthletes_Excel/blob/main/logo.png)


## 📌 Overview

This project involves a comprehensive analysis of Olympic Athlete dataset using Excel. The goal is to extract actionable insights and answer KPIs related to Sports, Country, Age Bracket, and more.

This README outlines the project’s objectives, KPIs, Excel Approach, and key findings.

---

## 🎯 Objectives

- Data Cleaning for Analyzing and Visualization using Excel
- Choosing KPI for available data.
- Visualization for the KPI defined.

---

## 📁 Dataset

- Source: Kaggle - Olympics Athlete Data
- Format: CSV
- Cleaned and structured into a Excel

---

## 🧱 Cleaning

```
-Cleaning by Removing Duplicate, TRIM, PROPER,FILTER.
-Changing Data types by Data Type, Format Cell and Custom.
-Imported a AthleteNames.csv sheet containing Athlete Names and Sports.
-Created Four columns: 
	1. Sports using XLOOKUP in AthleteNames Sheet.
	2. Total Medals using SUM(Gold+Silver+Bronze).
	3. Age Bracket using IFS(), to put numerous age in fewer brackets.
	4. Short forms for Countries like 'IND' for 'INDIA', using INDEX and MATCH form AthleteNames Sheet. 

```

---

## 🧠 KPIs

### 1️⃣ Total Medals by Country

```
-Pivot Table
	Rows: Country Short as Row Labels
	Values: Total Medals as Sum of Total Medals
-Pivot Chart
	Choose Column Chart

```
![KPI1](https://github.com/analyticsaq/OlympicsAthletes_Excel/blob/main/KPI1.png)

---

### 2️⃣ Gold Medals for Country

```
-Pivot Table
	Rows: Country Short as Row Labels
	Values: Gold Medals as Sum of Gold Medals
-Pivot Chart
	Choose Bar Chart

```
![KPI2](https://github.com/analyticsaq/OlympicsAthletes_Excel/blob/main/KPI2.png)

---

### 3️⃣ Distribution of Medals by Age Bracket

```
-Pivot Table
	Rows: Age Bracket as Row Labels
	Values: Total Medals as Sum of Total Medal
-Value Format
	Value format as Percentage.
-Pivot Chart
	Choose Pie Chart

```
![KPI3](https://github.com/analyticsaq/OlympicsAthletes_Excel/blob/main/KPI3.png)

---

### 4️⃣ Percentage Distribution of Top 5 Medal Winning Sports.

```
-Pivot Table
	Rows: Sports as Row Labels
	Values: Total Medals as Sum of Total Medal
-Value Format
	Value formatted as percentage.
-Pivot Chart
	Choose Donut Chart

```
![KPI4](https://github.com/analyticsaq/OlympicsAthletes_Excel/blob/main/KPI4.png)

---

### 5️⃣ Medals by Top 5 Country in Every Olympics.

```
-Pivot Table
	Rows: Year as Row Labels
	Values: Total Medals as Sum of Total Medal
    Column: Country as Column Labels.
-Pivot Chart
	Choose Line Chart

```
![KPI5](https://github.com/analyticsaq/OlympicsAthletes_Excel/blob/main/KPI5.png)

---


## 🎦 Visualization

```
-Removed Gridline
-Fill color
-Add Shapes, Text and Picture
-Copy and Past all five Pivot Chart
-Added Icons, made them Responsive by adding link of sheets to navigate
 Also on others sheets to navigate here and forth.
-Added Slicers(for Years) for making it more interactive and dynamic.

```
![Dashboard](https://github.com/analyticsaq/OlympicsAthletes_Excel/blob/main/Dashboard.png)

---

## 📌 Findings & Conclusions

- **Total Medals by Country:** Information about Top countries in winning Olympics medals, which can help other country to make strategies accordingly.  
- **Gold Medals for Country:** Which country are best in majorly sport, this can help in making many decisions like training, fitness, wellbeing, environment, etc.
- **Distribution of Medals by Age Bracket:** Age Bracket can help countries in deciding which players age group they should be investing time.
- **Percentage Distribution of Top 5 Medal Winning Sports:**  This further can help in deciding in which sport chances of winning medals are high, so countries can put efforts according to their capabilities. 
- **Medals by Top 5 Country in Every Olympics:** This is to get more details about which countries are consistent in performing well in Olympics, so other countries can learn from them in many factors possible.

---

## 🚀 Final Thoughts

This Excel-based exploratory Olympics analysis offers a strategic overview of Olympics Athletes and Sports. These insights can help strategists, analysts, and other stakeholders to make impactful planning and strategies to reach their common goal.
