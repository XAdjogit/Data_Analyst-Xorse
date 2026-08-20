# Employee Workforce Intelligence Analytics — Roblox Africa Operations

**Type:** Capstone project, Generation Ghana Data Analyst Upskill Programme
**Tools:** SQL, Power BI, Excel
**Prepared by:** Xorse Adjo, Data Analyst

## Problem

Roblox Africa Operations (case study client) needed a workforce intelligence analysis integrating employee, department, finance, health, and education data to support organizational performance decisions.

## Approach

- Cleaned and structured 30,000 employee records and 150,000 performance records across multiple raw datasets (employee, department, education, health, finance, performance)
- Built a relational data model connecting Employee_Master, Fact_Performance, and Department_Performance tables
- Built a 4-page interactive Power BI dashboard covering:
  1. **Workforce Composition** — headcount by department, gender split, employee status, age distribution
  2. **Performance & Training** — average performance score and training hours by department, performance trend by year, bonus distribution
  3. **Compensation & Cost** — average salary and allowances by department, revenue vs. cost by department, cost trend by year
  4. **Health & Wellbeing** — average medical leave balance by department, insurance status breakdown

## Key Findings

- **Balanced, evenly-distributed workforce** — 30,000 employees split almost evenly by gender (~50/50) and across 8 departments (each holding 12–13% of headcount), with employee status split roughly equally between Active, On Leave, and Inactive
- **Performance is consistent across departments** — average performance scores cluster tightly between 3.58–3.61 across all departments and stay flat year-over-year (2021–2025), suggesting performance is not department-driven
- **Finance and HR generate the most value** — Finance Department leads with GHS 20.2M in revenue generated (against GHS 12.9M cost), followed by HR at GHS 17.6M revenue; Data and Analytics generates the least revenue (GHS 5.1M) despite the highest average performance score
- **Insurance status needs attention** — split almost evenly across Active, Pending, and Expired (~33% each), flagging a potential enrolment gap worth investigating

## Files

- 🖼️ Dashboard screenshots: [screenshots/](./screenshots)
- 🔗 Live dashboard (Power BI): https://app.powerbi.com/groups/91516f2c-96e8-4fc7-9c27-7eebc74d098f/reports/16acc2bc-ef1f-4a7a-8773-9a719d2ba74b?ctid=bd697c1b-c481-479c-841e-c618542675c3&pbi_source=linkShare&bookmarkGuid=8209bc26-87f7-4fbe-aba7-413ac890ed81
  *(Note: requires Power BI access — screenshots below give a full view for anyone without access)*
