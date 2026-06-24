---


#  E‑commerce Marketing Performance Analysis

##  Project Overview

This project analyzes customer acquisition, marketing channel performance, and revenue generation for an e‑commerce platform (Olist seller funnel).  
Using **SQL** for data cleaning and **Python** for analysis and visualization, the study identifies which channels deliver the highest‑value customers, how revenue and sales volume evolve over time, and which customer segments drive orders and revenue.

---

##  Business Questions Answered

- Which marketing channels bring the highest revenue and best conversion rates?
- How does revenue and sales volume change month over month?
- How long does it take a lead to become a customer? (sales cycle length)
- Which customer groups (reseller vs manufacturer) generate more orders and higher payments?
- Which product categories (business segments) produce the most revenue?

---

##  Dataset Description

- **8,000 Marketing Qualified Leads (MQLs)** collected from June 2017 to June 2018.
- Two main tables:
  - `mql_leads` – acquisition channel, first contact date, landing page.
  - `mql_deals` – closed deals, won date, monthly revenue, business segment, lead type, business type.
- Source: Olist (Brazilian e‑commerce platform).

---

## Tools & Technologies

- **SQL** (PostgreSQL) – data cleaning, joining, aggregation  
- **Python** – pandas, matplotlib, seaborn, plotly  
- **Jupyter Notebook** – interactive analysis

---

##  Data Processing Steps

- Connected to PostgreSQL using SQLAlchemy.
- Checked for missing values, duplicates, structural errors.
- Created cleaned tables: `clean_mql_leads` and `clean_mql_deals`.
- Standardized date formats; filled missing `origin` with `'unknown'`.
- Merged datasets for funnel analysis.

---

## Funnel & Marketing Analysis Performed

1. **Channel effectiveness** – revenue per channel, conversion rate, revenue heatmap over time.
2. **Sales performance over time** – monthly revenue and sales count trends.
3. **Customer segmentation** – orders and revenue by business type and business segment.

---

##  Key Findings

###  Marketing Channels
- **Organic Search** is the most effective channel:  
  → **51,426 k revenue** | conversion rate **11.8%**  
- **Paid Search** ranks second:  
  → **9,169 k revenue** | conversion rate **12.3%**  
- **Email** and **Social** show much lower conversion (~3–5.6%).

###  Time Trends
- Revenue **grew sharply in October 2018** (50,874 k), but **sales volume declined over the last 7 months** – a potential warning sign.
- The sales cycle remains **long** – leads take considerable time to convert (process inefficiency).

###  Customer Segments
- **Resellers** generate the highest number of orders (587) but lower revenue per order.  
- **Manufacturers** generate fewer orders (242) but **much higher total revenue** (50.8 M vs 10.3 M) – higher‑value customers.
- Top revenue‑generating business segments:  
  `construction_tools_house_garden`, `phone_mobile`, `home_decor`, `pet`, `health_beauty`.

---

##  Sample Visualizations

- Bar charts – revenue per channel, conversion rates  
- Line charts – monthly revenue and sales volume  
- Heatmap – channel‑by‑month revenue  
- Pie & bar charts – customer segment analysis  

All visualizations created with `matplotlib`, `seaborn`, and `plotly`.


---

## 📄 License

This project is for educational and portfolio purposes. Feel free to use and adapt with attribution.

---

## 👤 Author

Ashot Movsisyan 
(https://github.com/ashot0231/) 

---
