# Insurance Data Analysis


## Project Overview

This project analyzes insurance data to evaluate the performance of different policy types, customer demographics, and claim activities. It also explores policy status (active vs inactive), claim status distribution, and key business metrics to understand overall insurance performance and risk exposure.

The goal is to generate insights that can support better decision-making in pricing, customer retention, and claims management.

---

## Dataset

### Datasource
Dataset provided as part of a Udemy training course.

### Data Description
The dataset contains insurance records including policy information, customer demographics, premium amounts, coverage amounts, claim amounts, and claim status details.

### Dataset Size
- Rows: 10,004
- Columns: 15

### Key Fields
- Premium Amount
- Coverage Amount
- Claim Amount
- Claim Status
- Age group
- Policy Type
- Policy Status

### Additional Dataset
A supplementary dataset containing Customer name and feedback relating to the insurance dataset was used to generate a word cloud visualization. This dataset helped identify frequently occuring terms in customer feedback.

---

## Tools Used
- MYSQL - Data storage and initial data loading
- Power BI
  - Data cleaning, transformation (Power Query Editor)
  - Data modeling and Visualization.

---

## Data Cleaning
1. Standardized data types.
2. Renamed Columns for clarity and consistency.
3. Created a conditional column to segment customers based on age into Young Adult, Adult and Elder.
4. Created a conditional column to classify policies as Active or Inactive based on the Policy end date.

---

## Exploratory Data Analysis
- Total premium generated is 5.98M, while total coverage amount is significantly higher at 600.55M.
- Total claim amount is 16.91M, which is relatively low compared to the overall coverage.
- Active policies account for 58.13%, while inactive policies make up 41.87%.
- The customer base is evenly distributed by gender.
- Travel insurance contributes the highest premium, followed by Health, Auto, Life, and Home.
- Claim rejection rate is higher than settled and pending claims.
- Adults contribute the highest claim amount, while Young Adults contribute the least.
- Travel insurance records the highest claim activity across all claim statuses.

---

## Key Insights
- The business carries a high coverage exposure relative to premium income, indicating significant insured risk compared to revenue generated.
- Low total claim payout compared to coverage suggests either strong risk control or strict claims approval processes.
-  High claim rejection rates may indicate strict validation rules or potential inefficiencies in claims handling, which may impact customer satisfaction.
- Travel insurance is the strongest revenue driver but also the highest risk contributor.
- Health insurance is a major contributor to claims and operational cost.
- Adults represent the highest-risk customer segment in terms of claim value.
- A relatively high inactive policy rate (41.87%) suggests potential customer retention challenges.

---

## Dashboard
An interactive Power BI dashboard was created to analyze insurance performance across key metrics such as premiums, claim status, policy types, and customer demographics.

<img width="1075" height="506" alt="Insurance_Dashboard" src="https://github.com/user-attachments/assets/0e15c605-3ffb-4a1b-bdee-434eaeb2eea9" />

---

## Additional Visual
A word cloud was generated to visualize the most frequently occuring terms from the customer's feedback dataset, helping to highlight the frequently occuring themes and keywords in customer feedback.

<img width="1221" height="504" alt="Prism Insurance_WordCloud" src="https://github.com/user-attachments/assets/79833805-cccd-4de0-a3a3-e26b1c8ef6a2" />

---

## Recommendations
- Review pricing strategy to ensure premium income is aligned with the high coverage exposure.
- Investigate claim rejection patterns to improve fairness, transparency, and customer satisfaction.
- Strengthen customer retention strategies to reduce the high proportion of inactive policies.
- Focus risk monitoring on Travel and Health insurance due to their high revenue and claim contribution.
- Introduce risk-based pricing for Adult customers to better manage claim exposure.
- Improve claims processing efficiency to reduce pending claims and improve resolution time.
