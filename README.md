# Power BI Dashboard - Export Order Shipment Analysis

This Power BI dashboard is a self-initiated portfolio project that simulates real-world export order analysis for a large-scale apparel manufacturer. It visualizes detailed insights into order quantities, shipment statuses, open shipments (OS), and commercial cost performance.

📌 Disclaimer: This project is not affiliated with any real organization. All data used is dummy/mock data, modeled based on my prior industry experience in exports and manufacturing.

<table>
  <tr>
    <td>
      <img src="Screenshot 2025-06-18 211825.png" alt="Summary" width="500"/>
    </td>
    <td>
      <img src="Screenshot 2025-06-18 211854.png" alt="OS Analysis" width="500"/>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td>
      <img src="Screenshot 2025-06-18 211928.png" alt="Shipment Performance" width="500"/>
    </td>
    <td>
      <img src="Screenshot 2025-06-18 212008.png" alt="Cost & Commercial" width="500"/>
    </td>
  </tr>
</table>

[![View Dashboard](https://img.shields.io/badge/PowerBI-Dashboard-blue?logo=powerbi)](https://app.powerbi.com/view?r=eyJrIjoiOTU1NTk2MDgtMDQ1YS00MjY0LWJlYWYtYzQxM2UyNDYzYjFhIiwidCI6Ijg2NDU3OWM1LWVjMjctNDAzYi1hMjAwLWFhNjViYmEwMTIyMyIsImMiOjEwfQ%3D%3D)


## Introduction

This dashboard was built as part of a personal initiative to demonstrate skills in data analytics, Power BI dashboard design, and supply chain business intelligence. The data structure and visual design reflect a realistic business scenario in the apparel export domain, including order tracking, cost breakdowns, and performance insights.

The project showcases my end-to-end capability—from raw data modeling to interactive visualization—intended purely for learning and portfolio purposes.

## 🎯 Objective

- <b>Goal:</b> Provide meaningful business insights through data-driven visuals around export orders and shipment performance.

- <b>Role:</b> As a Power BI Developer & Analyst, I created all visuals, DAX measures, data models, and layouts independently.

- <b>Scope:</b> No external requirement—this project is designed to simulate real-world reporting without actual business constraints.

## 📈 Metrics Created

- Total Order Quantity

- Shipped Quantity

- Open Shipment (OS) Quantity

- Shipment %

- Total FOB Value

- Average FOB per Pc

- Replenishment Status

- Cost Breakdown (FOB vs DDP vs DDU vs Plot)

- Buyer/Product Group/Destination Trends

## 🗂 Dataset Overview

Structured mock data was created with fields such as:

- Order Details (fileNos, Export PO, Order Qty, Delivery Date)

- Shipment Info (Shipped Qty, Status, Destination, ETD)

- Cost Metrics (FOB, DDP, DDU, Plot, CM)

- Time Dimensions (Year, Month, Week)

- Product Segmentation (Division, Product Group, Category, Gender_Dep)


## 💻 Technology Stack

- __Tool:__ Microsoft Power BI

- __Domain:__ Apparel Exports / Supply Chain (Simulated)

- __Key Skills Used:__ Power Query, DAX, Data Modeling, Custom Visuals, Page Navigation

## 📄 Dashboard Pages

__1. 🏠 Home (Summary)__ <br>
Snapshot of KPIs, buyer-wise shipment %, OS trends, and division performance with an interactive map.

__2. 📦 OS Analysis__ <br>
Insights into unshipped quantities by buyer, product group, season, and destination.

__3. 🚚 Shipment Performance__ <br>
Analysis of shipment % over time, seasonal patterns, and buyer-wise delivery metrics.

__4. 💰 Cost & Commercial__ <br>
Comparative cost view across multiple pricing structures (FOB, DDP, DDU, Plot), and analysis by division and season.

## 🔍 Key Insights
- High OS in Certain Buyers: Highlights operational bottlenecks and delays.

- Uneven Shipment %: Suggests prioritization gaps in execution.

- Division Cost Differences: Knit and Woven divisions have notable variance in FOB per unit.

- Regional Focus Needed: Some destinations show high OS despite early delivery windows.

- Replenishment Patterns: Can be used to forecast urgent production plans.
