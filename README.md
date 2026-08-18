# Pharmaceutical Sales Analysis - Power BI
<img width="2752" height="1536" alt="pharmaceutical_sales" src="https://github.com/user-attachments/assets/8df9bec5-9b25-44c6-922f-4cb9d8bc28bd" />

## 📌 Project Overview
Datamatrix-ml Pharmaceuticals is a leading pharmaceutical manufacturing company with a strong global presence. This project focuses on analyzing the sales data for the German and Polish markets. As the company conducts sales through appointed regional distributors rather than directly to end customers, this project leverages data-sharing agreements to access wholesale-to-retail transactions for deeper business insights.

## 🎯 Project Objectives
The primary goal is to deliver actionable insights into the company’s sales performance through in-depth data analysis and interactive Power BI dashboards tailored to different business stakeholders:

*   **Executive Committee:** Provide a high-level snapshot of overall sales performance (trends, top products, sales by country/city) for strategic decision-making.
*   **Sales Manager/Rep:** Enable operational teams to monitor detailed sales performance by distributor, customer, and channel.
*   **Head of Sales:** Support leadership in evaluating sales team effectiveness, performance by product class, and identifying top-performing sales representatives.

## 📊 Dataset Overview
The dataset represents wholesale-to-retail sales transactions sourced from authorized distributors. Key dimensions include:
*   **Geographical:** Country, City, Latitude, Longitude.
*   **Distributor & Sales:** Distributor name, Customer Name, Channel (e.g., Hospital, Pharmacy), Sub-channel.
*   **Product:** Product Name, Product Class, Quantity, Price, Total Sales.
*   **Time Dimension:** Month, Year.
*   **Sales Organization:** Sales Rep, Manager, Sales Team.

## 🛠️ Workflow & Solution Approach
1.  **Data Collection:** Consolidated raw sales data from multiple regional distributors.
2.  **Data Cleaning & Preparation:** Handled missing values, standardized categorical fields, validated sales metrics, formatted dates, and added geographic state fields.
3.  **Data Modeling:** Transformed the flat transactional data into a structured **Star Schema**, separating fact and dimension tables to support efficient querying and relationships.
4.  **Data Analysis:** Analyzed sales across dimensions such as time, geography, product, channel, and organization structure.
5.  **Visualization & Reporting:** Built interactive role-based dashboards to deliver comprehensive insights.
<p align="center">
  <img width="2502" height="1512" alt="data-modelling" src="https://github.com/user-attachments/assets/48fbcc34-73b6-46ed-91e5-ae2f915828ef" />
  <br>
  <i>Image 1. Star Schema Data Modelling.</i>
</p>


## 📈 Dashboard Reports
The Power BI solution is divided into three main reporting pages:
1. **Executive Summary:** An at-a-glance view of total sales, top products, and geographical distribution across Germany and Poland.
<p align="center">
  <img width="3034" height="1708" alt="dashboard_executive-tab" src="https://github.com/user-attachments/assets/582aa66f-da31-459e-ba9f-eff57f6b8e78" />
  <br>
  <i>Image 2. Executive Summary Report.</i>
</p>

2. **Distributor & Customer Analysis:** Detailed analysis of top distributors and customers, including sales by channel and drill-down capabilities into specific products.
<p align="center">
  <img width="3032" height="1703" alt="dashboard_sales-rep-tab" src="https://github.com/user-attachments/assets/5bc60917-3b76-46ca-bf29-2e952bc7cf9d" />
  <br>
  <i>Image 3. Distributor & Customer Analysis Report.</i>
</p>

3. **Sales Team Performance:** Tracks performance across different sales teams, top sales managers, and individual sales rep contributions by product class.
<p align="center">
  <img width="3035" height="1708" alt="dashboard_headsales-tab" src="https://github.com/user-attachments/assets/ec5400cb-eb2d-4381-af04-fbcde340718b" />
  <br>
  <i>Image 4. Sales Team Performance Report.</i>
</p>

## 💻 Tools Used
*   **Microsoft Excel / Power Query:** Data cleaning, transformation, and initial preparation.
*   **Microsoft Power BI:** Data modeling, visualization, and interactive reporting.

## 🔗 Live Dashboard & Demo
* **Public Dashboard:** [Power BI Service Link](https://app.powerbi.com/view?r=eyJrIjoiOTUwYmFjNTYtNjIxNi00YjgzLWExYzQtMWU4MTM3ZTc4ZDk4IiwidCI6IjFkNTE2OWFjLWM3Y2ItNDI3NS05NzY0LWJmOGM5YzM2NGE0YyIsImMiOjEwfQ%3D%3D)
* **Dashboard Demo Video:** [Demo Link](https://drive.google.com/file/d/1vqwtl1sKLgGW9_pYj_m8KUFpk65t2KIE/view?usp=sharing)

## 👇 Get in touch
[![email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:devindrayhanandaw@gmail.com)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/devindrw/)
