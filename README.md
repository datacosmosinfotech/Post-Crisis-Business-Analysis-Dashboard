# Startup Crisis Impact & Revenue Resilience Dashboard

## 📌Overview
This dashboard analyzes the impact of a crisis beginning in June 2025 and evaluates revenue resilience across customers and cities.
It measures revenue decline, churn, retention, recovery rate, and recoverable revenue opportunity to assess business stability and recovery potential.

## Preview
![Business Crisis Analysis Dashboard](https://github.com/datacosmosinfotech/Post-Crisis-Business-Analysis-Dashboard/raw/main/Business%20Crisis%20Analysis%20Dashboard%20SS.png)


## 🎯 Objectives

●Quantify revenue drop after crisis

●Measure customer churn and retention

●Compare pre vs post crisis customer base

●Identify recoverable revenue opportunity

●Analyze city level revenue impact

●Evaluate per customer revenue importance

## 🧩 Executive KPIs

Revenue Drop %
70.92%

Customer Recovery Rate
78.98%

Customer Retention Rate (Post-Crisis)
36.82%

Post Crisis Churn Rate
63.18%

Total Customers
108K

Pre-Crisis Active Customers
79K

Post-Crisis Active Customers
29K

Total Recoverable Revenue
₹2.91M

## 🔎 Key Insights

1️⃣ Revenue Impact

Revenue declined by 70.92% after the crisis.

This indicates a significant operational or demand disruption starting June 2025.

2️⃣ Customer Base Impact

Pre-crisis active customers: 79K

Post-crisis active customers: 29K

Customers lost: 50K

Churn rate: 63.18%

Retention rate: 36.82%

Nearly two thirds of the active base stopped transacting post crisis.

3️⃣ Recovery Strength

Customer recovery rate: 78.98%

Recoverable revenue opportunity: ₹2.91M

Recovery efforts show potential but have not fully stabilized revenue.

### 👤 Individual Customer Importance

Customer level contribution becomes critical during a revenue shock.

## 📊 Revenue Per Lost Customer

Lost customers = 50K

Recoverable revenue = ₹2.91M

₹2.91M ÷ 50,000 ≈ ₹58 per lost customer

## 💰 Financial Meaning

1 lost customer ≈ ₹58 impact

1,000 lost customers ≈ ₹58,000 impact

10,000 lost customers ≈ ₹5.8L impact

Even small retention improvements can generate meaningful revenue recovery.

## 📌 Why It Matters

Improving retention from 36.82% to 45% can significantly increase revenue

Segmenting high value customers improves recovery efficiency

Revenue stability depends on frequency, order value, and lifetime value

Retention is directly linked to revenue protection.

## 🏙 City Level Observations

Revenue decline observed across all major cities

Retention ranges between approximately 35%–38%

No city crosses 40% retention, confirming widespread impact

Targeted city-level reactivation campaigns are recommended

## 🛠 Technical Implementation

Tool: Power BI

Data Model: Fact Orders table + Date dimension

Crisis segmentation implemented using DAX

Measures created for churn, retention, recovery rate, and revenue drop

Interactive filters: Month and City slicers

## ▶️ How to Run the Project
Requirements

Power BI Desktop (latest version recommended)

Dataset file (Orders / Fact_Orders table with customer_id, order_id, order_timestamp, revenue fields)

Steps to Run

Download the .pbix file from the repository.

Open the file using Power BI Desktop.

If prompted, update the data source path to match your local dataset location.

Click Refresh to load the latest data.

Use slicers (Month, City) to interact with the dashboard.

Navigate between visuals to explore revenue and customer metrics.

Data Structure Expected

Fact_Orders Table

customer_id

order_id

order_timestamp

revenue

city

Date Table

Date

Month

Year

### Crisis marker (June 2025 logic applied via DAX)
Crisis Logic

Crisis date marker used:

June 1, 2025

Transactions before this date are classified as Pre-Crisis.

Transactions after this date are classified as Post-Crisis.

## Conclusion
The crisis resulted in:

70.92% revenue decline

63.18% churn rate

50K lost active customers

₹2.91M recoverable revenue opportunity

Each customer represents measurable financial value.

Retention improvement is the key lever for sustainable recovery.

## 🚀 Business Recommendations

Based on the analysis, the following strategic actions are recommended:

1️⃣ Immediate Retention Strategy

Launch targeted reactivation campaigns for the 50K lost customers

Offer personalized incentives for high-value customer segments

Use behavioral segmentation to prioritize customers with historically high frequency

Even a 5–8% retention lift can unlock substantial revenue recovery.

2️⃣ High Value Customer Protection

Identify top 20% revenue contributing customers

Implement loyalty programs and proactive engagement

Monitor drop in order frequency as an early churn signal

Retention of high value customers delivers exponential revenue protection.

3️⃣ City Level Recovery Plans

Allocate marketing budget based on city level revenue drop severity

Run localized campaigns in cities with lowest retention

Track city wise recovery trends monthly

This ensures targeted resource allocation instead of broad, inefficient spending.

4️⃣ Crisis Monitoring Framework

Build automated KPI alerts for revenue drop and churn spikes

Implement rolling 30-day churn tracking

Maintain real-time revenue resilience dashboard

This enables faster response in future operational disruptions.

## 📌 Strategic Takeaway

The crisis revealed that customer retention is the primary driver of revenue stability.

While revenue dropped sharply, recovery potential remains strong.

Sustainable growth will depend on:

Strengthening retention

Protecting high value customers

Improving lifetime value

Implementing proactive churn monitoring

Retention is not just a marketing metric — it is a revenue protection strategy.

## 👩‍💼 Author

Asma Sirkhot

Data Analyst | Business Intelligence Enthusiast

Specializing in Revenue Analytics, Churn Analysis & Interactive Dashboards


📊 Tools: Power BI | DAX | SQL | Excel

📈 Focus: Turning Data into Strategic Business Decisions
