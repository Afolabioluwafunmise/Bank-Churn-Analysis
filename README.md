# Bank-Churn-Analysis

# Table of contents

[Project Overview](#-project-overview)

 [understanding bank customer churn](#-understanding-bank-customer-churn)
 
   [why this matters?](#-why-this-matters?)
   


### Project Overview

**Understanding Bank Customer Churn**

Bank customer churn also referred to as *customer attrition* occurs when a customer ceases their relationship with a financial institution. In a banking context, this typically manifests as the closure of accounts, the transfer of deposits to a competing institution, or the gradual disengagement from the bank's products and services until the relationship is effectively dormant or terminated.

**Why This Matters?** 

At first glance, a 20% churn rate representing 2,037 customers out of 10,000 may appear to be a manageable figure. However, when examined through the lens of business impact, the implications are significantly more serious. Every churned customer represents not just a lost account but a lost stream of future revenue that the bank will need to replace through costly acquisition efforts.

**Problem Statement**

The bank is constantly loosing customers, which is causing revenue to drop and reducing the long-term value each customer brings.  Now the business does not have a clear understanding of why customers are leaving or which customers are leaving. Because of this lack of understanding & insights, the company cannot create effective plans to keep customers or predict when others might leave in the future.

**Project Objective**

The objective of this analysis is to examine customer data across 10,000 accounts to uncover the key drivers of churn, identify high risk customer segments and provide the bank with actionable insights to build a proactive and targeted retention strategy.

### Data Sources

This dataset contains details on; demographics, account balances, product usage, churn status, and geography.

[View Dataset](

### Tools & Technologies

•	Microsoft Excel: Data exploration & profiling
•	SQL: Data extraction & Create database
•	Power BI: core tool for data insights & visualization
•	Power Query: Used to clean, transform and create added columns
•	Dax: used in calculating measures
•	Data modeling: create relationships between tables for accurate visualizations & results

### Data Cleaning

Handled Missing Values
Removed Duplicates
Standardized formats
Feature Engineering
Encoding categorical variables

### Dashboard Snapshots

**Customer Insights Dashboard**

<img width="978" height="548" alt="bank churn snap" src="https://github.com/user-attachments/assets/b5759cf5-52af-40e9-a129-49e52bdd607d" />


**Customer Attrition Dashboard**

<img width="994" height="551" alt="bank churn 2" src="https://github.com/user-attachments/assets/ebab5247-f93a-4085-859e-af4a6999f373" />


### Key Insights & Conclusions

**Customer Insights**

•	**Gender Distribution:** Male customers account for 54.6% (5457) while female customers at 45.4% (4543), this near-parity suggests gender neutral product adoption across the bank’s offering.

•	**Geographic Reach:** France represents the banks largest customer market, accounting for 5,014 customers. Germany and Spain each contribute a significantly smaller share at 2,509, and 2477 customers respectively. Indicating a concentrated dependency on the French market.

•	**Product Adoption:** product 1 is the banks most widely held offering, with 5,084 customers. product 4 has an alarmingly low adoption rate with only 60 customers, raising questions about its market relevance, visibility, or value proposition to customers.

•	**Account Balance:** The largest customer segment by account balance is the low balance tier (3,692) followed closely by high balance holders at 3,147. This polarized distribution suggests the bank serves two distinct financial profiles

•	**Young & Tenure Segmentation:** The customers base is predominantly composed of young adults (4451 customers and middle-aged individuals (2781 customers), this youthful skew presents a significant growth opportunity but also a retention risk, as younger customers typically exhibit lower brand loyalty. On the tenure side,3020 customers are classified as experienced (long-standing relationships), while only 1474 are considered loyal veterans. Suggesting the bank faces structural challenges in converting long-term customers into truly committed advocates.

**Customer Attrition Analysis**

•	**Attrition Rate:** The bank recorded a total attrition rate of 20% (2,037 customers), meaning one in every five customers has exited the institution. Conversely, the retention rate stands at 80% (7663 customers)

•	**Geographic Risk** despite having only the second-largest customer base, Germany records the highest number of churned customers at 814, followed by Spain at 413. This disproportionately high attrition from Germany relative to its customer base size, signals a potential market-specific issue. Whether driven by competitive pressures, service gaps, or product market fit.


•	**Age Group Risk:** The middle-aged segment accounts for 1,057 churned customers (38.01%), young-adults follow with 538 customers (12.09%).

•	**Balance & Churn:**  churn is most prevalent among high balance customers (746 churned) and low balance customers (526 churned). Notably, customers with very high balances recorded the lowest churn at just 19 customers.


•	**Retention Signal:** credit card ownership correlates strongly with retention. Of the7963 customers who did not churn, a significant majority of 5631 hold a credit card with the bank. This strong correlation suggests that credit card ownership serves as a meaningful retention anchor.

•	**Positive Signal:** customers classified within the experienced tenure segment recorded the lowest attrition at 2,450 retained, demonstrating that long-term relationship building significantly reduces churn risk. In contrast, intermediate tenure customers (625) churned the most, suggesting critical vulnerability window in the mid-stage of the customer lifecycle.

### Recommendations

**Customer Insights**

•	Increase female engagement through women focused financial products & literacy programs.

•	Strengthen retention in Germany & Spain through localized marketing & engagement strategies

•	Boost product adoption for product 3 & 4 through bundling and discounts

•	Encourage higher balances through financial advisory services & tiered rewards

•	Enhance engagement for young adults & middle aged with customized banking products

**Customer Attrition Insights**

•	Introduce exclusive VIP banking services to high-net worth customers

•	Conduct targeted market research to address dissatisfaction in Germany

•	Improve onboarding experience for new customers

•	Expand credit card penetration across at-risk segments



### Interact With the Dashboard

View dashboard here

### License

### Author

Afolabi Oluwafunmise | Data Analyst | Financial Analyst

Email | My Linkedin


