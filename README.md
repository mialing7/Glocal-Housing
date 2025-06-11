# Glocal Housing: Housing Affordability Dashboard
*A GLOCAL CSJ Capstone Project | Summer 2025*

---

## Project Overview

This project systematically explores **housing affordability across Canada**, highlighting trends, financial pressures, market conditions, and lived experiences. Built exclusively on data from the Canada Mortgage and Housing Corporation (CMHC), this interactive Power BI dashboard supports policy analysis, public understanding, and civic engagement.

---

## Project Objectives

- Visualize and clarify Canada's current housing affordability landscape.
- Highlight historical trends and evolving affordability pressures.
- Analyze financial factors including mortgage rates and delinquency risks.
- Assess contemporary rental market conditions.
- Capture the lived experiences of Canadian residents from recent housing surveys.

---

## Target Audience

- Policymakers and urban planners  
- Housing advocacy organizations  
- Academic researchers and students  
- Community groups and concerned citizens  
- Civic technology and open-data communities  

---

## Dashboard Structure

The dashboard consists of five interconnected analytical pages:

### 1. Current Housing Affordability Crisis
- Map: Core housing need (CHN) rates by province
- Bar chart: Rent-to-income ratios by city
- Line chart: Shelter-cost-to-income ratio (STIR) comparison
- Heatmap: CHN by tenure (owners vs. renters)
- Vacancy rates and affordability indicators
- Summary KPI cards (rent, income, CHN%, vacancy rate)

### 2. Historical Trends & Affordability Erosion
- Line chart: CHN trends (1991–2021)
- Area chart: Evolution of renter vs. owner households (1971–2021)
- Line chart: Historical income vs. rent growth
- Bar chart: Household type shifts and tenure changes
- Timeline: Major housing policy milestones

### 3. Financial Factors – Mortgage Stress
- Line chart: Mortgage rates (1Y, 3Y, 5Y)
- Line chart: Delinquency rates over time by province
- Heatmap: Provincial delinquency distribution
- Scatter plot: Mortgage rate vs. delinquency rate
- Bar chart: Delinquency by CMA
- KPI cards: Average mortgage rate, delinquency %, risk zones

### 4. Rental Market Pressures – 2024 Snapshot
- Bar chart: Rent by unit size and CMA
- Line chart: Vacancy rate trends by province
- Map: Rental prices across CMAs
- Stacked bar chart: Unit mix by bedroom type
- Scatter plot: Vacancy vs. rent pressure
- Summary cards: lowest vacancy, highest rent, unit availability

### 5. Lived Experiences – Survey-Based Insights
- Bar chart: Satisfaction scores by province (CHS 2022)
- Heatmap: Reasons for housing dissatisfaction
- Funnel chart: Affordability stress → help-seeking → help received
- Boxplot: Satisfaction by tenure or income group
- Word cloud (optional): Thematic analysis of open-ended responses
- Table: Social housing experience summary (2023 survey)

---

## Data Sources

All datasets are sourced from the **Canada Mortgage and Housing Corporation (CMHC)**:

- **Mortgage Data**
  - `mortgage_rates_cleaned.csv`
  - `mortgage_delinquency_cleaned.csv`

- **Affordability & Household Composition**
  - `combined_core_housing_need_1991_2021.csv`
  - `combined_households_type_tenure_1971_2021.csv`

- **Rental Market**
  - `rmr-canada-2024-en.xlsx`

- **Survey Data**
  - `cleaned_housing_survey (2).xlsx`
  - `social-affordable-housing-survey-rental-2023-en.xlsx`

> Data was cleaned using Excel, Power Query, and Python (Pandas) to ensure consistency and joinability.

---

## Key Metrics

- **Core Housing Need (CHN)**: Households unable to access adequate, suitable, and affordable housing.
- **STIR (Shelter-Cost-to-Income Ratio)**: The percentage of income spent on shelter; a STIR > 30% indicates housing stress.
- **Vacancy Rate**: Proportion of available units not currently occupied.
- **Delinquency Rate**: Percentage of mortgages that are overdue.

---

## Tools and Methodology

- **Visualization**: Power BI (Desktop)  
- **Data Preparation**: Excel, Power Query, Python  
- **Documentation**: Dashboard annotations, KPI explanations, metric definitions  

---

## Expected Outcomes

- Establish a coherent narrative on Canada’s housing affordability crisis.
- Provide evidence to support data-driven policy and funding decisions.
- Inform advocacy efforts through public and stakeholder engagement.
- Contribute to open-source civic data storytelling at GLOCAL.

---

## Acknowledgments

This project was developed under the **GLOCAL Foundation of Canada** as part of the **Canada Summer Jobs (CSJ)** program, with support from mentors, housing policy researchers, and the broader GLOCAL research community.


## 📬 Contact

**Project Lead**: Mia Ling  
📧 Ziqing.l@glocalfoundation.ca  
🌐 [glocalfoundation.ca](https://www.glocalfoundation.ca)

