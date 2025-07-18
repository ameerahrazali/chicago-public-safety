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

## 2. Team & Roles

| Name                   | Responsibility                        |
|------------------------|----------------------------------------|
| Wan Ameerah (author)   | Exploratory Data Analysis (EDA)        |
| Ain Aqilah             | Exploratory Data Analysis (EDA)        |
| Syamimi Izzati         | Data Cleaning & Filtering              |
| Nadia Elysya           | Dashboard Design & Visualization (Power BI) |

---

## 3. Research Objectives & Questions

| Objective | Research Questions |
|----------|--------------------|
| **1. Crime Trends & Severity** | - What are the peak hours for crime?<br>- Are there yearly crime trends?<br>- How does crime severity vary by district?<br>- Which UCR categories are prevalent by district? |
| **2. Crime Hotspots** | - What are the most common districts for crimes? |
| **3. Temporal & Seasonal Analysis** | - How do monthly crime rates vary?<br>- What is the 24-hour crime distribution?<br>- Which districts report the highest crime volume?<br>- Are certain months/seasons safer?<br>- How does crime frequency vary overall? |

---

## 4. Data Preparation

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

## 5. Dashboard Access

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

## 6. Dashboard Overview

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

## Insights by Objective

### Objective 1: Crime Trends & Severity

This objective focuses on analyzing crime frequency by time, year, severity, and offense categories.

- **Crime by Hour:**  
  A line chart visualizes crime frequency throughout the day. The most crimes occur between **10 AM and 10 PM**, peaking around **4 PM**, while the fewest occur at **4 AM**. This suggests a correlation between crime rates and public activity.

- **Yearly Trends:**  
  A time-series chart shows daily crime counts from **January 2016 to December 2017**. The highest spike was on **September 15** with **131 cases**, while the lowest occurred between **October 1 and 16**, with only **1 to 5 cases daily**. However, no strong long-term increasing or decreasing trend is observed, suggesting a relatively stable crime rate during this period.

- **Crime Severity by District:**  
  A bar chart compares felony, misdemeanor, and petty offenses across districts. **Dorchester and Roxbury** report the highest numbers of felonies and misdemeanors, indicating more severe crime issues. Other districts predominantly show petty offenses.

- **UCR Classification:**  
  A pie chart illustrates the crime distribution by **UCR Part**. **Part 3 crimes** (serious offenses such as violent and property crimes) dominate with **98.53%**, while **Part 2 crimes** (less serious) make up only **1.47%**. This indicates a need for focused attention on high-severity crimes in the region.

---

### Objective 2: Crime Hotspots

The second dashboard maps crime distribution to identify hotspots across South Boston.

- **Geographical Clusters:**  
  A crime map shows dense clustering across **all districts**, especially in **Roxbury (11.58k cases)** and **Dorchester (11.25k cases)**. Other notable areas include **Mattapan (9.2k)**, **South End (8.7k)**, and **South Boston (5.8k)**.

- **Hotspot Concentration:**  
  The highest crime densities appear in **central and south-eastern parts** of South Boston. These patterns suggest possible links to **population density or socio-economic conditions**, informing potential areas for intervention and resource allocation.

---

### Objective 3: Temporal and Seasonal Trends

The third objective focuses on monthly, seasonal, and hourly crime patterns to improve public awareness.

- **Monthly Trends:**  
  A bar chart shows that crime rates are **highest in May** and **lowest in October**, following a nearly linear trend with slight fluctuations across months.

- **24-Hour Crime Pattern:**  
  A line chart reveals a higher risk of crime during **daylight and early evening**, especially around **4 PM**. The safest hours are between **midnight and 4 AM**.

- **District Safety Levels:**  
  Among the districts, **Roxbury has the highest crime rate**, while **Jamaica Plain is consistently the safest**.

- **Seasonal Distribution:**  
  **Roxbury and Dorchester** experience higher crime counts in **autumn and spring**, whereas **Jamaica Plain** remains relatively safe across all seasons.

- **Common Incident Types:**  
  A tree map shows the most frequent incidents are **motor vehicle accidents** and **medical assistance**, followed by **investigations, towing, property loss**, and **warrant arrests**—highlighting not only crime but broader public safety needs.

---

_This project was developed as part of a final-year academic coursework in data analytics, focusing on real-world data storytelling and visualization._
