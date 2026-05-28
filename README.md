# NOVAPAY DASHBOARD
The goal is to recommend optimizations that improve transaction success rates, enhance user experience, balance regional growth, and mitigate operational risks.

# Problem Statement
Analyze the provided transaction dataset (10,000 records from January 1 to June 28, 2024) to evaluate key performance indicators (KPIs), identify trends in volume and value, assess performance by channel, region, and transaction type, quantify success/failure rates, and deliver actionable insights.
The goal is to recommend optimizations that improve transaction success rates, enhance user experience, balance regional growth, and mitigate operational risks. Present findings in a clear, professional format suitable for Product, Operations, and Risk stakeholders.

# Objectives
•Calculate core KPIs (total volume, success rates, average transaction value).
•Identify temporal trends and patterns.
•Compare performance across transaction types, channels, and regions.
•Highlight failure hotspots and improvement opportunities.
•Provide 3–5 prioritized business recommendations.

Deliverables Expected Executive summary, detailed EDA, visualizations with clear interpretations, and prioritized recommendations.

## VISUALIZATION
![](novapaydashboard.jpg) 

# Insights
Key KPIs
- Transaction Volume: 2 Billion
- Transaction Value: 10,000
- Success Rate: 92.06%
- Failure Rate: 7.94%

1. Transaction Volume Trends
January recorded the highest transaction volume (441.7M), which is 15.98% higher than June (380.8M), the lowest month.

January contributed 17.69% of total transaction volume, making it the peak period.
There is a negative relationship between total transaction volume and successful transactions, suggesting that higher traffic may impact performance.

The largest gap between total and successful transactions occurred in January, indicating increased failed transactions during peak activity.

2. Success Rate Analysis
The highest success rate (92.64%) was recorded in April, while the lowest (91.54%) occurred in May.

Success rates remained relatively stable, ranging between 91.54% and 92.64% across the six months.

Overall, 92.03% of all transactions were successful, which reflects strong system performance but still leaves room for improvement.

3. Failure Rate Analysis
May recorded the highest failure rate (8.46%), while April had the lowest (7.36%).
Failure rates ranged from 7.36% to 8.46%, showing slight fluctuations but consistent operational challenges during certain periods.

4. Transaction Outcome Breakdown
Successful transactions (2.30B) significantly exceeded failed transactions (198.9M).
Failed transactions still represent a notable volume, especially during high-traffic periods.

5. Regional Performance
Port Harcourt recorded the highest transaction volume (639.2M), contributing 25.61% of total volume.
This was followed by Abuja, Lagos, and Kano.
Transaction activity appears concentrated in key urban locations.

6. Channel Performance
Web channel led with 837.1M transactions (33.54%).
USSD (831.4M) and Mobile App (827.6M) followed closely.
Transaction distribution across channels is relatively balanced, with a slight preference for web.


# Recommendations
1. Improve System Performance During Peak Periods
January shows high volume but also a larger gap in successful transactions.
2. Increase server capacity, load balancing, and monitoring during peak months.
Example: Auto-scale infrastructure during high-demand periods to reduce failures.

