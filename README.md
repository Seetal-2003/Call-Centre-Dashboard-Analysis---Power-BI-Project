# 📞 Call Centre Dashboard Analysis - Power BI Project

## 📊 Overview:
This project presents an interactive and analytical Power BI dashboard for a call centre. It captures vital metrics like total call volume, call durations, SLA compliance, sentiment distribution, and channel performance. The dashboard is split into two sections — **Home** and **Grid** — allowing high-level KPI tracking and detailed record inspection.

---

## 🎯 Project Objective:
- Track and analyze call centre performance.
- Evaluate effectiveness of communication channels.
- Understand customer sentiments and common call reasons.
- Improve response times and SLA compliance.
- Provide actionable insights for business decisions.

---

## 📁 Dataset:
- **File Name:** `Call Centre dataset.csv`
- **Format:** CSV
- **Data Fields:** Id, Call Timestamp, Call-Centre, Customer Name, Channel, State, City, Reason, Call Duration (mins), Sentiment, SLA Type, etc.

📂 **[Dataset Download Link]:
[Call Centre dataset](Call Centre dataset.csv)
---

## ❓ Key Questions Answered
1. What is the total number of calls?
2. What is the average call duration?
3. What percentage of calls meet the SLA response time?
4. How do call volumes vary by day of the week?
5. Which call centres and states handle the most calls?
6. What are the most common reasons for calls?
7. How are customers interacting across different channels?
8. What does the sentiment analysis reveal about customer experience?

---

## 🛠️ Tools & Techniques Used
- **Power BI:** Visualization and dashboard development.
- **Power Query:** Data cleaning, transformation, and model shaping.
- **DAX Measures:** Custom calculations for KPIs (e.g., total calls, average duration, SLA %).
- **Date Table:** Created using the `CALENDAR` DAX formula for time-based analysis.
- **Visualizations:** Bar charts, pie charts, treemaps, stacked visuals, slicers, and card visuals.
- **Interactive Filters:** Date, City, and Channel slicers for user-driven exploration.

---

## 🔁 Process
1. **Data Loading:**
   - Loaded `Call Centre dataset.csv` into Power BI.
2. **Data Cleaning & Transformation:**
   - Used **Power Query** to shape the data.
   - Removed nulls and fixed data types.
3. **Date Table Creation:**
   - Created a custom date table using:
     ```DAX
     DateTable = CALENDAR(DATE(2020, 10, 1), DATE(2020, 10, 31))
     ```
   - Marked as date table and related with call date field.
4. **DAX Measures:**
   - Total Calls
   - Total Call Duration (Mins & Hrs)
   - Average Call Duration
   - SLA Response % using conditional logic
   - Sentiment Count, Channel Usage, and Call Reasons
5. **Dashboard Design:**
   - **Home Page:** KPIs, Call Distribution, Sentiment, Call Reasons, Channel Usage.
   - **Grid Page:** Detailed call-level data with slicers and filters.

---

## 🖼️ Dashboard Screenshots
### 📌 Home Dashboard
![Call Centre Dashboard - Home](Call%20Centre%20Dashboard_Home.jpg)

### 📌 Grid Dashboard
![Call Centre Dashboard - Grid](Call%20Centre%20Dashboard_Grid.jpg)

---

## 📈 Dashboard Insights
- ✅ **Total Calls:** 32.94K
- ⏱️ **Total Call Duration:** 824.22K minutes (13.74K hours)
- 📞 **Average Call Duration:** 25.02 minutes
- 🎯 **SLA Compliance:** 75.26% calls responded within SLA
- 🗓️ **Busiest Days:** Thursday and Friday
- 🌍 **Top Call Centres:** Los Angeles (13.73K), Baltimore (11.01K), Chicago (5.42K)
- 📡 **Top Channels:** Call Centre (39.86%), Email (32.25%), Chatbot (22.62%)
- 📍 **Top States:** California, Texas, Florida, New York
- 🧾 **Common Call Reasons:** Billing Questions (71.28%), Payments, Service Outage
- 😟 **Customer Sentiment:** Mostly Negative and Neutral feedback

---

## ✅ Conclusion
This Power BI dashboard enables in-depth monitoring of call centre operations. It identifies:
- Inefficiencies in SLA response and customer sentiment.
- Operational patterns across channels, cities, and time.
- Critical areas needing training and resourcing.

By visualizing KPIs and trends interactively, this dashboard empowers stakeholders to take strategic, data-driven actions to improve customer service quality and operational efficiency.

---

## 📂 Files Included
- `Call Centre dataset.csv` – Raw dataset
- `Call Centre Dashboard_Home.jpg` – Home dashboard image
- `Call Centre Dashboard_Grid.jpg` – Grid dashboard image
- `Call Centre Dashboard.pbix` – Power BI report file

📌 **[Download PBIX Dashboard](#)**  
[Call Centre Dashboard](Call Centre Dashboard.pbix)
---


