# SALES PERFORMANCE ANALYSIS
## Automating Sales Data Integration and Reporting with Power BI Folder Connections
![image](https://github.com/user-attachments/assets/c4f0e9b5-7ab5-4902-ba68-374c94a38615)

***Disclaimer⚠️:** All datasets, slides and reports do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual mention. All info are dummy and design to demonstrate my capabilities of using PowerBI to perform advance analysis on healthcare dataset*
## INTRODUCTION
This case study demonstrates how PureSip Beverages leveraged Microsoft Excel and Power BI to automate sales data integration through local folder connectivity. By connecting Power BI directly to a centralized folder containing retailer sales spreadsheets, the company eliminated manual data consolidation, improved reporting accuracy, and streamlined its sales analysis process.

The solution enabled automatic data refresh whenever new sales files were added to the folder, ensuring stakeholders always had access to the latest sales information. Interactive dashboards were developed to provide visibility into sales performance, retailer contributions, regional trends, product demand, and revenue generation.

  ![image](https://github.com/joel-adusei/PureSip-PowerBI-CaseStudy/blob/main/images/ChatGPT%20Image%20Jun%2010,%202026,%2007_57_05%20PM.png?raw=true)

## PROBLEM STATEMENT
PureSip Beverages distributes popular beverage brands such as Coca-Cola, Fanta, and Sprite to major retailers including Costco, Walmart, Target, and Walgreens. Each regional manager maintained separate sales spreadsheets, creating several operational challenges:

- Data Consolidation

Combining multiple retailer spreadsheets into a unified sales report required significant manual effort, making the process time-consuming and prone to errors.

- Data Accuracy

Variations in spreadsheet structures, naming conventions, and data-entry practices across regions often resulted in inconsistencies and reporting inaccuracies.

- Limited Analysis

Traditional spreadsheet reporting provided limited capabilities for advanced analytics, making it difficult to identify sales trends, retailer performance, regional opportunities, and product demand patterns.


## AIM OF THE PROJECT
- Automate the integration of sales data from multiple retailer spreadsheets using Power BI Folder Connections.
- Improve data accuracy and consistency by eliminating manual consolidation processes.
- Analyze sales performance across retailers, regions, and beverage brands.
- Develop interactive dashboards to monitor key business metrics and support strategic decision-making.
- Create a scalable reporting solution capable of accommodating future business growth.

  
## METHODOLOGY 
Explored retailer sales datasets to understand key fields, business relationships, and reporting requirements.

**ETL Process**

Extracted data from multiple Excel files stored in a centralized folder, transformed and cleaned the data using Power Query, and loaded it into Power BI.

**DATA MODELING**

Created relationships between sales transactions and supporting dimensions such as Date, Retailer, Product, and Region.

**Analysis & Visualization**

Developed interactive dashboards and visualizations to uncover trends in revenue, units sold, retailer performance, and regional sales distribution.


## DATA MODELLING
The project follows a star schema data model designed to support efficient reporting and analysis.

The central Sales Fact Table contains transactional metrics such as Units Sold, Sales Revenue, Order Date, Payment Date, and Price per Unit. This table is connected to several dimension tables, including:

Retailer Dimension (Costco, Walmart, Target, Walgreens)
Product Dimension (Coca-Cola, Fanta, Sprite, etc.)
Date Dimension (Year, Quarter, Month)
Region Dimension (Region and State)

This structure enables flexible analysis across multiple business perspectives while maintaining high report performance.


## DATA ANALYSIS

### KPI Performance Overview

The dashboard reports a total sales revenue of **$1.21 million** generated from **2.31 million units sold** across **4 major retailers**. The KPI tracker recorded **238,850**, which is slightly below the target of **250,000**, representing a performance gap of approximately **4%**. Despite this shortfall, overall sales volume and revenue indicate strong market penetration and consistent demand across retailers.

### Sales Trend Analysis

### **Sales by Month**

The monthly sales trend demonstrates a steady increase throughout the year. Sales started at approximately **82K** in January and experienced gradual growth through the first half of the year. The strongest growth period occurred between **May and August**, where sales increased significantly and reached a peak of approximately **116K** in August.

Following this peak, sales declined slightly during September and October before recovering in November and December. The year ended with sales levels close to the annual peak, suggesting strong year-end demand and positive sales momentum.

**Key Insights:**

* August recorded the highest monthly sales performance.
* Sales growth accelerated significantly during Q2 and Q3.
* A temporary slowdown occurred in September–October.
* Strong recovery in Q4 indicates sustained customer demand.

  ![image](https://github.com/joel-adusei/PureSip-PowerBI-CaseStudy/blob/main/images/sales%20trend.JPG?raw=true)




## Total Sales | Region, Retailer, and Beverage Brand


### **Regional Sales Analysis**


The regional map visualization highlights variations in sales performance across different states and regions. Texas appears to be one of the strongest-performing locations, contributing significantly to overall sales revenue.

The geographical analysis provides management with valuable insights into high-performing markets and areas that may require additional marketing efforts, distribution support, or retailer engagement.

**Key Insights:**

* Sales are concentrated in a few high-performing regions.
* Certain states contribute disproportionately to overall revenue.
* Geographic performance monitoring can support expansion and resource allocation decisions.

  
### **Retailer Performance Analysis**


Retailer analysis shows that **Walmart** generated the highest sales revenue, contributing approximately **392K**, making it the company's most valuable retail partner.

**Costco** ranked second with approximately **332K** in sales, followed by **Walgreens** at **251K** and **Target** at **239K**.

This distribution indicates that Walmart and Costco account for a significant portion of total revenue and should remain key strategic partners.

**Key Insights:**

* Walmart is the top-performing retailer.
* Costco is the second-largest contributor to sales.
* Sales are concentrated among a small number of major retailers.
* Opportunities exist to increase sales performance in Walgreens and Target locations.

 
### **Beverage Brand Performance Analysis**


Brand-level analysis reveals that **Dasani Water** is the best-performing product, generating approximately **234K** in sales revenue. Closely following are **Coca-Cola** (**228K**) and **Diet Coke** (**214K**).

Among the beverage portfolio, **Fanta** recorded the lowest sales performance at approximately **167K**, while **Sprite** and **Powerade** generated moderate sales volumes.

**Key Insights:**

* Dasani Water is the highest-selling beverage brand.
* Coca-Cola remains one of the company's strongest products.
* Fanta presents potential opportunities for promotional campaigns and sales improvement.
* Consumer demand appears strongest for water and cola-based beverages.


  ![image](https://github.com/joel-adusei/PureSip-PowerBI-CaseStudy/blob/main/images/total%20sales.JPG?raw=true)

  

### Overall Business Insights

The dashboard reveals that PureSip Beverages experienced healthy sales growth throughout the year, supported primarily by Walmart, Costco, and top-performing brands such as Dasani Water and Coca-Cola. The strong upward sales trend observed during the middle and final months of the year suggests effective market demand and retailer performance.

By leveraging Power BI's automated folder connection, management gains real-time visibility into sales performance across retailers, brands, and regions, enabling faster decision-making and more accurate business planning.


## BUSINESS IMPACT

The implementation of Power BI Folder Connections transformed PureSip Beverages' sales reporting process by automating data collection and integration from multiple retailer spreadsheets. Instead of manually consolidating quarterly sales files, Power BI automatically combines and refreshes data whenever new files are added to the designated folder.

### Key Benefits Achieved

#### Automated Data Integration

The folder connection eliminated the need for manual data consolidation by automatically combining sales data from multiple retailers into a single reporting model.

#### Improved Data Accuracy

Standardized data processing reduced errors associated with manual data entry, spreadsheet manipulation, and inconsistent reporting formats.

#### Faster Reporting

Stakeholders gained access to near real-time sales insights, allowing them to monitor performance and respond more quickly to changing market conditions.

#### Enhanced Decision-Making

Interactive dashboards provided visibility into retailer performance, product demand, regional sales trends, and KPI achievement, enabling more informed business decisions.

#### Scalability

The solution can easily accommodate additional retailers, regions, or sales files without requiring changes to the reporting process, supporting future business growth.

---

## RECOMMENDATIONS

### Strengthen Relationships with Top Retailers

Since Walmart and Costco contribute the largest share of sales revenue, PureSip should continue strengthening partnerships with these retailers through promotional campaigns, exclusive offers, and inventory support.

### Improve Performance of Lower-Contributing Retailers

Target and Walgreens generate comparatively lower sales volumes. Management should investigate opportunities to increase sales through localized marketing initiatives and product placement strategies.

### Focus on High-Performing Beverage Brands

Dasani Water, Coca-Cola, and Diet Coke consistently generate strong sales performance. Maintaining adequate inventory levels and promotional support for these brands will help sustain revenue growth.

### Increase Promotion for Underperforming Products

Fanta records the lowest sales among the featured brands. Targeted marketing campaigns, discounts, and retailer promotions could help improve its market performance.

### Leverage Seasonal Demand Patterns

Sales peak during the middle and latter part of the year, particularly between June and August. Forecasting and inventory planning should align with these seasonal trends to prevent stock shortages and maximize revenue opportunities.

### Expand Regional Analysis

Further investigation into top-performing and underperforming regions can help identify growth opportunities and optimize distribution strategies.

---

## CONCLUSION

This project demonstrates how Power BI Folder Connections can effectively automate sales data integration and reporting processes. By connecting multiple retailer spreadsheets through a centralized folder, PureSip Beverages eliminated manual data consolidation, improved data accuracy, and significantly reduced reporting workload.

The resulting dashboard provides valuable insights into sales trends, retailer performance, regional distribution, and beverage brand performance. Key findings revealed strong contributions from Walmart and Costco, increasing sales momentum throughout the year, and high demand for products such as Dasani Water and Coca-Cola.

Overall, the solution showcases how Power BI can transform fragmented spreadsheet-based reporting into a scalable, automated, and data-driven business intelligence system that supports faster and more effective decision-making.

---

## THANK YOU

Thank you for taking the time to review this case study.

For questions, collaboration opportunities, or feedback, please feel free to contact me.


