# PowerBI-SwiftRoute-Logistics-Dashboard

## 📌 Project Overview
SwiftRoute Logistics is a performance analytics project built using **Power BI** to evaluate the operational efficiency of **hubs, drivers, and vehicles** across a logistics network. The dashboard analyzes **27,979 delivery orders** to transform raw operational data into **decision-ready insights** that support capacity planning, performance monitoring, and process optimization.

The analysis covers **order volume, delivery time, hub capacity utilization, driver efficiency, and vehicle performance**, enabling business stakeholders to quickly identify strengths, inefficiencies, and improvement opportunities.

---

## 🎯 Business Objectives
- Track overall order fulfillment performance  
- Measure average delivery time at driver and vehicle levels  
- Assess hub-wise order capacity and workload distribution  
- Identify high-performing and underperforming drivers and vehicles  
- Support operational decisions using data-backed KPIs  

---

## 📊 Key KPIs & Metrics
- **Total Orders Processed** – Volume indicator of operational scale  
- **Average Delivery Time** – Primary efficiency metric  
- **Orders by Hub** – Capacity utilization and workload balance  
- **Driver Performance Rating** – Delivery efficiency and consistency  
- **Vehicle-Level Average Delivery Time** – Asset performance comparison  

---

## 🧩 Dashboard Structure & Analysis

### 1️⃣ Executive Overview
Provides a consolidated view of logistics performance:
- Total number of orders processed  
- Overall average delivery time  
- Hub-wise order distribution for capacity comparison  

**Insight:**  
A small number of hubs handle a disproportionately high share of total orders, indicating potential capacity strain and the need for load balancing.

---

### 2️⃣ Hub Performance Analysis
- Orders processed by each hub  
- Comparison of hub capacity utilization  

**Insight:**  
Certain hubs consistently operate close to maximum capacity, while others remain underutilized, suggesting opportunities to redistribute orders and optimize network efficiency.

---

### 3️⃣ Driver Performance Analysis
- Average delivery time by driver  
- Performance rating analyzed against driver experience  

**Insight:**  
Drivers with higher experience levels generally show lower average delivery times, though several low-experience drivers outperform the network average—highlighting best practices that can be scaled through training.

---

### 4️⃣ Vehicle Performance Analysis
- Average delivery time by vehicle  
- Performance comparison across vehicle types  

**Insight:**  
Delivery performance varies noticeably across vehicles, indicating that vehicle type and utilization patterns directly impact delivery efficiency and should be considered in route planning.

---

## 📐 DAX Measures Used (Calculated Metrics)

The following DAX measures were created to derive business KPIs and performance metrics used across the dashboard:

<img width="367" height="802" alt="image" src="https://github.com/user-attachments/assets/fe69fc51-e04c-4fa9-b0bb-6390520db749" />

**Previous month On Time Delivery Rate-**
<img width="750" height="26" alt="image" src="https://github.com/user-attachments/assets/65938de6-f979-4697-a0dd-23b52846a9fb" />

**Month on Month Avg Delivery Time-**
<img width="813" height="33" alt="image" src="https://github.com/user-attachments/assets/0bdb060c-5a5f-4250-80ea-e52f1ccefba2" />

**Star Rating** of driver's performance-

<img width="454" height="93" alt="image" src="https://github.com/user-attachments/assets/1cde3529-a083-48e1-beda-576750bb91cf" />



Also created **New Table** naming as Date Table to have all the date related data in one place:

<img width="366" height="339" alt="image" src="https://github.com/user-attachments/assets/3653c0a6-d089-4089-96c6-83542ee38abe" />


**DAX function for Day of Week-**

<img width="745" height="48" alt="image" src="https://github.com/user-attachments/assets/535ab0ab-be64-4d64-924c-460076a8dccc" />

---

## 🛠️ Tools & Technologies Used
- **Power BI** – Interactive dashboard development and reporting  
- **Power Query** – Data cleaning, transformation, and preprocessing  
- **DAX** – KPI calculations and performance measures  
- **Excel / CSV** – Source data format  

---

## 🧠 Key Business Insights
- **27,979 orders** were analyzed in **2023 & 2024**, with an overall **average delivery time of ~35.8 hours** across the network
- Overall analyzed KPIs are
  - <img width="114" height="45" alt="image" src="https://github.com/user-attachments/assets/4c174854-cb7d-4a58-84d0-f257b7305daf" />

  - <img width="88" height="46" alt="image" src="https://github.com/user-attachments/assets/3eb46e6e-66e5-4e12-be50-3eb285fa4f68" />

  - <img width="121" height="42" alt="image" src="https://github.com/user-attachments/assets/cc60cc52-1e43-4c79-9c66-ac8533ddfee2" />

- The **top 3 hubs** that handles most of the orders are - **El paso Hub, Houston Hub and Dallas Main Hub** indicating high operational concentration and potential capacity risk
- There are **12 vehicles** which are in **under maintenance all the time**, should keep an eye on it and resolve this problem either by replacing or repairing them so that efficiency and utillisation can be increased

---

## 📁 Data Modeling Approach
- **Fact Table:** Orders
- **Dimension Tables:**  
  - Drivers  
  - Vehicles  
  - Hubs  
  - Date  

A **star schema** data model was implemented to ensure efficient filtering, accurate aggregations, and scalable reporting.

---

## 📈 Skills Demonstrated
- Business KPI identification and translation into dashboards  
- Data cleaning and transformation using Power Query  
- Analytical data modeling using star schema  
- DAX-based performance calculations  
- Insight-driven dashboard storytelling  

---

## 🚀 Future Enhancements
- Predictive analysis for delivery delays  
- Fuel cost and vehicle maintenance analytics  
- Route-level performance optimization

---

## 📷 Dashboard Preview
_Add dashboard screenshots here_
<img width="931" height="549" alt="Home dashboard" src="https://github.com/user-attachments/assets/42663ab3-e696-47de-9e56-73804beef922" />

<img width="924" height="549" alt="Hubs overview" src="https://github.com/user-attachments/assets/4701efb5-c5eb-4b3b-a26a-faa99beb599d" />

<img width="932" height="545" alt="Drivers Overview" src="https://github.com/user-attachments/assets/b53d57e1-7e5c-4640-be25-3290fa863e50" />

<img width="931" height="548" alt="Vehicles Overview" src="https://github.com/user-attachments/assets/3d05763d-1dda-48e4-8dfa-8a8759fd3b6f" />





---

⭐ If you find this project useful, consider starring the repository!
