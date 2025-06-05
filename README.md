# Kaohom Jewelry Business Analysis
Table of Contents:
- [Project Background](#Project-Background)
- [Project/Business Workflow](#Project/Business-Workflow)
- [Insight Summary](#Insight-Summary)
- [Insights Deep-Dive and Specific Recommendations](#Insights-Deep-Dive-and-Specific-Recommendations)
  - [Demographic Insights](#Demographic-Insights)
  - [Spending Trends and Expense Metrics](#Spending-Trends-and-Expense-Metrics)
  - [CLV and CAC Ratio](#CLV-and-CAC-Ratio)
  - [Influencer ROI & Efficiency](#Influencer-RO--Efficiency)
  - [Key Product Performance](#Key-Product-Performance)
  - [Sales Trend and Growth Rate](#Sales-Trend-and-Growth-Rate)
  - [Net Earnings](#Net-Earnings)
  - [Email Funnel Performance: Drop-Off & Conversion Analysis](#Email-Funnel-Performance-Drop-Off--Conversion-Analysis)
- [Strategic Direction](#Strategic-Direction)
## Project Background
Kaohom Jewelry is a mock business dataset I created for a learning project, simulating operations from January 2022 to December 2024. The business specializes in jewelry accessories, including silver, pearl, gold, and diamond pieces. The dataset is designed to reflect real-world complexity, covering multiple levels of analysis: transactional, customer, marketing performance, manpower, funnel performance, business efficiency and business outcomes.

## Project/Business Workflow
While working on this project, I imagined the end-to-end business workflow as if I were responsible for driving outcomes in a real role. This led me to design a flowchart that outlines the strategic process, from insight generation to team action, KPI tracking, and a feedback loop. Although this is a mock business and the feedback loop isn’t implemented, the structure reflects how a real-world system could function effectively.
<p align="center">
<img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/87a7631137234b0edd556e6351de4d0f9617ddc7/viz%20%26%20screenshot/IMG_5958.PNG" alt="Project Workflow" width=1000>
</p>
Project Workflow: Blurred on purpose. No secrets, just don’t want to spoil the fun😉.


PS. I'm not planning to do RFM or any customer segmentation at this stage, as this is just a learning project and I prefer to avoid that level of complexity for now.

## Insight Summary
This analysis is based on 35,000 sales records from 2022 to 2024, with total revenue consistently reaching approximately $10 million. 76% of sales were generated through physical branches, while 24% came from the online website. The average Customer Lifetime Value(CLV) across all channels is approximately $600, with a mean Customer Acquisition Cost (CAC) ratio of 15. These figures indicate that the business is both healthy and profitable. Strong customer retention plays a key role, with 72% of all-time customers being repeat buyers and only 28% making a one-time purchase. This high retention rate suggests effective customer engagement and long-term value creation.

## Insights Deep-Dive and Specific Recommendations
### Demographic Insights (Customer Understanding and Branch Contribution and Comparative Metrics)
- Monthly customer volume stable at around 900. Customer retention is a major strength, with 72% of customers making repeat purchases and only 28% being one-time buyers.
- Repeat buyer rates remain stable at 50–55% month-on-month, despite strong long-term retention (72% of all-time customers). This indicates that monthly revenue growth still relies heavily on acquiring new customers. At the same time, the upward trend in repeat buyer share suggests our CRM is performing well. To move beyond assumption, we should A/B test CRM impact by comparing retention between customers with and without CRM exposure. If the data shows causation, not just correlation, we’ll have clear justification to scale CRM investment. Otherwise, resources can be reallocated to higher-yield acquisition channels.
<p align="center">
<img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/e719922d9ada31ae1d9f13ee392d8f2203157b78/viz%20%26%20screenshot/Monthly_Customer_Growth.png" alt="Customer Growth" width= 350>
<img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/e16c074dfcb685ba1a54de668f0f656932d8daa9/viz%20%26%20screenshot/Screenshot%20(3).png" alt="All-time Customer Share" width=350>
</p>

---
- Customer data shows that 60% of our buyers are Lao citizens, with 20% from Thailand and 20% from other nationalities. Gender distribution is nearly balanced at 50/50. This insight shows strong local support, showing a point of pride and proof of product-market fit in our home country. At the same time, with 40% of customers being non-Lao, we see clear potential for international growth. This diversity signals that our product quality and pricing are competitive beyond local borders. The balanced gender ratio also suggests we should maintain inclusive marketing strategies, avoiding assumptions that jewelry appeals primarily to women. This helps us avoid gender bias and better serve a wider audience.
<p align="center">
<img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/999ff4b4c7d34fb68980290a92105fc18b579be6/viz%20%26%20screenshot/Customer_Count_by_Nationality.png" alt="Customer Nationality" width=350>
<img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/4342a47bb98781b76c086fe65cfd2526ab7ac4e8/viz%20%26%20screenshot/Customer_Count_by_Gender.png" alt="Customer Gender" width=350>
</p>

---
- Our business shows solid profitability, with an average customer lifetime value (CLV) of $600. The 36–45 age group not only represents the largest customer segment but also delivers the highest CLV. This makes them a clear priority for both marketing and retention strategies. By the way, the gap between age segments isn’t significantly wide based on the current (mocked) data. For now, an all-age marketing approach remains practical. However, in a real business context, further A/B testing and segmentation analysis would be essential to validate whether focused targeting drives materially better ROI.


<p align="center">
<img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/e719922d9ada31ae1d9f13ee392d8f2203157b78/viz%20%26%20screenshot/CLV_and_Count_by_Age_Group.png" alt="CLV age" width=400>
<img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/e719922d9ada31ae1d9f13ee392d8f2203157b78/viz%20%26%20screenshot/Monthly_Average_CLV.png" alt="Average CLV Monthly" width=350>
<p/>

---
- Customer share by branch shows the highest contribution from the online website at 23.5%, followed by the Luang Prabang shop at 21.7% and the Vientiane shop at 20.3%, with CLV performance showing minimal variance across all branches. However, total sales are still dominated by physical branches at 76.5%, with online contributing 23.5%. This indicates clear potential to grow the online channel further while also strengthening CRM efforts for offline customers.
<p align="center">
<img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/317ffc25ba192991934045ed121bf3d767c25ed0/viz%20%26%20screenshot/Customer_Count_by_Branch.png" alt="Customer Count by Branch" width="350">
<img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/e719922d9ada31ae1d9f13ee392d8f2203157b78/viz%20%26%20screenshot/Average_CLV_by_Branch.png" alt="CLV all Branches" width=350>
<img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/219ae7d3045f953ca03b961c363f9b90589600be/viz%20%26%20screenshot/Monthly_Metrics_and_Growth_Rates_by_Branch_and_Year.png" width=700>
<p/>
  
---
### Spending Trends and Expense Metrics
- Our manpower-related fixed cost stands at $31,700, with 36% allocated to customer acquisition and 64% directed toward retention and other operational processes. This cost structure reflects a heavier focus on sustaining operations and serving existing customers.
- Monthly marketing spend averages $8,400, with Facebook Ads being the primary channel. While the highest overall expense remains Cost of Goods Sold (COGS), it's excluded from metric-based analysis, as it consistently yields a 50% profit margin by design.
<p align="center">
<img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/cc2985b22f630455b8facda431029124637613b6/viz%20%26%20screenshot/Marketing_Spend_by_Channel.png" width=350>
<img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/cc2985b22f630455b8facda431029124637613b6/viz%20%26%20screenshot/Screenshot%20(263).png" width=560>
</p>

### Acquisition Channel Efficiency
- Analysis of first-touch data shows that walk-in traffic is the top acquisition channel. This is partly due to attribution gaps that many customers see online ads but head straight to the physical store without triggering UTM tracking. This highlights the critical role of offline presence in building trust, especially in a high-value category like jewelry. As we scale online, offline cannot be neglected. This also reinforces the logic behind our current cost structure, which prioritizes support for physical channels.
- If we exclude offline channels, which are hard to track. Influencer marketing delivers the highest acquisition performance, with 8% more new customers compared to Facebook Ads, while costing only half as much. However, it comes with an 8% lower CLV as a trade-off. Even so, this clearly suggests we should invest more in influencer marketing and reduce spending on Facebook Ads to improve efficiency.
<p align="center">
<img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/cc2985b22f630455b8facda431029124637613b6/viz%20%26%20screenshot/Yearly_Acquisition_Channel_Performance%20(1).png" width=350>
</p>
  
### Influencer ROI & Efficiency
### CLV and CAC Ratio
### Key Product Performance
### Sales Trend and Growth Rate
- Revenue held steady at around $10 million per month, with a sharp 300% spike in December 2024. Monthly orders averaged about 1,000, also seeing a similar spike. The sudden jump was mainly due to my data mock-up not being as realistic as it should’ve been. It's a good reminder of how important accurate test data is for reliable analysis.
- March 2022 recorded a 42% growth rate, driven by a 15% reduction in marketing spend and a 33.8% increase in customer numbers. Also in December 2022 reached 22%, mainly driven by returning customers. These insights can be applied to improve the effectiveness of future campaigns.
<p align="center">
  <img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/219ae7d3045f953ca03b961c363f9b90589600be/viz%20%26%20screenshot/Monthly_Metrics_and_Growth_Rates_by_Year.png" width=1550>
  <img src="https://github.com/EmSomsanook/Kaohom-Jewelry-Business-Analysis/blob/e719922d9ada31ae1d9f13ee392d8f2203157b78/viz%20%26%20screenshot/Screenshot%20(264).png" width=1150>
  <p/>
    
---
- 
### Net Earnings
### Email Funnel Performance: Drop-Off & Conversion Analysis

## Strategic Direction


