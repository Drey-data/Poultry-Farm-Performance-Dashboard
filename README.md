# Poultry-Farm-Performance-Dashboard
End-to-end Power BI analytics dashboard analyzing poultry farm production, feed efficiency, and flock health using operational farm data.

# Poultry Farm Performance Dashboard  
*(Anonymized Case Study)*

## 📌 Project Overview

This project analyzes daily operational records from a commercial poultry farm and transforms them into an interactive Power BI dashboard designed for management decision-making.

The dashboard provides visibility into flock health, egg production performance, feed usage, and operational efficiency across pens and time. All data has been anonymized and is shared strictly for portfolio and demonstration purposes.

## 📊 Dataset & Scope

- Daily operational records captured at pen level
- Time-based tracking of flock population, egg production, feed intake, mortality, and medication events
- Covers multiple pens monitored concurrently over a defined production period
- Dataset anonymized to protect farm identity and sensitive business information

## 🛠 Tools & Technologies

- Power BI  
  - Power Query for data transformation  
  - Data modeling using fact and dimension tables  
  - DAX for KPI calculations and performance metrics  

- Microsoft Excel  
  - Daily data capture and initial record keeping

## 🧹 Data Preparation & Modeling

- Daily records from multiple pens were consolidated into a single fact table.
- Date, Pen, and Medication dimension tables were created to support a star schema model.
- Medication names were standardized to ensure consistent reporting and analysis.
- Calculated measures were created for key KPIs including mortality rate, production rate, feed per bird, and feed efficiency.
- Relationships were configured as one-to-many with single-direction filtering to ensure accurate aggregation.

## 📈 Dashboard Pages Overview

The Power BI dashboard is organized into four main analytical pages:

- **Executive Overview**  
  Provides a high-level snapshot of farm performance, including population size, mortality rate, production rate, feed usage, and quality indicators.

- **Flock Health & Mortality**  
  Analyzes mortality trends over time and across pens, supporting early identification of health risks and intervention effectiveness.

- **Production Performance**  
  Evaluates egg production trends, production rate by age, peak production points, and pen-level performance differences.

- **Feed & Efficiency**  
  Examines feed consumption patterns, feed per bird, and feed-to-egg efficiency to highlight cost and productivity drivers.
  
## 🔍 Key Insights

- Production performance improves rapidly with flock age but declines noticeably after peak laying periods, reducing overall output efficiency.

- Significant performance differences exist across pens, indicating uneven management practices or environmental conditions.

- Feed consumption does not always scale proportionally with egg production, highlighting periods of reduced feed efficiency.

- Mortality levels are uneven across pens and time, suggesting targeted health or management interventions are required rather than blanket actions.

- Peak production occurs within a narrow age window, emphasizing the importance of age-specific production and feed strategies.
