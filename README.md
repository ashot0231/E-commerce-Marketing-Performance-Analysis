
# E-commerce Marketing Performance & Revenue Analysis

## Project Overview

Analysis of marketing channel performance, customer acquisition efficiency, and revenue generation for an e-commerce platform using the Olist dataset (~8,000 MQLs).

The project evaluates how different marketing channels contribute to revenue, how effectively leads convert into customers, and which customer segments generate the highest business value.

---

## Business Objectives

* Evaluate marketing channel performance by revenue and volume
* Measure conversion efficiency across acquisition sources
* Analyze revenue and sales trends over time
* Identify high-value customer segments
* Assess performance of different business categories
* Detect inefficiencies in customer acquisition and conversion

---

## Dataset

* ~8,000 Marketing Qualified Leads (MQLs)
* Period: June 2017 – June 2018
* Source: Olist e-commerce platform

### Tables

* mql_leads: acquisition data (channel, landing page, first contact date)
* mql_deals: closed deals (revenue, segment, customer type, deal date)

---

## Methodology

* SQL-based data extraction and transformation (PostgreSQL)
* Data cleaning and standardization
* Dataset integration (lead-to-deal matching)
* Exploratory analysis in Python
* Visualization of key business metrics

---

## Key Findings

### Marketing Channels

* Organic Search is the primary driver of revenue and lead volume
* Paid Search is the second strongest acquisition channel
* Other channels show significantly lower efficiency

---

### Revenue Trends

* Revenue shows recent growth while sales volume declines
* Growth is driven by higher-value transactions rather than volume

---

### Conversion Efficiency

* Conversion rates vary significantly across channels
* Overall funnel efficiency is inconsistent across acquisition sources

---

### Customer Segments

* Manufacturers generate fewer deals but higher revenue per customer
* Resellers generate higher volume but lower value per deal

---

### Business Segments

Top-performing:

* construction_tools_house_garden
* phone_mobile
* home_decor
* pet
* health_beauty

Low-performing:

* watches
* food_drink
* perfume
* party
* bed_bath_table

---

## Business Impact

* Identified Organic Search as the highest-value acquisition channel
* Highlighted inefficiencies in conversion performance
* Revealed dependency on high-value customer segments
* Provided basis for marketing budget optimization
* Identified priority business categories for growth focus

---

## Key Takeaway

Revenue is primarily driven by Organic Search and high-value manufacturer customers, while overall efficiency is constrained by declining volume and inconsistent conversion performance.

---

## Tools

* SQL (PostgreSQL)
* Python (Pandas, Matplotlib, Seaborn, Plotly)
* Jupyter Notebook

---

## Author

Ashot Movsisyan
GitHub: [https://github.com/ashot0231/](https://github.com/ashot0231/)


