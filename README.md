# Insurance Data Analysis


### Project Overview

This project analyses the insurance data of a company to identify how well its different types of policies availableare performing,the age group of the customers of the company, the claim status of different policies taken within the time period of the report, the number of active and inactive members of the insurance company, also the feedback from customers who have used the company service.

### Dataset

#### Datasource
Dataset provided as part of a Udemy training course.

#### Data Description
This datset contains information on the 

###Dataset Size
- Rows: 10,004
- Columns: 15

### Key Fields
- Premium Amount
- Coverage Amount
- Claim Amount
- Claim Status
- Age group


### Tools Used
- MYSQL - Data storage and initial data loading
- Power BI
  - Data cleaning, transformation (Power Query Editor)
  - Data modeling and Visualization.

### Data Cleaning
1. Standardized data types
2. Renamed Columns
3. Created a conditional column to segment customers based on age into Young Adult, Adult and Elder
4. Created a conditional column to segment policies into Active or Inactive based on the Policy End Date

### Exploratory Data Analysis
- Total premium generated is 5.98M, while total coverage amount is significantly higher at 600.55M.
- Total claim amount is 16.91M, which is relatively low compared to the overall coverage.
- Active policies account for 58.13%, while inactive policies make up 41.87%.
- The customer base is evenly distributed by gender.
- Travel insurance contributes the highest premium, followed by Health, Auto, Life, and Home.
- Claim rejection rate is higher than settled and pending claims.
- Adults contribute the highest claim amount, while Young Adults contribute the least.
- Travel insurance records the highest claim activity across all claim statuses.

### Key Insights
- The business carries a high coverage exposure relative to premium income, indicating significant insured risk compared to revenue generated.
- Low total claim payout compared to coverage suggests either strong risk control or strict claims approval processes.
- High claim rejection rate may indicate strict validation rules or potential inefficiencies in claims processing. This may also indicate potential customer dissatisfaction.
- Travel insurance is the most important revenue driver but also the highest risk contributor.
- Health insurance is a major contributor to claims, making it a key cost driver.
- Adults represent the highest-risk customer segment in terms of claim value.
- A relatively high inactive policy rate (41.87%) suggests potential customer retention challenges.

### Dashboard
An interactive Power BI dashboard was created to analyze insurance performance across key metrics such as premiums, claim status, policy types, and customer demographics.


Recommendations
- Review pricing strategy to ensure premium income is aligned with the high coverage exposure.
- Investigate claim rejection patterns to improve fairness, transparency, and customer satisfaction.
- Strengthen customer retention strategies to reduce the high proportion of inactive policies.
- Focus risk monitoring on Travel and Health insurance due to their high revenue and claim contribution.
- Introduce risk-based pricing for Adult customers to better manage claim exposure.
- Improve claims processing efficiency to reduce pending claims and improve turnaround time.
