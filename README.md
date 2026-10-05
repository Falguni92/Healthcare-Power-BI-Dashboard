# Healthcare Patient Analytics Dashboard

A comprehensive Power BI dashboard analyzing healthcare patient data across 9,216 records, providing insights into patient demographics, wait times, department performance, and satisfaction scores.

## 📊 Project Overview

This interactive dashboard helps healthcare administrators track and analyze:
- Patient demographics (age, gender, race)
- Department-wise patient distribution and wait times
- Patient satisfaction trends
- Appointment scheduling patterns (AM/PM visits)

## 🔍 Key Insights

- **9,216 total patients** tracked across the dataset (April 2019 - October 2020)
- **58.6% of patients** had no department referral, highlighting a significant gap in care coordination
- Average patient satisfaction score of **4.99/10** (based on 27% response rate)
- Neurology and Physiotherapy departments show the **highest average wait times**

## 🛠️ Data Cleaning & Analysis Process

This project involved significant data quality work:
- Identified and corrected a data transformation error where satisfaction scores of "0" were incorrectly converted to null values, skewing the average
- Fixed a filtering issue that was excluding 73% of patient records from key metrics
- Restructured department referral categorization to surface previously hidden "No Referral" patients
- Corrected date hierarchy issues causing misleading month-over-month trend visualizations

## 📁 Dashboard Pages

1. **Overview** — High-level KPIs including total patients, average wait time, satisfaction score, and admin rate
2. **Demographics** — Patient breakdown by race, age group, and department referral
3. **Performance** — Department-wise wait time analysis and satisfaction trends over time

## 🎥 Demo Video

[https://github.com/user-attachments/assets/540d1e73-5086-495c-a2d2-6c35b8ad5ea6]

## 🖼️ Screenshots

### Overview Page
![Overview](Page%1_Overview.png)

### Demographics Page
![Demographics](Page%2_Demographics.png)

### Performance Page
![Performance](Page%3_Performance.png)

## 🧰 Tools Used

- **Power BI Desktop** — Data modeling, DAX measures, and visualization
- **Power Query** — Data cleaning and transformation

## 📥 How to View

Download the `.pbix` file and open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) to explore the dashboard interactively.

---

*This project was built as a data analysis exercise to demonstrate skills in data cleaning, DAX calculations, and dashboard design in Power BI.*
