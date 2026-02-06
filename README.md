# Shipment-Data-Analytics
# Enterprise Shipment & Sales Analytics – Power BI

## Overview
This project implements an **enterprise-grade analytical reporting model** built in **Power BI**, designed using **dimensional modeling and governed semantic layer principles** commonly used in large financial and global enterprises.

The solution enables consistent analysis of **shipment volume, revenue, profit, sales performance, and geographic distribution**, with a strong focus on **time-based comparison and profitability**.

---


## Architecture & Data Model
- **Star Schema**
- **Fact Table**: Shipments (Amount, Boxes, Cost, Profit)
- **Dimensions**:
  - Calendar (time intelligence)
  - Products
  - Salespeople
  - Locations (Geo / Region)

**Design standards**
- One-directional relationships
- Calendar marked as Date table
- Business logic centralized in measures
- No calculations embedded in visuals

---

## Semantic Layer (DAX)
All KPIs are defined in reusable measures to ensure a **single source of truth**.

**Core Metrics**
- Total Amount
- Total Profit
- Profit %
- Shipments Count
- Amount per Box

**Time Intelligence**
- Year-over-Year comparison
- Last Year Amount
- Rolling and variance analysis

This mirrors **enterprise BI semantic modeling practices**.

---

## Reporting Capabilities
- **Executive Dashboard** – KPI overview and trends
- **Year-over-Year Analysis** – Performance comparison
- **Product & Location Profitability**
- **Salesperson Performance**
- **Shipment Volume Analysis**
- **Operational Metrics (Amount per Box)**

All reports support **drill-down, slicing, and cross-filtering**.

---

## Governance & Performance
- Sample data only
- Optimized DAX using VAR patterns
- Star schema for performance and scalability
- Modular and extensible design

---

## Technology Stack
Power BI • DAX • Power Query (M) • Dimensional Modeling • GitHub

---

## Portfolio Context
This project demonstrates **enterprise BI architecture, semantic modeling discipline, and executive-ready analytics**, aligned with standards used in **large-scale analytics and financial institutions**.

---

## Author
**Harika Murari**  
Data Engineer | BI Engineer  
Power BI • DAX • SQL
