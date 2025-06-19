# Vertex Mobile Churn Analysis

## Overview

Vertex Mobile Churn Analysis is a data analytics project focused on understanding and reducing customer attrition at Vertex Mobile Net, a telecom company offering a variety of communication services such as mobile phone, internet, and data plans. As customer churn poses a major challenge for subscription-based telecom businesses, this project aims to analyze customer data and uncover the main drivers behind churn.

Using Power BI as the primary BI tool, the analysis investigates key factors influencing churn, explores customer demographics, contract types, group plans, payment methods, and service usage patterns. The ultimate goal is to deliver actionable insights and recommendations that will help Vertex Mobile Net improve customer retention strategies, reduce churn rates, and increase overall customer satisfaction.



## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Analysis Workflow](#analysis-workflow)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Technologies Used](#technologies-used)
- [Results and Impact](#results-and-impact)
- [Contact](#contact)

## Dataset

- **Source:** Only Quality Data (acquired during my data analyst internship)
- **Rows/Columns:** 6,687 customers, 30 columns
- **Features:**
    - **Customer status:** Customer ID, Churn label (Yes/No), Churn reason, Churn category
    - **Demographics:** Gender, Age, Age groups (e.g., Under 20, 20-29, 30-39, etc.), Under 30, Senior
    - **Contact Information:** State, Phone number, Group, Number of customers in a group
    - **Contract and Payment:** Contract type (Month-to-Month, One Year, Two Year), Payment method (Paper Check, Direct Debit, Credit Card)
    - **Subscription Types & Charges:** Account length (months), Local calls, International calls/minutes, International plan, Extra international charges, Avg monthly GB download, Unlimited data plan, Extra data charges, Monthly charges, Total charges
    - **Customer Service:** Number of customer service calls
- **Time Period:** [Please specify the time period if known, e.g., Jan 2023 – Dec 2023]
- **Preprocessing:** Data cleaning included removing duplicates, handling missing values, verifying data types, creating age groups, extracting features, and removing irrelevant columns for analysis.




## Analysis Workflow
The following steps were taken to analyze the Vertex Mobile Net customer churn data:

1. **Data Cleaning and Preprocessing**
    - Removed duplicates and handled missing values
    - Verified and adjusted data types for accuracy
    - Created age groups and categorized other relevant variables
    - Removed irrelevant or redundant columns

2. **Exploratory Data Analysis (EDA)**
    - Explored churn distribution across demographics, contract types, and payment methods
    - Analyzed churn rates by state, group plans, and data plan usage
    - Visualized customer service interactions, account length, and monthly charges

3. **Feature Engineering**
    - Created new variables such as age brackets, churn categories, and customer segments
    - Calculated churn rates for different customer groups and segments

4. **Data Visualization**
    - Developed interactive dashboards in Power BI to present key findings
    - Used bar charts, pie charts, line charts, and maps for clear communication of insights

5. **Insights and Recommendations**
    - Identified major factors driving customer churn
    - Provided actionable recommendations to improve customer retention



## Key Findings
## Key Findings

- **Overall Churn Rate:** The churn rate among customers was 26.86%, with 1,796 out of 6,687 customers churning during the analysis period.
- **Churn by Contract Type:** Month-to-month contracts had the highest churn rate (47.31% for females, 40% for males), compared to lower rates for one-year and two-year contracts.
- **Churn by Payment Method:** Customers paying by paper check had the highest churn rate, followed by those using direct debit and credit card.
- **Churn Categories:** The most common churn category was “Competitor” (44.82%), followed by Attitude, Dissatisfaction, and Price.
- **Churn Reasons:** The main reasons for churn included extra data charges, limited reach, poor experience, lack of available support, and price concerns.
- **Churn by Age Group:** Older age groups (70-79 and 80+) had the highest churn rates, while the “Under 20” group had the lowest.
- **Group Plans:** Customers in group plans had lower average monthly charges and a significantly lower churn rate (6.51%) compared to those not in a group (33.49%).
- **Unlimited Data Plan:** Customers without unlimited data plans were more likely to churn compared to those with unlimited plans.
- **Account Length:** Churn rate decreased as account length increased; newer customers were more likely to churn.
- **Customer Service Calls:** Customers who churned had a much higher average number of customer service calls (239.59%) than those who stayed (37.21%).
- **Churn by State:** There were noticeable differences in churn rates and total customers by state, with some states experiencing higher churn than others.


## Recommendations

- **Promote Long-Term Contracts:** Encourage customers to switch from month-to-month to yearly contracts by offering attractive discounts or added benefits, as these contracts have significantly lower churn rates.
- **Targeted Retention Campaigns:** Focus retention efforts on customer segments with the highest churn rates, such as older customers and those not enrolled in group plans or unlimited data plans.
- **Simplify and Incentivize Payment Methods:** Provide incentives for customers to use digital payment methods (e.g., direct debit, credit card) instead of paper checks, which are associated with higher churn.
- **Reduce Extra Charges:** Review and address extra data and international charges, as these are common churn reasons. Consider bundled offers or clearer communication of potential fees.
- **Enhance Customer Service:** Improve customer support by reducing wait times, offering proactive support, and following up with customers who have made frequent service calls, since high service call frequency is linked to churn.
- **Promote Group Plans:** Actively market and facilitate group plan enrollment, as these have been shown to reduce individual churn rates and lower monthly charges for customers.
- **Unlimited Data Plan Offers:** Expand or promote unlimited data plan options to retain customers who are at higher risk of leaving due to data limits.
- **Onboarding and Engagement for New Customers:** Since churn is higher among newer customers, implement onboarding programs and regular engagement initiatives during the first few months of service.
- **State-Specific Strategies:** Analyze and address state-level factors contributing to higher churn rates with targeted campaigns or local offers.


## Technologies Used

- **Power BI:** For data visualization and interactive dashboard development
- **Microsoft Excel:** For initial data exploration and cleaning


## Results and Impact

- The analysis identified critical factors contributing to customer churn at Vertex Mobile Net, such as contract type, payment method, customer service interactions, and extra data charges.
- Data-driven recommendations were provided to help the company improve its customer retention strategies.
- The Power BI dashboards enabled management to easily monitor churn trends, segment at-risk customers, and track the effectiveness of retention initiatives over time.
- The project contributed to a better understanding of customer behavior and helped inform decision-making processes regarding product offerings, customer support, and targeted marketing.
- Insights from the analysis are expected to reduce churn rates, increase customer satisfaction, and boost overall company revenue.



## Contact

For questions, feedback, or collaboration opportunities:

- **LinkedIn:** [My LinkedIn Profile](https://www.linkedin.com/in/elvisfrimpong)
- **Email:** elvisfrimpong.da@gmail.com

