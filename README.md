📊 E-commerce Marketing Funnel & Revenue Analysis (Olist Dataset)
📌 Project Overview

This project analyzes the performance of marketing channels, customer acquisition efficiency, and revenue generation for an e-commerce platform using the Olist Marketing Funnel dataset (~8,000 MQLs).

The main goal is to understand how leads move through the funnel, which channels generate the most valuable customers, and what drives revenue growth across time and customer segments.

The analysis combines SQL (PostgreSQL) for data extraction and transformation with Python (Pandas, Matplotlib, Seaborn, Plotly) for exploratory data analysis and visualization.

🎯 Business Objectives

The project focuses on answering the following questions:

Which marketing channels are the most effective in terms of revenue and conversions?
How does channel performance differ in conversion efficiency?
How does revenue and sales volume evolve over time?
What is the structure and efficiency of the sales funnel?
How long does it take for a lead to convert into a customer?
Which customer types and business segments generate the most value?
Where are the main inefficiencies in the funnel?
🗄️ Dataset Description
~8,000 Marketing Qualified Leads (MQLs)
Time period: June 2017 – June 2018
Source: Olist e-commerce platform (Brazil)
Main Tables
mql_leads – lead acquisition data (marketing channel, landing page, first contact date)
mql_deals – closed deals (revenue, business segment, deal date, customer type)
⚙️ Data Preparation & Cleaning
Established connection to PostgreSQL database via SQLAlchemy
Handled missing values (e.g., unknown marketing channels)
Standardized date formats for time-series analysis
Checked and removed duplicates
Validated data structure and consistency
Created cleaned analytical tables for modeling:
clean_mql_leads
clean_mql_deals
Joined datasets to construct full funnel view (lead → deal)
📈 Analytical Approach
1. Marketing Channel Analysis
Revenue contribution by channel
Conversion rate comparison (lead → deal)
Channel efficiency evaluation
2. Funnel Analysis
Lead-to-customer conversion behavior
Funnel performance and bottlenecks
Time between acquisition and conversion
3. Revenue & Time Trends
Monthly revenue evolution
Sales volume trends over time
Identification of growth and decline patterns
4. Customer Segmentation
Comparison of resellers vs manufacturers
Revenue per customer type
Volume vs value trade-off analysis
5. Business Segment Analysis
Revenue distribution across industries
Identification of top-performing and underperforming segments
🔍 Key Insights
📣 Marketing Channels
Organic Search is the dominant acquisition channel
Generates the highest revenue
Provides the largest volume of qualified leads
Paid Search is the second strongest channel
Strong revenue contribution
Slightly lower efficiency compared to organic traffic

👉 Conclusion: Organic acquisition is the primary driver of business growth.

📉 Funnel Performance
Sales cycle remains consistently long across the observed period
Conversion process shows inefficiencies between lead and deal stages
Revenue growth is not fully aligned with sales volume trends

👉 Conclusion: The funnel has bottlenecks that slow down conversion efficiency.

📊 Revenue Trends
Revenue shows short-term growth in recent months
However, overall sales volume is declining

👉 Conclusion: Growth is driven by fewer but higher-value deals.

👥 Customer Segmentation
Manufacturers
Lower number of deals
Significantly higher revenue contribution
Resellers
Higher deal volume
Lower revenue per deal

👉 Conclusion: Business is driven by high-value B2B customers rather than volume.

🧩 Business Segments

Top-performing segments:

construction_tools_house_garden
phone_mobile
home_decor
pet
health_beauty

Lower-performing segments:

watches
food_drink
perfume
party
bed_bath_table
📊 Visualizations

The analysis includes:

Revenue comparison across marketing channels
Conversion rate analysis
Monthly revenue trends
Sales volume trends
Funnel efficiency visualizations
Customer segmentation breakdown
💡 Business Impact

This analysis provides actionable insights for:

Optimizing marketing budget allocation across channels
Improving funnel conversion efficiency
Identifying high-value customer segments
Supporting revenue growth strategy
Prioritizing high-performing business categories
🚀 Key Takeaway

The business is primarily driven by:

Organic Search (main acquisition channel)
Manufacturers (highest revenue segment)

However, performance limitations exist due to:

Long sales cycles
Declining deal volume
Funnel inefficiencies
📄 License

This project is intended for educational and portfolio purposes. Feel free to use with attribution.

👤 Author

Ashot Movsisyan
GitHub: https://github.com/ashot0231/
