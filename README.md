# Data-Analytics-Project
Interactive Sales &amp; Revenue Analysis Dashboard built using Power BI, Excel, Power Query, and DAX. Features real-time KPI tracking, revenue trends, top-performing products, regional analysis, and dynamic slicers to transform sales data into meaningful business insights and support data-driven decision-making.
Customer Segmentation & Behaviour Analytics
Project Overview
This project analyses customer demographics and purchasing behaviour to identify meaningful customer segments. An interactive Power BI dashboard presents key customer metrics, customer distributions, income and spending patterns, and segment-level summaries to support data-driven marketing decisions.
This project was completed as part of the Thiranex Customer Segmentation Project assignment.
Objectives
- Analyse customer demographics and purchasing behaviour.
- Segment customers using the available customer data.
- Compare annual income with spending score.
- Visualise customer groups and their characteristics.
- Present actionable business recommendations through a Power BI dashboard.
Tools & Technologies
- Microsoft Power BI — interactive dashboard and visual analytics
- DAX — KPI measures and calculations
- Power Query — data preparation, where applicable
- Customer dataset — customer ID, gender, age, annual income, spending score, and cluster assignment
The dashboard uses a dataset of 200 customers. Update this section if your final dataset or workflow differs.

Dashboard Features
KPI Cards
- Total Customers: 200
- Average Age: 38.85 years
- Average Annual Income: 60.56 (k$)
- Average Spending Score: 50.20 (scale of 1–100)
Filters
- Gender — filter customers by gender.
- Cluster — view customers assigned to a particular cluster.
- Age — narrow the analysis using an age range.
Visualisations
- Gender Distribution: compares the number of female and male customers.
- Age Distribution: shows how customer ages are distributed.
- Customer Segment Distribution: shows the number and percentage of customers in each cluster.
- Annual Income vs Spending Score: compares customer income and spending behaviour.
- Customer Segment Summary: compares average age, average income, average spending score, and customer count by cluster.
Key Findings
Based on the current dashboard:
- The dataset contains 200 customers.
- Average customer age is 38.85 years.
- Average annual income is 60.56 k$.
- Average spending score is 50.20.
- The dashboard separates customers into five clusters.
- The clusters show different combinations of annual income and spending score, which can help identify groups for different marketing strategies.
Segment Interpretation
Use the cluster summary to interpret the groups:
- High income, high spending: potential high-value customers for loyalty programmes and personalised rewards.
- High income, low spending: potential audience for relevant offers and engagement campaigns.
- Low income, high spending: customers who may respond to suitable targeted offers.
- Low income, low spending: consider budget-friendly offers and re-engagement campaigns.
- Moderate income or spending: use the measured cluster characteristics to design appropriate promotions.
Cluster numbers are identifiers, not rankings. Confirm each cluster's actual averages in the dashboard before assigning a business label. The segment descriptions above are general interpretations, not proof of customer intent.

Business Recommendations
- Offer loyalty rewards to customers in the high-income, high-spending segment.
- Test relevant promotions for high-income customers with lower spending scores.
- Consider personalised, affordable offers for lower-income customers who spend more.
- Use re-engagement campaigns for customers with lower spending scores.
- Monitor segment performance over time before deciding which strategy is most effective.
How to Use the Dashboard
1. Open the Power BI report (.pbix) in Power BI Desktop.
2. Use the Gender, Cluster, and Age filters on the left to narrow the analysis.
3. Review the KPI cards to see the overall metrics or metrics for the selected filters.
4. Explore the charts to compare demographics, segment sizes, and income/spending patterns.
5. Use the summary table to compare the average characteristics of each cluster.
Suggested Repository Structure
Customer-Segmentation-Analysis/
├── README.md
├── Customer_Segmentation.pbix
├── dataset/
│   └── Mall_Customers.csv
└── images/
    └── customer-segmentation-dashboard.png
Rename files and folders to match the files you actually upload. Include the dataset only if you are permitted to share it, and add your final dashboard screenshot to the images/ folder if desired.
Project Outcome
The final Power BI dashboard brings customer metrics, filters, charts, and cluster summaries into one view. It demonstrates how customer data can be organised into segments and translated into practical marketing recommendations.
Future Improvements
- Evaluate the appropriate number of clusters using methods such as the elbow method or silhouette score if using K-Means.
- Add more customer behaviour data when available.
- Track campaign outcomes to test whether recommendations improve engagement.
- Improve accessibility with clear labels, consistent formatting, and helpful tooltips.
Author
Mahadeb Kundu

