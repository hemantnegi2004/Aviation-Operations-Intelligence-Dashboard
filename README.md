# ✈️ Aviation Operational Intelligence Dashboard (Power BI)

This project showcases a real-time **flight operations dashboard** built using Power BI to analyze and monitor key airline performance metrics such as on-time performance, delay causes, cancellations, and turnaround times.

---

## 📌 Objective

To simulate how a **Data Analyst in the aviation industry** (e.g., at Air India) can use historical and operational flight data to deliver insights that optimize flight scheduling, reduce delays, and improve turnaround efficiency.

---

## 🧠 Key Features

- ✅ **Top Delay Cause Detection** using DAX (`Weather`, `Crew`, etc.)
- 📊 **Delay Trends Over Time** (volume and severity)
- 🧭 **Route-wise Cancellation Hotspots**
- 🛫 **Aircraft Turnaround Time Analysis**
- 💡 **KPIs**: On-Time Performance %, Average Delay (mins), Cancellation Rate, and more
- 🎯 Fully interactive with **filters by Airline, Aircraft Type, Delay Cause, Airport, and Route**

---

## 📂 Dataset

A simulated dataset of **1,000+ flight records**, including:
- Scheduled vs Actual Departure/Arrival times  
- Delay Cause (Weather, Crew, ATC, etc.)  
- Aircraft Type  
- Origin and Destination airports  
- Turnaround Time  
- Cancellation status  

🗂️ Columns:
- `Flight_ID`, `Airline`, `Aircraft_Type`, `Origin`, `Destination`  
- `Scheduled_Departure`, `Actual_Departure`, `Scheduled_Arrival`, `Actual_Arrival`  
- `Delay_Cause`, `Cancelled`, `Turnaround_Time_Minutes`

---


## 🛠 Tools & Technologies

- **Power BI** (Data modeling, DAX measures, visual design)
- **DAX** (Custom KPIs: Delay %, Turnaround, Top N Causes)
- **Python (for data generation)** – *optional script included for dataset simulation*

---

## 📊 KPIs Used

| KPI | Description |
|-----|-------------|
| On-Time Performance % | % of flights departing within 15 mins of schedule |
| Avg Departure Delay | Average delay in minutes |
| Top Delay Cause | Most frequent reason for delay |
| Avg Turnaround Time | Ground operation efficiency |
| Cancellation Rate | % of total flights cancelled |
| Delay Trends | Daily view of delay volume and severity |

---

## 🧑‍💼 Use Case

This project reflects real-world responsibilities of a **Data Analyst at an airline** like Air India, helping optimize:
- Flight planning
- Block time decisions
- Operational bottlenecks
- Real-time performance tracking

---

## 📎 Files Included

- `Airline_Operations_Dataset.csv` – simulated flight data  
- `Aviation_Operations.pbix` – Power BI dashboard  
- `delay_cause_analysis.dax` – sample DAX snippets  
- `README.md` – this file

---

## 📌 Future Improvements

- Incorporate real airline data (OTP & AAI API)  
- Add passenger load factor and revenue metrics  
- Deploy dashboard via Power BI Service for live access  
- Include predictive analysis for delay forecasting

