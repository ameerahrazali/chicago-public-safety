# Boston Public Safety Dashboard (2016–2017)

Brief one-liner about the project:  
This interactive dashboard explores crime trends in South Boston (2016–2017), using Excel and Power BI to analyze severity, timing, and location patterns in public safety.

---

## 1. Project Summary

- **Type:** Final-year academic group project
- **Objective:** Provide actionable insights into public safety using crime data
- **Tools:** Excel (EDA & data prep), Power BI (dashboard development)
- **Dataset:** [Kaggle – Crimes in Boston](https://www.kaggle.com/datasets/AnalyzeBoston/crimes-in-boston)

---

## 2. Research Objectives & Questions

| Objective | Research Questions |
|----------|--------------------|
| **1. Crime Trends & Severity** | - What are the peak hours for crime?<br>- Are there yearly crime trends?<br>- How does crime severity vary by district?<br>- Which UCR categories are prevalent by district? |
| **2. Crime Hotspots** | - What are the most common districts for crimes? |
| **3. Temporal & Seasonal Analysis** | - How do monthly crime rates vary?<br>- What is the 24-hour crime distribution?<br>- Which districts report the highest crime volume?<br>- Are certain months/seasons safer?<br>- How does crime frequency vary overall? |

---

## 3. Data Preparation

- **Initial size:** 300k+ records
- **Filtered by:**
  - **Years:** 2016–2017
  - **Districts:** South Boston, Roxbury, Dorchester, Mattapan, Hyde Park, South End, Jamaica Plain
  - **Focus:** Public safety-related offenses only
  - **Final rows used:** 56,109

### Derived Attributes (Created in Excel)

| Attribute         | Description                              |
|------------------|-------------------------------------------|
| `offense_severity` | Severity level (felony, misdemeanor, petty) |
| `district_name`   | Full district name                       |
| `occurred_date`   | Date of occurrence                       |
| `occurred_time`   | Time of occurrence                       |
| `season`          | Winter, Spring, Summer, Autumn           |
| `type_of_day`     | Weekday or Weekend                       |

---

## 4. Dashboard Access

Due to platform restrictions, the full interactive dashboard is **not available for public web viewing**.

- **Download Full Dashboard (.pbix):**  
  [OneDrive Link](https://xuliujun1-my.sharepoint.com/:u:/g/personal/75900_office365proplus_co/EZ-nUDGe14lMr8gBX1gehOcB5QyUVGwvllEJu_9uGMjoXg?e=5QJ4oL)  
  *(Requires [Power BI Desktop](https://powerbi.microsoft.com/desktop) to open)*

- **View Interactivity Demos (GIFs):**

### Dashboard Demos

#### Authority Dashboard 1 – Crime by Time & Severity
![Authority Dashboard 1 Demo](assets/authority1_demo.gif)

#### Authority Dashboard 2 – Crime Hotspot Map
![Authority Dashboard 2 Demo](assets/authority2_demo.gif)

#### Public Dashboard – Temporal & Seasonal Trends
![Public Dashboard Demo](assets/public_demo.gif)

---

## 5. Dashboard Overview

### Dashboard 1: Crime by Time & Severity
- Slicers: Year, District
- Visuals: Crime totals, time-of-day trends, annual frequency, severity by district, UCR Part breakdown

### Dashboard 2: Crime Hotspots
- Slicers: Year, District
- Visuals: Crime totals, district-level map of incidents

### Dashboard 3: Monthly, Seasonal, and Daily Trends
- Slicers: Year, District, Type of Day
- Visuals: Monthly frequency, 24-hour distribution, seasonality, common incident types

---

## 6. Insights by Objective

### Objective 1: Crime Trends & Severity

- Crimes occur most frequently between **10 AM and 10 PM**, peaking at **4 PM**; early mornings see the fewest.
- Crime rates from **2016–2017** remained stable, with no strong long-term trend.
- **Dorchester** and **Roxbury** reported the highest felony and misdemeanor cases.
- **Part 3 crimes** (serious offenses) make up **98.53%** of all incidents, requiring focused attention on severe cases.

---

### Objective 2: Crime Hotspots

- **Roxbury (11.58k)** and **Dorchester (11.25k)** recorded the highest crime volumes.
- Crime incidents are heavily clustered across all districts, with central and southeast South Boston showing the most density.
- Hotspots may relate to **population density** and **socio-economic factors**.

---

### Objective 3: Temporal and Seasonal Trends

- **May** sees the highest monthly crime rate; **October** the lowest.
- Risk is highest during the day, particularly around **4 PM**, and lowest from **12–4 AM**.
- **Jamaica Plain** is consistently the safest district; **Roxbury** has the highest rate.
- **Autumn and spring** show increased activity in Roxbury and Dorchester.
- Top incidents include **vehicle accidents**, **medical assistance**, and **investigations**—reflecting both criminal and public safety concerns.

---

_This project was developed as part of a final-year academic coursework in data analytics, focusing on real-world data storytelling and visualization._
