# Boston Public Safety Dashboard (2016–2017)

This project analyzes and visualizes crime data to understand public safety patterns in South Boston using Microsoft Excel for data preparation and Power BI for interactive dashboard development.

---

## Dashboard Access

Due to platform restrictions, the full interactive dashboard is **not available for direct web viewing**. However, you may:

- **Download the complete Power BI dashboard (.pbix):**  
  [Download from OneDrive](https://xuliujun1-my.sharepoint.com/:u:/g/personal/75900_office365proplus_co/EZ-nUDGe14lMr8gBX1gehOcB5QyUVGwvllEJu_9uGMjoXg?e=5QJ4oL)  
  *(Requires Power BI Desktop to open: https://powerbi.microsoft.com/desktop)*

- **Preview dashboard interactivity through demo GIFs below:**

---

## Dashboard Interactivity Demos

### Authority Dashboard 1: Crime by Time & Severity  
Shows filtering by district and time-based trends.  
![Authority Dashboard 1 Demo](assets/authority1_demo.gif)

### Authority Dashboard 2: Crime Hotspot Map  
Shows map visuals and slicer interaction.  
![Authority Dashboard 2 Demo](assets/authority2_demo.gif)

### Public Dashboard: Seasonal and Monthly Crime Patterns  
Demonstrates monthly trend analysis and seasonal drill-down.  
![Public Dashboard Demo](assets/public_demo.gif)

---

## Project Summary

- **Project Type:** Final-year academic group project for a data analytics course
- **Objective:** Provide insights into crime frequency, severity, temporal patterns, and district-level trends in South Boston
- **Data Source:** [Kaggle – Crimes in Boston](https://www.kaggle.com/datasets/AnalyzeBoston/crimes-in-boston)
- **Tools Used:**
  - Microsoft Excel (EDA, feature engineering)
  - Power BI (dashboard development)

---

## Team & Roles

| Name                   | Responsibility                        |
|------------------------|----------------------------------------|
| Wan Ameerah (author)   | Exploratory Data Analysis (EDA)        |
| Ain Aqilah             | Exploratory Data Analysis (EDA)        |
| Syamimi Izzati         | Data Cleaning & Filtering              |
| Nadia Elysya           | Dashboard Design & Visualization (Power BI) |

---

## Research Objectives & Questions

| Objective                     | Research Questions |
|-------------------------------|--------------------|
| **1. Crime Trends & Severity** | - What are the peak hours for crime?<br>- Are there yearly crime trends?<br>- How does crime severity vary by district?<br>- Which UCR categories are prevalent by district? |
| **2. Crime Hotspots**         | - What are the most common districts for crimes? |
| **3. Temporal & Seasonal Analysis** | - How do monthly crime rates vary?<br>- What is the 24-hour crime distribution?<br>- Which districts report the highest crime volume?<br>- Are certain months/seasons safer?<br>- How does crime frequency vary overall? |

---

## Data Preparation

- Raw dataset: Over 300,000 rows
- Final filtered dataset:
  - **Years:** 2016–2017
  - **Districts:** South Boston, Roxbury, Dorchester, Mattapan, Hyde Park, South End, Jamaica Plain
  - **Focus:** Public safety-related crimes only
  - **Rows Used:** 56,109

### Derived Attributes (Created in Excel)

| New Attribute     | Description                             |
|------------------|------------------------------------------|
| `offense_severity` | Crime severity level                   |
| `district_name`   | Full district name                      |
| `occurred_date`   | Date of occurrence                      |
| `occurred_time`   | Time of occurrence                      |
| `season`          | Derived season (Winter, Spring, Summer, Autumn) |
| `type_of_day`     | Weekday or Weekend classification       |

---

## Dashboard Overview

Three Power BI dashboards were created, aligned to the three research objectives:

### Authority Dashboard 1: Crime by Time & Severity (Objective 1)
- **Slicers:** District, Year
- **Visuals:**
  - Total crime cases (number card)
  - Crime by time of day (line chart)
  - Crime frequency over years (line chart)
  - Crime severity by district (bar chart)
  - Crime distribution by UCR Part (pie chart)

### Authority Dashboard 2: Crime Hotspot Map (Objective 2)
- **Slicers:** Year, District
- **Visuals:**
  - Total crime cases (number card)
  - District-level crime map (map visual)

### Public Dashboard: Temporal and Seasonal Trends (Objective 3)
- **Slicers:** Year, District, Type of Day
- **Visuals:**
  - Monthly crime trends (bar chart)
  - 24-hour crime distribution (line chart)
  - Crime by district (bar chart)
  - Crime by season (bar chart)
  - Crime type distribution (tree map)

---

## Key Features

- Interactive slicers for targeted analysis
- District and time-based filtering
- EDA-informed visual selection
- Focused on actionable public safety insights

---

## Key Insights

- Evening hours showed peak crime activity
- Crime trends shifted slightly between 2016 and 2017
- Certain districts had consistently higher severity scores
- Weekends saw slightly higher crime rates
- Winter months showed reduced activity

---

_This project was developed as part of a final-year academic coursework in data analytics, focusing on real-world data storytelling and visualization._
