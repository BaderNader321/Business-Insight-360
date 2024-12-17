# Business Insight 360

### Quick Links
  * [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZDU3ZmYwNWYtOWYxMS00MDNhLWEyZTctYWRjMzUxMDMwODRjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
  * [LinkedIn Post](https://www.linkedin.com/posts/badernader_business-insight-360-activity-7264969422296031232-T1a7?utm_source=share&utm_medium=member_desktop)

### Table of Contents
* [Company Details](#company-details)
* [Project Overview](#project-overview)
    * [Business Problem](#business-problem)
    * [Presentation](#presentation)
    * [Approach & Methodology](#approach-and-methodology)
    * [Key Insights & Outcomes](#key-insights-and-outcomes)
    * [Business Related Terms](#business-related-terms)
    * [Technical Details](#technical-details)
    * [Key Learnings](#key-learnings)
* [Understanding the Datasets](#understanding-the-datasets)
* [Data Modelling](#data-modelling)
* [Dashboards](#dashboards)

### Company Details
**AtliQ Hardware** is a prominent electronics accessories company that specializes in providing a wide range of high-quality hardware solutions, including connectors, cables, circuit boards, and other essential components for electronic devices and systems. They cater to both individual consumers and businesses, emphasizing quality and performance to meet the evolving needs of their customers.

#### Channels and Platforms
- **Retail Stores:** Physical locations such as Croma and Staples where customers can purchase AtliQ Hardware products.
- **Distributors:** Third-party entities like Neptune that help distribute AtliQ Hardware products to various markets.
- **Exclusive Showrooms:** Dedicated spaces, both physical and online, showcasing AtliQ Hardware products.
- **Online Platforms:** E-commerce websites and platforms such as Amazon and Walmart where customers can buy AtliQ Hardware products.

#### Customers
- **Individual Consumers:** People purchasing hardware components for personal use.
- **Businesses: Companies:** buying hardware solutions for their operations and projects, including top customers like Amazon, Neptune, Staples, and Walmart

___

[Back to the top](#business-insight-360)

### Project Overview

**AtliQ Hardware** has experienced significant growth in recent years. To maintain this momentum and gain a competitive edge, they've decided to leverage the power of data analytics. By implementing PowerBI, AtliQ aims to make data-driven decisions that will positively impact their finance, sales, marketing, and supply chain operations. This initiative is expected to provide valuable insights to stakeholders across all departments.

#### Business Problem
Recently, the company encountered unexpected losses due to the opening of a new store in America. This decision was primarily based on surveys, intuition, and basic Excel analysis. In contrast, our competitors possess dedicated analytics teams that leverage data-driven insights to inform their strategies.

To ensure our long-term survival and competitiveness, AtliQ Hardware must establish its own analytics team. This team will be crucial in providing data-driven insights and supporting informed decision-making.

During the project kickoff session, you will gain a clear understanding of the project’s objectives and rationale.

#### Presentation

#### Approach and Methodology
To deliver actionable insights for AtliQ Hardware, the project followed a systematic approach:

1. **Understanding Business Objectives**  
   Collaborated with stakeholders to identify key business challenges, such as financial losses and competitive gaps, and established clear project goals.  

2. **Data Collection and Cleaning**  
   Gathered data from multiple sources, including MySQL and Excel files. Used Power Query to clean and transform the data, handling missing values, duplicates, inaccuracies, and outliers 
   for consistency and reliability.  

3. **Data Modelling**  
   Developed a robust data model using Star and Snowflake schemas to efficiently organize relationships between fact and dimension tables, enabling streamlined analysis.  

4. **Analytics**  
   Leveraged Power BI for creating dashboards, utilizing DAX measures, calculated columns, and visual storytelling techniques to uncover key insights.  

5. **Dashboard Customization**  
   Designed tailored dashboards to meet specific departmental needs—finance, sales, marketing, supply chain, and executive functions. Incorporated features like dynamic headings,    
   conditional formatting, and bookmarks for a seamless user experience.  

6. **Iterative Refinement**  
   Regularly reviewed and optimized reports and dashboards based on stakeholder feedback, ensuring alignment with business requirements and usability standards.  

7. **Actionable Insights and Recommendations**  
   Delivered insights on financial performance, sales trends, marketing effectiveness, and supply chain operations, empowering data-driven decision-making across the organization.  

#### Key Insights and Outcomes
Here’s a simplified and more consistent version:

---

### Key Metrics and Insights  
In this analysis, I’m focusing on **Net Sales (NS$)**, **Gross Margin (GM%)**, and **Net Profit (NP%)** to identify what influenced these numbers. I’ve also discussed these insights further in the presentation video.

#### **Finance View**  

1. **Net Sales (NS$)**  
   - **2022 Net Sales:** $3.74B  
   - **2021 Net Sales:** $823.8M  
   - **Growth:** **+353.5%**  
   - This strong increase reflects robust demand and solid sales performance for Atliq’s products.  

2. **Gross Margin (GM%)**  
   - **Gross Margin:** Improved by **4.37%** compared to last year.  
   - This shows the company’s efficiency in managing production costs, as Gross Margin measures how effectively sales are converted into gross profit (before other expenses).  

3. **Net Profit (NP%)**  
   - **2022 Net Profit:** **-13.98%**  
   - **2021 Net Profit:** **-6.63%**  
   - The decline is concerning and primarily driven by **higher operating expenses** (e.g., marketing and promotions).

##### **What’s Driving These Metrics?**  
Looking deeper into the **Profit & Loss Statement**:

1. **Gross Margin %**  
  - **GM%:** 38.08%  
  - Driven by a Gross Margin of **$1,422.88M**, calculated as the difference between Net Invoice Sales and Manufacturing Costs.  

2. **Net Profit %**  
  - Net profit is heavily impacted by **Operational Expenses**, which stand at **$1,945.30M**.  
  - Since operational costs exceed the Gross Margin, the result is an overall net loss for the company.

##### **Additional Insights from the P&L Statement**  

1. **Deductions Breakdown**  
   - **Pre-Invoice and Post-Invoice Deductions** (e.g., discounts, returns) grew significantly:  
     - Pre-Invoice: **+340%**  
     - Post-Invoice: **+341%**  
   - This could indicate **aggressive discounting** or an increase in product returns.  

2. **Cost of Goods Sold (COGS)**  
   - **Manufacturing Costs**: **+341%**  
   - **Freight Costs**: **+355%**  
   - Rising freight costs might be due to **logistics issues**, **higher fuel prices**, or **increased shipment volumes**—worth further investigation.  

3. **Gross Margin Per Unit**  
   - **2022:** $15.76 per unit (up from $5.99)  
   - **Growth:** **+162%**  
   - It’s important to identify **which products or services** are driving this growth and explore whether the success can be replicated across other segments.

#### Business Related Terms
- **Gross Price:** The original selling price before any discounts or reductions.
- **Pre-Invoice Deductions:** Discounts applied before the final bill is created.
- **Post-Invoice Deductions:** Additional discounts or adjustments made after the bill is issued.
- **Net Invoice Sale:** The final amount on the bill after all deductions are applied.
- **Gross Margin:** The difference between selling price and cost of production, shown as a percentage.
- **Net Sales:** Total sales minus all returns, discounts, and deductions.
- **Net Profit:** The money left over after subtracting all expenses from total revenue.
- **COGS (Cost of Goods Sold):** The direct cost of producing the products sold by a company.
- **YTD (Year to Date):** The total amount accumulated from the start of the current year until now.
- **YTG (Year to Go):** The remaining period until the end of the current financial year.
- **Direct:** Selling products straight to the end customer without intermediaries.
- **Retailer:** A business that sells products directly to consumers.
- **Distributors:** Companies that buy products from manufacturers and sell to retailers.
- **Consumer:** The final person who buys and uses the product.

#### Technical Details
- **MySQL:** Utilized SQL databases to manage millions of rows of data, subsequently connecting them to Power BI.
- **Power Query:** Employed Power Query for data transformation, cleaning, and merging multiple tables.
- **Microsoft Excel:** Leveraged Excel to incorporate smaller, yet crucial datasets like targets, operating expenses, and market share data.
- **Microsoft Power BI:** Primarily utilized Power BI for analytics and dashboard development to address business challenges.
- **DAX Studio:** Employed DAX Studio to optimize report performance and accelerate response times across various dashboards.

#### Key Learnings
- **Data Integration:** Connected data seamlessly from MySQL and Excel.
- **ETL Process:** Cleaned and transformed data using Power Query.
- **Data Modelling:** Designed Star and Snowflake schemas to connect related tables.
- **Advanced Analytics:** Created calculated columns and DAX measures for deeper insights.
- **Interactive Dashboards:** Used buttons for intuitive navigation, applied bookmarks to switch between visuals dynamically, and designed dynamic headings that change based on filters.
- **Visual Enhancements:** Leveraged conditional formatting for impactful storytelling.
- **Real-Time Updates:** Configured automatic data refresh through the Power BI gateway.

___

[Back to the top](#business-insight-360)

### Understanding the Datasets
Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get good understanding of what are data available.

- **Dimension table:** It will have the static data like details of customer and products

- **Fact table:** It will have the data about the transactions  

#### gdb041

  **dim_customer**

- **27** distinct markets (ex India, USA, spain)
- **75** distinct customers thorough out the market
- **2** types of platforms
  - Brick & Motors - Physical/offline store
  - E-commerce - Online Store (Amazon, flipkart)
        
**Three channels**
 - Retailer
 - Direct
 - Distributors

**dim_market**

 - 27 distinct markets (ex India, USA, spain)
 - 7 sub-zones
 - 4 regions
    - APAC
    - EU
    - nan
    - LATAM
   
**dim_product**

  - Divisions
    - P & A
      - Peripherals
      - Accessories
    - PC
      - Notebook
      - Desktop
    - N & S
      - Networking
      - Storage
    - There are 14 different categories, Like Internal HDD, keyboard
    - There are different variants available for the same product

**fact_forecast_monthly**

 - This table is used to forecast the customer’s need in advance, which can help in

    - Higher customer satisfaction

    - Reduced cost in warehouses for storage purpose
 
 - The table is denormalized by data engineering team, as it is a data warehouse which is aimed to be used for analytical work.
 
 - All the date of the month will be replaced by the start date of the month
 
 - It will have all the column names and in the end it will have the forecast quantity need of the customer

**fact_sales_monthly**

- This table is more or less is same as fact_forecase_monthly table, but the last column has the value of sold quantity instead of forecast value.

#### gdb056

**freight_cost**
 
  - This table has details of travel cost and other cost for each market with fiscal year

**gross_price**

  - Has the details of gross prices with product code
    
**manufacturing_cost**

  - Has the details of manufacturing cost with product code with year

**Pre_invoice_dedutions**

  - Has the details of pre invoice deductions percentage for each cutomer with year

**Post_invoice_deductions**

  - Post invoice deductions and other deductions details

___

[Back to the top](#business-insight-360)

### Data Modelling

<img src="https://github.com/BaderNader321/Business-Insight-360/blob/61d10d1d8a4f94f4a5bbfb453ccec580a7d26132/Data%20Modelling%20(BI%20360).png" class="center">

### Dashboards
**AtliQ Hardware** is committed to data-driven decision-making. To support this goal, we've developed a suite of PowerBI dashboards tailored to specific user needs.

- **Finance View:** Provides insights into financial performance, including revenue, expenses, and profitability.
- **Sales View:** Offers a comprehensive view of sales trends, customer behavior, and sales pipeline.
- **Marketing View:** Delivers insights into marketing campaign effectiveness, customer acquisition, and customer retention.
- **Supply Chain View:** Provides visibility into supply chain operations, inventory levels, and logistics performance.
- **Executive View:** Presents a high-level overview of key performance indicators (KPIs) across all business functions.

#### Home Page
<br>
<img src="https://github.com/BaderNader321/Business-Insight-360/blob/eeb539b51b969f448ce0ebe4f91bc33892b26a2d/Reports/2.png" class="center">

#### Finance View
<br>
<img src="https://github.com/BaderNader321/Business-Insight-360/blob/eeb539b51b969f448ce0ebe4f91bc33892b26a2d/Reports/3.png" class="center">

#### Sales View
<br>
<img src="https://github.com/BaderNader321/Business-Insight-360/blob/eeb539b51b969f448ce0ebe4f91bc33892b26a2d/Reports/4.png" class="center">

#### Marketing View
<br>
<img src="https://github.com/BaderNader321/Business-Insight-360/blob/eeb539b51b969f448ce0ebe4f91bc33892b26a2d/Reports/5.png" class="center">

#### Supply Chain View
<br>
<img src="https://github.com/BaderNader321/Business-Insight-360/blob/eeb539b51b969f448ce0ebe4f91bc33892b26a2d/Reports/6.png" class="center">

#### Executive View
<br>
<img src="https://github.com/BaderNader321/Business-Insight-360/blob/eeb539b51b969f448ce0ebe4f91bc33892b26a2d/Reports/7.png" class="center">

___

[Back to the top](#business-insight-360)

