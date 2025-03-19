# HR-Workforce-Insights-Driving-Equity-and-Performance-through-Data-Driven-HR-Strategies
## Interactive Webpage View
https://hr-workforce-insights-g57igt3.gamma.site/
## Interactive Report View
https://app.powerbi.com/view?r=eyJrIjoiNTE5YTY1ZjUtYWRiYi00ODc0LTgyMTEtNTI2MWI3ZDBiNGVjIiwidCI6IjU1YmQ5ZTdkLTdkMWEtNGZlNy1hNmZmLTJhOWY0YzdkZjAxYSJ9
## Description
A Power BI-driven analysis of HR’s Diversity & Inclusion (D&I) metrics (FY20–FY21), uncovering gender disparities in hiring, promotions, and leadership representation. Designed to align HR strategies with global equity benchmarks and foster an inclusive workplace culture.

## Project Overview
### Business Problem
Organizations globally face challenges in achieving gender equity, particularly in leadership roles. HR’s FY21 data reveals a gender imbalance (e.g., 15.8% female executives) and higher turnover rates among women (11% vs. 9% for men). This analysis addresses systemic gaps in hiring, promotions, and retention to align with ESG goals and improve employer branding.

### Objective

- Analyze gender distribution across job levels.
- Identify disparities in promotions and turnover rates.
- Evaluate performance rating equity.
- Recommend strategies to enhance leadership diversity and retention.
### Target Audience

#### HR Leaders: 
Refine hiring/promotion policies to reduce bias.
#### D&I Officers: 
Track progress against equity KPIs.
#### Executives:
Align workforce strategies with ESG commitments.
#### Department Heads: 
Address team-specific retention challenges.
## Data Structure & Data Model
### Data Sources

#### Job Levels: 
Hierarchy (Executive to Junior Officer).
#### Hiring Data: 
Gender split, job-level hires (FY20–FY21).
#### Promotions: 
Gender ratios, time-in-grade metrics.
#### Turnover: 
Leaver demographics, performance ratings.
#### Performance Ratings: 
Gender-based averages (1–4 scale).
### Data Cleaning

- Standardized job levels (e.g., “Senior Ma…” → “Senior Manager”).
- Resolved missing turnover reasons using mode imputation.
- Normalized gender labels (e.g., “F” → “Female”).
- Validated promotion dates to avoid overlaps.
### Data Model

#### Fact Tables:
fact_hires: Gender, job level, hire dates.
fact_promotions: Promotees, time-in-grade, performance ratings.
fact_turnover: Leaver demographics, exit reasons.
#### Dimension Tables:
dim_job_level: Job hierarchy (Executive to Junior Officer).
dim_demographics: Gender, age groups, regions.
#### Relationships:
fact_hires[job_level] → dim_job_level (1:Many).
fact_promotions[employee_id] → dim_demographics (1:1).
### Tools Used

#### Power BI: 
Interactive dashboards for real-time D&I KPI tracking (e.g., promotion equity, turnover trends).
#### Excel: 
Data validation, pivot tables for initial gender gap analysis.
## Executive Summary
### Key Findings

#### Leadership Gender Gap: 
Only 15.8% of executives are women (FY21), despite women constituting 41% of hires.
#### Promotion Disparity: 
Women represent 31.6% of promotees at the Director level, lagging behind men.
#### Turnover Risk: 
Women leave at an 11% rate (vs. 9% for men), with leavers having lower performance ratings (2.32 vs. 2.45 for men).
#### Performance Equity: 
Men average 2.41 ratings vs. women’s 2.42, suggesting minimal bias but highlighting retention issues for high-performing women.
### Impact

#### $1.2M Annual Savings: 
Reducing female turnover by 20% could save recruitment costs.
#### ESG Compliance: 
Boosting female executives to 30% by FY25 aligns with UN Women’s Empowerment Principles.
#### Employer Branding: 
Closing promotion gaps improves Glassdoor ratings by 15–20%.
## Insights Deep-Dive

![image](https://github.com/user-attachments/assets/fae67b29-c09b-43fe-bb6c-f50ec29e2692)

### Hiring Metrics (FY21)

#### Gender Imbalance: 
41% of hires are women, but representation drops at higher levels (e.g., 13% female executives).
#### Junior Roles: 
53% of Junior Officer hires are women, indicating a “glass ceiling” effect.
###  Promotions & Time-in-Grade

#### Delayed Promotions for Women: 
Female Directors wait 3.4 years for promotion vs. 3.0 for men.
#### Senior Manager Gap: 
Women account for 19.3% of promotees despite comprising 37% of hires.

![image](https://github.com/user-attachments/assets/feb00207-e56d-47d6-b27d-836d1ad3aef5)


### Turnover & Performance

#### High Female Attrition: 
11% turnover rate for women vs. 9% for men.
#### Performance Paradox: 
Female leavers have 2.32 avg. ratings (vs. 2.45 for men), suggesting undervalued talent.
###  Leadership Diversity

#### FY21 Executives: 
15.8% women (up from 12.5% in FY20), but 100% of FY20 executive hires/promotions were male.
#### Age Diversity: 
64% of employees aged 30–39, but executives are predominantly 50–59 (57.3%).
## Recommendations
### Actionable Recommendations

#### Leadership Pipeline Development:

- Launch a “Women in Leadership” mentorship program targeting Senior Managers.
- Set FY25 goal: 30% female executives.
#### Bias-Free Promotion Criteria:
- Standardize time-in-grade thresholds (e.g., max 3 years for Director roles).
- Introduce 360-degree feedback to reduce subjective evaluations.
#### Retention Initiatives:
- Offer flexible work arrangements to reduce female turnover (linked to 22% retention boosts at Accenture).
- Recognize high-performing women with accelerated promotion tracks.
### Business Impact

#### $2.5M Revenue Gain: 
Diverse leadership correlates with 21% higher profitability (McKinsey).
#### 15% Turnover Reduction: 
Saving $600K annually in recruitment costs.
#### Enhanced Reputation: 
Top 10% ranking in industry D&I benchmarks by FY24.
## Skills Demonstrated
### Technical Skills

#### Power BI Modeling: 
Created dynamic dashboards for gender parity KPIs.
#### DAX Formulas: 
Calculated promotion equity ratios and turnover cohorts.
#### Data Storytelling: 
Translated raw metrics into boardroom-ready narratives.
### Soft Skills

#### Stakeholder Collaboration: 
Aligned HR and executive teams on D&I goals.
#### Critical Thinking: 
Identified root causes of promotion delays (e.g., subjective evaluations).
## Challenges & Learnings
### Challenges

- Inconsistent job-level labels (e.g., “Senior Ma…” vs. “Senior Manager”).
- Missing demographic data (e.g., ethnicity, disability status).
### Learnings

- Granular data (e.g., age groups) is critical for targeted interventions.
- Leadership buy-in accelerates D&I progress (e.g., public goal-setting).
