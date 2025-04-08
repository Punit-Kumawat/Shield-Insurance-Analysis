# Shield-Insurance-Analysis
This project is a part of the virtual Internship at AtliQ Technologies.

👉 [Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTUzNWIxMjctNThhYy00ZTE3LTg0MWItMjRjZWVlMzJjN2IyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Project Overview:
Shield Insurance is committed to providing affordable and accessible insurance policies for individuals across all age groups. The company operates in five major cities — Mumbai, Chennai, Delhi NCR, Hyderabad, and Indore — and distributes its policies through various channels including offline agents, direct sales, a mobile application, and a dedicated website. Currently, Shield Insurance offers a diverse portfolio of nine policy types.

As part of this project, my objective was to support the company in making informed, data-driven decisions by analyzing their operational data from November 2022 to April 2023.

### 📁 Data Sets Used:
For this project, I worked with a Star Schema data model consisting of 3 Dimension Tables and 2 Fact Tables:

### 🔹 Dimension Tables:
Dim_Customer – Contains customer information

Dim_Date – Includes date-related details 

Dim_Policies – Information about policy types and categories

### 🔸 Fact Tables:
Fact_Premiums – Records of premium payments made by customers

Fact_Settlements – Details of insurance claims and settlements

## Dashboard Overview - 

I created a dashboard with three key sections:

**Home Page -** When a user logs in for the first time, they will land on this page. From here, they can navigate to different pages.

![home page](https://github.com/Punit-Kumawat/Shield-Insurance-Analysis/blob/main/Screenshot%202025-04-08%20173226.png)

**General Analysis -** Provides an overview of essential insurance metrics, including a monthly revenue and customer trend. Also age group and city segmentation.

**Sales Mode Analysis -** Showcases sales performance metrics across different modes, including a revenue trend chart highlighting the sales channel that generated the highest revenue percentage.

**Age Group Analysis -** Demonstrates company revenue and customer performance by age group, including metrics for estimated settlement amounts and policy preferences.

## Insights -

 1. Revenue and Customer Trends: March 2023 recorded the highest revenue and customers, while November 2022 saw the lowest daily revenue and customergrowth.

 2. Regional Revenue: Delhi NCR region led with the highest revenue, whereas Indore contributed the least in both revenue and customer base.

 3. Top Age Group: The 31-40age group generated the highest revenueand had the largest number of customers.

 4. Lower-Contributing Age Groups: Customers aged 18-24 and 25-30 contributed the least, representing just 8.30% of total revenue.

 5. Sales Channel Performance: Offline agent channels performed best, generating 55.67% of the revenueand serving 55.41% of customers.

 6. Top Policy: Policy ID -POL2005HEL generated the highest revenue despite being held by only 7.33% of customers.

 7. Lower-Revenue Policies: Policy IDs -POL4321HEL and POL4331HEL collectively contributed just 5.96% of the revenue while covering 30.43% of customers.

 8. Claims Settlement: Customers aged 31-40 had the highest settlement amounts, whereas those aged 18-24 and 25-30 had the lowest settlement needs.

## Recommendations -

 1 - Target High-Revenue Segments :

 •The 31-40 age group contributes the highest revenue ($166.73M). Marketing campaigns should be 
tailored to attract and retain this group.
 •The 65+ age group is the second-highest revenue generator ($145.23M), indicating a strong preference 
for policies among senior citizens.

 2 - City-Specific Strategy :

 •Delhi NCR, Mumbai, and Hyderabad generate the highest revenue and have the most customers. Focus 
on improving customer experience and retention strategies in these cities.
 •Indore and Chennai have lower revenues but a notable number of customers, indicating potential for 
growth.

 3 - Optimize Sales Channels :

 •Offline-Agent sales contribute the highest number of customers (14,873). Investing in training and incentives for agents can boost sales further.
 •Online-App and Website sales are significantly lower. A strong digital marketing campaign and an easy-to-use 
interface can improve online sales.

4 - Improve Policy Offerings :

 •POL2005HEL and POL1048HEL generate the highest revenue. These policies should be further 
promoted.
 •Lower revenue policies (e.g., POL4321HEL) should be reviewed for better pricing or improved 
benefits to attract customers.

 5 - Enhance Customer Retention :

 •Repeat customers can be encouraged through loyalty programs, renewal discounts, and targeted 
follow-ups.
 •Analyzing why certain policies have higher repeat customers can help refine offerings.

 6 - Seasonal Trends :

 • March shows a peak in new customers. Special offers or discounts should be launched before this 
period to maximize conversions.
 • Other months have lower numbers; introducing seasonal campaigns can help maintain steady sales.

 7 - Engage Young Customers :

 Analyze why customers aged 18-30 show less interest in purchasing insurance policies. Develop affordable and 
customized plans tailored to their needs and financial situation to attract this age group.


## 🛠 Tools Used:
- Power BI
- Microsoft Excel
- Power Query
