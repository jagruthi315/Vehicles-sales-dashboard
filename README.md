# VEHICLES SALES DASHBOARD ANALYSIS SUPPORT
# Objective
To analyze vehicle sales data to identify revenue trends, popular vehicle categories, key regions , and to provide actionable business insights using visual analytics.

## Tech Stack 
• Power BI (Data visualization & dashboard creation)
• Power Query (Data cleaning and transformation)
• Kaggle(Dataset source)
• File formats : .pbit for development and .png for dashboard previews.

## Dataset Description
The analysis uses a Vehicles dataset sourced from Kaggle. The dataset includes information related to vehicles like cars, trains , ships, trucks and buses etc that are being sold and bought across various regions.

## Key columns used in this analysis: 
•city •state • country • territory • deal size • sales •delivery time • order time

# Methodology

## Data Collection

The dataset was obtained from Kaggle and imported into Power BI for analysis.
It contains detailed records of vehicle sales, including product lines, deal sizes, order status, delivery times, customer locations, and revenue metrics.

## Data Understanding

The initial step involved exploring the dataset structure and defining key business questions, such as:

Which product lines generate the most revenue?

How do sales vary by region and time?

What deal sizes contribute most to sales volume?

Are delivery times improving over time?

Which areas show high cancellations or operational issues?

This step helped identify relevant fields and define the analytical scope.

## Data Cleaning

To ensure accuracy and consistency:

Removed irrelevant columns not required for analysis

Handled missing and null values appropriately

Removed duplicate or invalid records

Standardized categorical fields such as product line, territory, and order status

This ensured reliable and clean data for analysis.

## Feature Engineering

New measures and calculated fields were created using DAX to enhance analysis:

Total Sales

Average Order Value

Delivery Time Trends

Sales by Territory, State, and City

Deal Size Distribution

Order Status Counts

Revenue Contribution by Product Line

These transformations enabled deeper insights and more meaningful visualizations.

 ## Data Visualization

The cleaned and transformed data was visualized in Power BI using appropriate charts:

KPI Cards → Overall performance metrics

Line Charts → Sales trends & delivery time trends

Bar Charts → Sales by geography and deal size

Pie/Donut Charts → Product line contribution

Area Charts → Monthly delivery time trends

Visual types were selected based on the insight required (trend, comparison, distribution, or proportion).

## Dashboard Overview

The Vehicles Sales Dashboard provides a consolidated view of sales performance, operational efficiency, and geographic trends.

## It includes:

KPI cards showing total sales, average order value, average price, and total orders

Sales distribution by product line and deal size

Monthly and yearly sales trends

Delivery time trend analysis

Order status breakdown (shipped, cancelled, disputed, etc.)

Geographic performance by territory, country, state, and city

This dashboard enables stakeholders to monitor performance, identify growth opportunities, and address operational inefficiencies.

## Key insights uncovered:

1. Total sales of 8.07M with an average order value of ~27.08K

2. Classic Cars emerged as the highest revenue-generating product line

3. Medium-sized deals contributed the highest number of line items, highlighting volume-driven demand

4. Sales showed a clear year-end peak in November, indicating seasonal buying behavior

5. Delivery time decreased over time, reflecting improved operational efficiency

6. EMEA led at the territory level, while USA, California, and Madrid stood out geographically

7. The Ships product line recorded the highest cancellations, indicating an area for deeper investigation

8. There is no mismatch between quantity ordered and revenue generated , suggesting that vehicle pricing is well aligned wit customer demand.

# Screenshot 
## Vehicles Sales Dashboard Preview:
![Dashboard Preview:](https://github.com/jagruthi315/Vehicles-sales-dashboard/blob/main/vehicles%20sales%20dashboard.PNG)


## What I Learned from this Project

• Gained a clear understanding of row context and filter context and how they influence calculations, helping in deriving accurate and meaningful metrics.

• Learned to apply DAX functions such as SUMX, COUNTX, and CALCULATE effectively by choosing the correct context based on business requirements.

• Understood the importance of creating measures instead of calculated columns, which helps reduce memory usage and improves report performance and loading speed.

• Explored data drilling techniques (drill-up and drill-down) to create dynamic and interactive visuals, enabling faster insight discovery without creating redundant charts.

• Developed the ability to evaluate insights with reasoning and impact and how it should be highlighted or hidden based on their business relevance, client requirements, and decision-making impact.








