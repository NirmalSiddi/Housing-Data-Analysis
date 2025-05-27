# Housing-Data-Analysis
Housing Data Analysis (GCP  Google Big Query)

![image](https://github.com/user-attachments/assets/9fe26b88-641e-4226-a540-5e5982435a40)


#   Housing Market Analysis Dashboard

##   Overview

   This Power BI project represents my comprehensive analysis of housing market data, providing a dynamic view of sales patterns, pricing trends, and regional disparities. I utilized Google Cloud Platform (GCP) and BigQuery to extract and process the data before bringing it into Power BI for visualization and in-depth analysis. Through this project, I aimed to demonstrate my ability to connect to cloud-based data, apply advanced DAX calculations, and craft actionable insights for stakeholders in the real estate industry.

##   Key Features

   The dashboard is packed with insightful metrics, all driven by my custom-built DAX formulas:

* **Age:** I calculated the age of each property to understand how age influences pricing and sales trends, which involved subtracting the build year from the sale date.
* **Offer Price:** To get a clearer picture of negotiation dynamics, I derived the original offer price from the final purchase price and the percentage change between offer and purchase.
* **Average Price SQM:** I computed the average price per square meter to enable standardized price comparisons across different property sizes.
* **Last 12 Month Sales:** I tracked the total sales value over the past 12 months to identify short-term market fluctuations and momentum.
* **Median Sales Price Change:** I analyzed the year-over-year change in median sales price to gauge market appreciation and identify potential bubbles or downturns.
* **Offer to SQM Ratio:** I created this metric to assess the relative value of offers in relation to property size, which is crucial for evaluating investment opportunities.
* **Sales by Region:** I broke down total sales by region to highlight geographical variations in market activity and pricing.
* **Total YTD Sales:** I monitored the cumulative sales year-to-date to track progress toward annual targets and identify seasonal trends.
* **Units Sold in Latest Year & Quarter:** I counted the number of units sold in the most recent periods to provide the latest snapshot of market activity.
* **YOY\_Sales\_Growth:** I calculated the year-over-year sales growth to measure the market's overall health and growth trajectory.

##   Technical Skills Demonstrated

   This project allowed me to showcase a range of technical skills:

* **GCP and BigQuery Expertise:** I gained hands-on experience connecting to and querying data within the Google Cloud Platform ecosystem using BigQuery, demonstrating my ability to work with cloud-based data warehouses.
* **Power BI Proficiency:** I utilized Power BI to its fullest extent for data loading, transformation, modeling, and visualization.
* **Advanced DAX Skills:** I developed complex DAX formulas, including:
    * Time intelligence functions to analyze sales trends over time.
    * Statistical functions to calculate averages, medians, and growth rates.
    * Filtering and context manipulation to analyze data at various levels of granularity.
* **Data Visualization and Storytelling:** I designed the dashboard to effectively communicate key findings and tell a compelling story about the housing market.
* **Performance Optimization:** I focused on writing efficient DAX to ensure the dashboard remains responsive and performs well with large datasets.

##   Key Insights and Actionable Suggestions

   My analysis revealed several key insights that could drive strategic decisions:

* **Regional Disparities and Targeted Strategies:** The significant differences in sales performance across regions, as seen in the "Sales by Region" visualization, suggest the need for targeted strategies. I recommend a deeper investigation into the underlying economic factors to inform tailored marketing campaigns or identify optimal areas for investment.
* **Pricing Optimization Based on Property Type and Location:** The variations in "Average Price SQM by region" and "Offer to SQM Ratio by sales\_type" indicate that certain property types or regions command premium prices. This insight can guide developers to focus on high-value properties in specific locations to maximize profitability.
* **Negotiation Strategy Refinement:** The "Offer Price Vs Purchase Price" scatter plot highlights the relationship between initial offers and final purchase prices. Analyzing this data further could enable sellers to set more competitive prices and empower buyers to negotiate more effectively, leading to quicker transactions and greater market efficiency.
* **Sales Trend Adaptation:** The "YOY Sales Growth by Sales Type" analysis pinpoints which sales types are growing or declining. Real estate agents and investors can leverage this information to adapt their strategies, focusing on expanding segments and mitigating risks in declining ones.

   To further enhance the analysis and provide even greater value, I propose the following:

* **Predictive Price Modeling:** Developing a predictive model using machine learning to forecast future property prices based on historical data and economic indicators would provide a powerful tool for investors and buyers alike.
* **Buyer Segmentation for Targeted Marketing:** Conducting a detailed segmentation analysis to identify distinct buyer personas would enable more effective targeting of marketing efforts, increasing conversion rates and reducing marketing costs.
* **Risk Assessment for Investment Decisions:** Creating a risk assessment model to evaluate the potential risks and returns associated with different real estate investments would help investors make more informed decisions and minimize potential losses.
* **Real-time Data Integration for Dynamic Insights:** Integrating real-time data feeds would allow for a more dynamic and up-to-date view of the market, enabling stakeholders to react quickly to changing conditions and capitalize on emerging opportunities.

## Link

https://app.powerbi.com/links/ULREzWlgMn?ctid=79a3fac8-adad-4f54-b6c6-5896bad3d102&pbi_source=linkShare

##   Conclusion

   This Housing Market Analysis project demonstrates my ability to independently manage a complex data analysis workflow, from data extraction and processing to insightful visualization and strategic recommendations.
