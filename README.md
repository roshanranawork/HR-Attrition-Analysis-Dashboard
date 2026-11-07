# HR-Attrition-Analysis
HR Employee Attrition Analysis using PostgreSQL, SQL, and Power BI to identify employee turnover trends, analyze workforce patterns, and generate actionable insights for better HR decision-making.
# HR-Attrition-Analysis

**Why do employees leave TechIT Solutions, and what can HR do about it?**

HR employee attrition analysis using PostgreSQL, SQL and Power BI to identify turnover trends, analyze workforce patterns and generate actionable insights for HR decision-making.

TechIT Solutions is an IT services company with **10,010 employees**. **2,251 have left**, an attrition rate of **22.49%**.

## At a Glance

| Total employees | Left the company | Still active | Attrition rate | Average age |
|---|---|---|---|---|
| 10,010 | 2,251 | 7,759 | **22.49%** | 40 |

## Business Problem

High attrition delays projects and raises hiring and training costs. HR initiatives are generic because nobody can see the real drivers. This project answers 10 questions:

1. What is the overall attrition rate?
2. Which departments lose the most people?
3. How does job role affect attrition?
4. Does distance from home matter?
5. Does overtime push people out?
6. How do job and environment satisfaction affect retention?
7. Do people with poor work-life balance leave more?
8. Does frequent travel increase attrition?
9. Does time in the same role affect leaving?
10. Do salary hikes keep people?

**Who uses it:** HR, department heads, business leaders, recruitment and finance teams.

## Key Findings

| Question | What the data shows | Action |
|---|---|---|
| Overall | 2,251 of 10,010 employees left (22.49%) | Set a target to bring this down |
| Departments | Cyber Security has the most leavers (503), then Software Development (464), Data Science (443), IT Services (431) and Network Administration (410) | Start retention work in these teams |
| Job roles | Leavers are spread across many roles. Consultants have the most (208), then Directors and QA Analysts (199 each) | Look at role-specific causes, not one company-wide fix |
| Distance from home | Leavers stay low up to 7 distance units, then rise steadily to 48 at 12 units | Offer remote or flexible work to employees who live far away |
| Business travel | Travel Rarely: 1,183 leavers (52.5%). Travel Frequently: 693 (30.8%). No Travel: 375 (16.7%) | Review the travel policy |
| Years in current role | Leavers peak at 5 years in the same role (235) | Plan promotions or role changes around year 5 |
| Satisfaction | Low Job Environment scores (1 to 3) cover about 30% each, against about 11% at scores 4 and 5 | Improve the work environment for low-scoring teams |
| Salary hike | Leavers are spread evenly across all hike bands (about 200 to 243 each) | Pair hikes with growth and recognition |
| Education | Graduation (703) and Degree (687) holders are the largest groups of leavers | Target early-career employees with development plans |

> Most numbers above are **counts of employees who left**, not attrition rates. A group with many leavers may also simply be a large group.

## Recommendations

1. **Start with Cyber Security, Software Development and Data Science.** They have the most leavers.
2. **Fix the work environment.** Low environment and involvement scores go with higher attrition.
3. **Make work flexible for people who live far away.** Leavers rise sharply beyond 7 distance units.
4. **Create a growth path around year 5 in a role.**
5. **Do not rely on salary hikes alone.** They do not separate who stays from who leaves.

## Tools

- **PostgreSQL / SQL:** data analysis and queries
- **Power BI:** interactive dashboard with Job Level, Job Role and Gender filters

## Repository Files

| File | Description |
|---|---|
| `HR_Attrition_dataset.csv` | Employee dataset used for the analysis |
| `HR_Attrition_Project.pbix` | Power BI dashboard (open in Power BI Desktop) |
| `HR_Attrition_Project.pdf` | Project presentation: business problem, stakeholders and dashboard |
| `README.md` | Project overview |

## About Me

**Roshan Rana** | Data Analyst

BCA from GMN College (Kurukshetra University), based in Ambala Cantt, Haryana. I use Python, SQL/PostgreSQL, Power BI, Tableau and Excel to turn raw data into decisions. I completed a Grade A Data Analytics internship at ThinkNEXT Technologies (Uber ride-sharing data) and a Data Analytics internship at InAmigos Foundation (NGO research and AI strategy). I'm looking for data analyst roles in e-commerce and finance.

[LinkedIn](https://linkedin.com/in/roshan-rana-/) · [GitHub](https://github.com/roshanranawork)

## Acknowledgment

Business brief and problem framing adapted from the HR Attrition Analytics project by Ankit Raj Mishra. Analysis, dashboard and findings are my own work.
