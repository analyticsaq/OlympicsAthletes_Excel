# 📊 Olympic Athlete Data Analysis using Excel

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
	![KPI1](https://github.com/analyticsaq/Project_SQL_Netflix/blob/main/logo.webp)

```

---

### 2️⃣ Gold Medals for Country

```
-Pivot Table
	Rows: Country Short as Row Labels
	Values: Gold Medals as Sum of Gold Medals
-Pivot Chart
	Choose Bar Chart
	![KPI2](https://github.com/analyticsaq/Project_SQL_Netflix/blob/main/logo.webp)

```

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
	![KPI3](https://github.com/analyticsaq/Project_SQL_Netflix/blob/main/logo.webp)

```

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
	![KPI4](https://github.com/analyticsaq/Project_SQL_Netflix/blob/main/logo.webp)

```

---

### 5️⃣ Medals by Top 5 Country in Every Olympics.

```
-Pivot Table
	Rows: Year as Row Labels
	Values: Total Medals as Sum of Total Medal
    Column: Country as Column Labels.
-Pivot Chart
	Choose Line Chart
	![KPI5](https://github.com/analyticsaq/Project_SQL_Netflix/blob/main/logo.webp)

```

---


## 🎦 Visualization

```
-Removed Gridline
-Fill color
-Add Shapes, Text and Picture
-Copy and Past all five Pivot Chart
-Added Icons, made them Responsive by adding link of sheets to navigate
 Also on others sheets to navigate here and forth.

	![Dashboard](https://github.com/analyticsaq/Project_SQL_Netflix/blob/main/logo.webp)

```

---

## 📌 Findings & Conclusions

- **Total Medals by Country:** Top countries in winning olypics medals 
- **Gold Medals for Country:** Sellers can choose a strategy according to the these categories revenue. 
- **Distribution of Medals by Age Bracket:** These report can be useful in strategizing the product launch.
- **Percentage Distribution of Top 5 Medal Winning Sports:**  Sellers and Buyers both will be helped, by the information of average price of products.
- **Medals by Top 5 Country in Every Olympics:**

---

## 🚀 Final Thoughts

This Excel-based exploratory data analysis offers a strategic overview of Amazon Sales. These insights can help content strategists, analysts, and business stakeholders make informed decisions around content curation, user targeting, and market focus.