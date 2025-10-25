# EDA-Project-FedEx-Logistics-Performance-Analysis
<img width="500" height="268" alt="image" src="https://github.com/user-attachments/assets/6ad861fc-1cc9-4edd-a305-335340d4d57f" />




#  **FedEx Logistics Data Analysis (EDA Project)**

##  Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on a **FedEx logistics dataset** to gain insights into delivery efficiency, cost optimization, and customer satisfaction.  
The analysis highlights trends in **shipment modes, delivery delays, freight cost, and insurance**, helping FedEx identify areas for operational improvement.

---

##  Business Objective
The main goal of this project is to:
- Understand logistics performance through data.  
- Identify factors causing **delivery delays** and **cost variations**.  
- Suggest data-driven recommendations to **improve efficiency and profitability**.  

---

##  Steps Performed
1. **Data Loading & Understanding** – Read the dataset and explored its structure.  
2. **Data Cleaning** – Handled missing values, corrected data types, and removed duplicates.  
3. **Univariate Analysis** – Studied distributions of shipment mode, delivery status, etc.  
4. **Bivariate & Multivariate Analysis** – Explored relationships between weight, cost, and delivery time.  
5. **Visualization & Insights** – Used visual charts to uncover hidden trends.  

---

##  Dataset Overview

- Rows & Columns: 10,324 rows, 33 columns

##  Key Columns:

- 1. Country
- 2. Shipment Mode
- 3. Delivery Timelines
- 4. Product Details
- 5. Vendor Information
- 6. Delivery Cost & INCO Terms

---
 
##  Data Preprocessing & Feature Engineering

*  Converted date columns to datetime format for accurate analysis.
*  Removed PO Sent to Vendor Date due to excessive missing data.
*  Filled missing values in Dosage using mode.
*  Detected outliers using IQR method.
*  Created Delivery Time = Delivered to Client Date − Scheduled Delivery Date to analyze on-time vs delayed deliveries.

---

##  Key Visualizations
1.  **Shipment Mode Distribution** – Identified the most used and cost-effective shipment methods.  
2.  **Delivery Delays by Country** – Highlighted regions with frequent delivery delays.  
3.  **Shipment Weight vs Freight Cost** – Showed how shipment weight impacts cost.  
4.  **Delivery Performance by Mode** – Compared on-time delivery across shipment modes.  
5.  **Correlation Heatmap** – Showed the relationship between weight, freight cost, and insurance value.

---

##  Key Insights
- Heavier shipments lead to higher **freight and insurance costs**.  
- **Air shipment** ensures faster delivery but at a higher expense.  
- Some countries experience frequent **delivery delays**, needing infrastructure improvements.  
- Strong correlation found between **weight**, **freight cost**, and **insurance** — enabling pricing strategy optimization.  

---

##  Recommendations
- Implement **weight-based pricing discounts** for bulk shipments.  
- Improve delivery routes and **reduce regional delays** through partnerships.  
- Offer **tiered insurance options** based on shipment weight/value.  
- Develop **data-driven pricing models** for cost transparency.  

---

##  Tech Stack
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Jupyter Notebook / Google Colab**

---

##  Conclusion
This project demonstrates how data analytics can help FedEx enhance operational efficiency, reduce costs, and improve customer satisfaction.  
The insights from this EDA can serve as a foundation for building **predictive models** or **logistics optimization systems** in the future.

---



