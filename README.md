#  AtliQ Hospitality Revenue Analysis

This project is part of the **Codebasics Resume Challenge**. It analyzes real-world hotel data to uncover insights and provide recommendations to the Revenue Team of **AtliQ Grands**, a five-star hotel chain in India. The goal is to reverse revenue decline and optimize business decisions using data.

---
##  Live Demo & Resources

-  **Live Power BI Dashboard** → [View Dashboard](<iframe title="Hospitality_Analysis" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiYTc4YzJiYmEtZGMwYS00OTYwLWFjYmUtMzViNzg4MmM3MTFhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=413535e1bcb5a87eeab3" frameborder="0" allowFullScreen="true"></iframe>)
-  **Video Presentation** → [Watch on YouTube](https://youtu.be/your-video-link)


---

##  Problem Statement

**AtliQ Grands** is facing a decline in revenue and market share due to growing competition and ineffective decision-making. As part of their strategic initiative to integrate data intelligence, they hired a data analyst (me!) to uncover key business insights from their historical data and help drive smarter decisions.

---

##  Objective

- Identify patterns in **revenue, occupancy, ADR, RevPAR**
- Analyze **cancellation/no-show rates** and their impact on revenue
- Evaluate **performance across booking platforms, room classes, and properties**
- Provide **strategic recommendations** to optimize revenue and efficiency

---

## 🗃 Dataset Overview

The project is based on 5 CSV files:

| File Name                   | Description |
|----------------------------|-------------|
| `dim_date.csv`             | Contains calendar details like date, week no, month, and day type |
| `dim_hotels.csv`           | Information about hotel properties including city and category |
| `dim_rooms.csv`            | Room category mapping (Standard, Premium, etc.) |
| `fact_aggregated_bookings.csv` | Daily aggregated room booking data (bookings & capacity) |
| `fact_bookings.csv`        | Individual booking records with status, revenue, and ratings |

---

## 📈 KPIs Calculated

- **Revenue** – Total and Realized
- **RevPAR** (Revenue per Available Room)
- **ADR** (Average Daily Rate)
- **Occupancy Rate**
- **Realization %**
- **Cancellation %**
- **Average Ratings**

---

## 🛠 Tools Used

- **Power BI** – Dashboard design, DAX calculations, visualization, data modelling


---

## 📌 Key Insights

- 🔸 **Revenue dropped by 81.7% in Week 32** while ADR remained steady — potential seasonal or demand-side issue.
- 🔸 **Cancellation rate of 24.83%** led to ~₹199M in lost revenue — policy or reminder systems needed.
- 🔸 **Bangalore and Hyderabad underperforming** despite large capacities — explore local marketing strategies.
- 🔸 **Weekends have higher occupancy (44.2%)** than weekdays — suggest adjusting weekday pricing.
- 🔸 **Tripster has highest ADR (₹12,780)** but lowest volume — potential to scale revenue via targeted offers.

---


---

## 💡 Recommendations

- Revise pricing strategy to balance **ADR vs Occupancy** and boost **RevPAR**
- Reduce cancellations through flexible policies and **pre-arrival reminders**
- Prioritize marketing for properties with **high ratings but low bookings**
- Strengthen partnerships with **platforms providing high ADR & realization**

---


