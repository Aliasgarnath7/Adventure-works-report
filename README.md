# AdventureWorks Power BI Dashboard

A Microsoft Power BI business intelligence project built for **AdventureWorks**, a fictional global cycling equipment and accessories company.

This dashboard analyzes sales, profit, orders, returns, customers, and regional performance across **Australia, Canada, France, Germany, the United Kingdom, and the United States**. The dataset covers the period from **01/01/2020 to 30/06/2022** and includes customer demographics such as date of birth, annual income, education level, number of children, occupation, and homeowner status.

<img alt="AdventureWorks Executive Dashboard" src="images/screenshots/exec_dashboard.gif">

## Project Overview

This is one of my best Power BI projects and was built to demonstrate end-to-end business intelligence skills, including data cleaning, data modeling, DAX, Power Query, and interactive dashboard design.

The goal of the report is to help business stakeholders quickly understand:

* how the company is performing overall
* which products and categories drive revenue and profit
* where customers are located
* which customer segments are most valuable
* how returns affect business performance

## Features

* KPI tracking for **Revenue**, **Profit**, **Orders**, **Return Rate**, **Customers**, and **Revenue per Customer**
* Interactive views for **executive summary**, **geography**, **product details**, and **customer analysis**
* Drill-through style analysis for individual products
* Regional comparison across countries and continents
* Product-level performance against targets
* What-if analysis using **price adjustment** to estimate adjusted profit
* Customer segmentation by income level and occupation
* Custom tooltips and report summary insights

## Dashboard Pages

### 1. Executive Summary View

This page provides a high-level overview of the business with:

* total revenue, profit, orders, and return rate
* revenue trend over time
* orders by category
* top 10 products by orders, revenue, and return rate
* most ordered and most returned product type

### 2. Map View

This page shows the geographic distribution of orders across all supported countries and regions.

### 3. Product Detail View

This page focuses on one selected product and shows:

* monthly orders, revenue, and profit against targets
* price adjustment what-if analysis
* total profit versus adjusted profit
* a detailed report summary for the selected product

### 4. Customer Detail View

This page analyzes the customer base with:

* total customers and revenue per customer
* customer trends over time
* top customers by revenue
* orders by income level
* orders by occupation
* customer rankings and summary highlights

## Tools and Skills Used

* **Power BI Desktop**
* **Power Query** for data transformation
* **DAX** for calculated columns and measures
* **Data modeling** with relationships between tables
* **Interactive visual design**
* **What-if parameters**
* **Custom report layout and storytelling**

## Data Preparation

This project involved:

* connecting and transforming raw data
* cleaning and shaping tables in Power Query
* building a relational data model
* creating calculated columns and measures with DAX
* creating a rolling calendar using Power Query M code
* designing interactive report pages

## Key Insights

* Between **01/01/2020 and 30/06/2022**, AdventureWorks generated about **$24.9M in revenue** and **$10.5M in profit**.
* Revenue shows a visible dip in the middle of 2020 before recovering and rising steadily into 2022.
* **Tires and tubes** are the most ordered product type.
* **Shorts** are the most returned product type.
* **Accessories** and **clothing** are among the strongest categories for revenue and profit.
* The **United States** is the largest market by orders and revenue.
* **Australia** shows the highest revenue per customer.
* Customer growth increased sharply from around August 2021 onward.


## Repository Structure

````text
Adventure-works-report/
├── Data/
├── Screenshots/
├── AdventureWorks Report_FINAL.pbix
└── README.md
````

## Getting Started

1. Clone this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Refresh the dataset if needed.
4. Explore the report pages and interact with the slicers, filters, and drill-through views.

## Dataset Source

The dataset was supplied with the [Maven Analytics Power BI Desktop course](https://mavenanalytics.io/course/microsoft-power-bi-desktop) and is derived from the [AdventureWorks sample databases](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure) available from Microsoft.

## About This Project

This dashboard was created to showcase practical business intelligence skills and present a complete analysis workflow, from raw data to executive-level reporting.

If you are reviewing my portfolio, this project highlights my ability to:

* turn raw business data into clear insights
* build clean and organized data models
* create meaningful DAX measures
* design professional dashboards
* communicate findings through visuals and written insights

---

**Built with Power BI Desktop**
