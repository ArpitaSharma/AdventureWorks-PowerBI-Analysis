# AdventureWorks Executive BI Dashboard
> **Transforming raw retail data into a scalable, interactive business intelligence solution.**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=microsoftpowerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data_Analysis_Expressions-blue?style=for-the-badge)
![SQL](https://img.shields.io/badge/SQL-Optimization-00758F?style=for-the-badge&logo=mysql&logoColor=white)

---

## 📈 Project Overview
This project delivers a comprehensive executive-level overview of **$24.9M in total revenue** and **$10.5M in profit**. By architecting a robust data model, I enabled stakeholders to track global performance, identify seasonal revenue trends, and simulate pricing strategies using "What-If" analysis.

### 🔗 [Click Here to View the Full Project Folder](AdventureWorks_Project/Report)

---

## 🛠️ Technical Deep-Dive

### 🏗️ Data Architecture (Star Schema)
I built a high-performance **Star Schema** with centralized fact tables for Sales and Returns, connected to 7 dimension lookups. This design ensures:
* **Optimized Query Performance:** Reduced system latency through efficient 1:Many relationship cardinality.
* **Data Integrity:** Established a "Single Source of Truth" for customer, product, and territory attributes.



### 🧠 Advanced DAX Logic
I engineered over 30+ custom measures to drive complex business logic:
* **Time Intelligence:** Rolling 10-day and 90-day averages to smooth out seasonal fluctuations.
* **What-If Simulations:** Dynamic parameters allowing executives to adjust prices and instantly visualize the impact on profit margins.
* **KPI Benchmarking:** Custom "Target Gaps" to monitor Monthly Revenue and Orders against 110% growth targets.

---

## 🎨 Visual Storytelling & Insights

| [Executive Dashboard](AdventureWorks_Project/Image/Executive%20Worksheet.png) | [Customer Intelligence](AdventureWorks_Project/Image/Customer%20Worksheet.png) |
| :--- | :--- |
| ![Dashboard](AdventureWorks_Project/Image/Executive%20Worksheet.png) | ![Customer Detail](AdventureWorks_Project/Image/Customer%20Worksheet.png) |
| **Highlights:** Real-time KPI tracking for Orders (25.2K) and Return Rates (2.2%). | **Highlights:** Top 100 customer segmentation and revenue-per-customer analysis. |

### 🚀 Key Business Insights
* **Top Product:** "Tires and Tubes" identified as the highest-volume product type.
* **Regional Growth:** North America represents the largest market share, with geospatial visualizations identifying untapped growth areas in the Pacific.
* **Risk Management:** Identified "Shorts" as the most returned product type, prompting a quality control review.

---

## 📂 Repository Structure
* **[/Report](AdventureWorks_Project/Report)**: Final `.pbix` project file.
* **[/Scripts](AdventureWorks_Project/Scripts)**: Full DAX library and SQL cleaning scripts.
* **[/Image](AdventureWorks_Project/Image)**: High-resolution screenshots and Star Schema diagrams.
