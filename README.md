# ✈️ Airline Customer Reviews Dashboard

## 📌 Project Overview

This project analyzes **British Airways customer reviews** from March 2016 to October 2023. The goal was to design an **interactive Tableau dashboard** that highlights customer satisfaction across key flight experience metrics and provides actionable insights for business decisions.  

It demonstrates my ability to:  

- Clean and structure real-world datasets  
- Build interactive dashboards that answer business questions  
- Translate raw data into meaningful insights for stakeholders  

---

## 🗂️ Data Sources

- **ba_reviews.csv** – Customer review ratings across dimensions:
  - Overall rating (1–10)  
  - Cabin staff service, entertainment, food & beverages, ground service, seat comfort, value for money (1–5)  
- **Countries.csv** – Country codes and names for geographic analysis  

---

## ⚙️ Data Preparation & Approach

- Imported datasets into Tableau and joined on `Place → Country`  
- Created a **dynamic parameter** to allow exploration of different metrics  
- Grouped aircraft types with fewer than 50 reviews into “Various” for clarity  
- Built calculated fields to standardize metrics across visualizations  
- Designed **filter-driven dashboards** tailored for multiple stakeholder needs  

---

## 🖼️ Dashboard Preview

You can view this dashboard on [Tableau Public](https://public.tableau.com/app/profile/apurva.khangar2606/viz/AirlineCustomerReviewsAnalysis/Dashboard12). 

![Airline Customer Review Dashboard](https://github.com/ApurvaKhangar/Airline-Customer-Reviews-Analysis-Tableau/blob/main/Airline%20Reviews%20Dashboard.png)  
---

## 📊 Dashboard Features

- **Trend Analysis:** Track average ratings over time (monthly)  
- **Geographic Breakdown:** Average rating by country  
- **Aircraft Comparison:** Bar charts showing average rating and number of reviews per aircraft type  
- **Summary KPIs:** Quick-view metrics for overall rating and individual categories  
- **Filters:** Seat type, traveler type, aircraft group, continent, and selected metric  

---

## 🔎 Key Insights

- **Impact of COVID-19:** Ratings dropped sharply between late 2020 and 2021, reflecting operational disruptions and travel restrictions.  
- **Consistently Weak Categories:** Entertainment, food & beverages, and value for money scored lowest, indicating high-priority improvement areas.  
- **Overall Performance:** Despite some weak categories, British Airways maintained a 4.2/10 average rating over 7 years.  
- **Aircraft-Specific Findings:** Larger aircraft (Boeing 747, 787) consistently received higher ratings than smaller models (A319, A321), suggesting customer preference for more spacious or modern aircraft.  
