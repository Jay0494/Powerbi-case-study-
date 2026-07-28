
# 🌾 Tan & Sons Executive Business Intelligence Solution

## 📌 Project Overview

This project demonstrates an end-to-end Business Intelligence solution developed in **Power BI** for **Tan & Sons**, a UK-based food manufacturer.

The objective was not simply to build dashboards, but to transform fragmented business data into a **single source of truth** that enables executives to make faster, evidence-based decisions.

The reporting solution was designed to answer key business questions across:

* Executive Performance
* Commercial Intelligence
* Product Intelligence
* Production Intelligence

---

## Business Challenge

The CEO identified a recurring issue across the organisation:

> *"It takes too long to get a straight answer to a simple business question."*

Reporting relied heavily on spreadsheets and manual analysis, making it difficult for leadership to obtain timely insights.

The goal of this project was to design an interactive reporting solution that would enable decision-makers to:

* Monitor business performance in real time
* Identify emerging risks
* Understand revenue drivers
* Improve operational efficiency
* Support strategic decision-making

---

# Project Workflow

## 1. Business Understanding

The project began with stakeholder workshops to understand:

* Business objectives
* Existing reporting challenges
* Key performance indicators
* Decision-making requirements

Rather than designing visuals first, the focus was on identifying the business questions executives needed answered.

Examples included:

* Is revenue growing profitably?
* Which brands generate the highest revenue?
* Which sales channels perform best?
* Are exports driving business growth?
* Which farms operate most efficiently?
* Where are operational risks emerging?

---

## 2. Data Acquisition

Power BI was connected directly to a **MySQL database**.

The project incorporated multiple business datasets covering:

* Sales
* Products
* Brands
* Customers
* Farms
* Production
* Workforce
* Geography

---

## 3. Data Quality Assessment

Before modelling the data, a quality assessment was performed to identify:

* Missing values
* Duplicate records
* Inconsistent formatting
* Invalid relationships

This ensured the reporting solution was built on reliable data.

---

## 4. Data Transformation (Power Query)

Data was transformed using Power Query.

Tasks included:

* Cleaning and standardising fields
* Merging Sales and Brand tables
* Removing unnecessary columns
* Creating business-friendly attributes
* Correcting data types
* Preparing tables for modelling

---

## 5. Data Modelling

A scalable **Star Schema** was designed to improve performance and simplify analysis.

### Fact Tables

* Sales
* Production
* Workforce

### Dimension Tables

* Date
* Product
* Brand
* Farm
* Customer
* Geography

This structure enables efficient filtering and supports reusable DAX calculations.

---

## 6. DAX Development

Business measures were developed to calculate KPIs including:

* Total Revenue
* Gross Profit
* Gross Margin %
* Revenue Growth %
* Average Revenue per Order
* Yield per Acre
* Processing Efficiency %
* Export Revenue %
* Labour Cost per Tonne

Measures were designed to reflect agreed business definitions and support consistent reporting.

---

## 7. Dashboard Development

Four interactive dashboards were developed.

### Executive Overview

Provides leadership with a high-level view of business performance.

Key KPIs include:

* Revenue
* Gross Profit
* Gross Margin
* Revenue Growth
* Yield per Acre
* Processing Efficiency

---

### Commercial Intelligence

Analyses:

* Revenue trends
* Sales channels
* Customer performance
* Export performance
* Brand contribution

Supports commercial decision-making and revenue optimisation.

---

### Product Intelligence

Provides insights into:

* Product performance
* Category contribution
* Brand performance
* Revenue distribution

Helps identify product growth opportunities.

---

### Production Intelligence

Analyses:

* Harvest volumes
* Processed output
* Processing efficiency
* Farm performance
* Production trends

Supports operational improvement initiatives.

---

# Key Business Insights

Several insights emerged during the analysis.

## Sustainable Financial Growth

Revenue reached **£32.9M** while maintaining a healthy **47% Gross Margin**, indicating profitable growth rather than revenue growth at any cost.

---

## Domestic Market Drives Performance

Although the Export channel generated significant revenue, analysis revealed that approximately **64% of total revenue originated from the domestic UK market**, demonstrating a resilient commercial model supported by multiple routes to market.

---

## Brand Concentration

The **Tiptree** brand generated more than half of total revenue.

Rather than reducing investment, the recommendation was to leverage Tiptree's customer base to increase sales across complementary brands through cross-selling and bundled promotions.

---

## Production Efficiency Opportunity

One of the most valuable insights came from production analysis.

Although:

* Harvest declined by **0.4%**

Processed output declined by:

* **1.6%**

Further investigation identified a temporary decline in processing efficiency at **Goldhanger Farm**, caused by equipment and staffing issues.

Following operational improvements, Goldhanger returned to being the Group's highest-performing farm.

Rather than simply addressing underperforming farms, the recommendation was to identify Goldhanger's best practices and replicate them across the wider operation to increase finished output without expanding farmland, labour or cultivation costs.

---

# Tools & Technologies

* Power BI Desktop
* Power Query
* DAX
* MySQL
* Data Modelling (Star Schema)
* Data Visualisation
* Business Intelligence

---

# Skills Demonstrated

* Business Requirements Gathering
* Stakeholder Analysis
* Data Cleaning
* Data Transformation
* Data Modelling
* DAX Development
* KPI Design
* Executive Dashboard Design
* Data Storytelling
* Business Analysis
* Insight Generation
* Strategic Decision Support

---

# Live Dashboard

🔗 **Power BI Report**

[https://app.powerbi.com/view?r=eyJrIjoiM2I5YmRkODQtODE1OC00MzUzLTljYzctMjkzMjliZjVlZDQzIiwidCI6ImIyMTFiMjkwLWFkNzUtNGJlNC1iZDk3LWI5Y2MxZDlmMzdlZCJ9](https://app.powerbi.com/view?r=eyJrIjoiM2I5YmRkODQtODE1OC00MzUzLTljYzctMjkzMjliZjVlZDQzIiwidCI6ImIyMTFiMjkwLWFkNzUtNGJlNC1iZDk3LWI5Y2MxZDlmMzdlZCJ9)

---

# Conclusion

This project demonstrates an end-to-end Business Intelligence workflow, from understanding business requirements and preparing data to delivering interactive dashboards and actionable insights. Rather than focusing solely on reporting historical performance, the solution was designed to help leadership identify opportunities, manage risks, and make informed strategic decisions.

---
