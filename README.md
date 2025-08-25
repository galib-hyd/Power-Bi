# Flight Status Dashboard (Power BI)

## Project Overview
This project is a **Power BI dashboard** that analyzes **2 million+ flight records** from the **Federal Aviation Administration (FAA)**.  
It provides insights into flight operations, delays, and cancellations using an optimized **star schema data model**.

---

## Features
- **Data Source**: FAA datasets (Flights, Airlines, Airports, Cancellation Codes).  
- **Data Transformation**: Performed using **Power Query**.  
- **Data Model**: 
  - Fact Table: Flights  
  - Dimension Tables: Airlines, Airports, Cancellation Codes  
- **DAX Measures**: Total Flights, Delayed Flights, % Delayed, etc.  
- **Visualizations**:  
  - **Cards** – Total Flights, Delayed Flights, Cancelled Flights  
  - **Bar Charts** – Flights by Airport, Delay Rate by Airline  
  - **100% Stacked Bar** – Flights by Status  
  - **Column Chart** – Cancellations by Day of Week  
  - **Doughnut Chart** – Cancellations by Type  

---

## Files
- `Flight_Status_Dashboard.pbix` – Main Power BI dashboard file.  
- `flights.csv`, `airlines.csv`, `airports.csv`, `cancellation_codes.csv` – Datasets used.  

---

## Screenshots
<img width="1910" height="958" alt="image" src="https://github.com/user-attachments/assets/8b6547b2-8e29-4890-8aa3-2a1af3599082" />

<img width="1275" height="764" alt="image" src="https://github.com/user-attachments/assets/cf42db63-ba3a-49c6-b1be-2f395b19c9c0" />

<img width="1807" height="729" alt="image" src="https://github.com/user-attachments/assets/88283e65-4874-4ab7-a120-c6eff48457a9" />


---

## How to Use
1. Download the `.pbix` file and open in **Power BI Desktop**.  
2. Select CITY or AIRLINE from bar charts, to see on-time, delayed, canceled flights.  

---
