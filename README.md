# HR-Attrition-Analytics
A data analysis project on the cause of attrition rates on a HR Dataset
# HR Attrition Analysis: What Drives Employee Turnover?

I put together this project to dive into employee retention and figure out what factors actually drive people to leave a company. Using IBM’s HR Analytics dataset, I used Excel to clean the data and transform key fields, then built Pivot Tables to analyze patterns across department roles, travel requirements, overtime, and age demographics.

---

## Key Takeaways

- **Overtime is the biggest red flag:** Staff working overtime quit at **30.5%**, compared to just **10.4%** for those who don't.
- **Travel takes a toll:** Employees who travel frequently have a **24.9%** attrition rate, versus **8.0%** for non-travelers.
- **Younger staff leave faster:** The 18–27 age bracket sees the highest turnover at **28.1%**, while the 38–47 group stays steady at **9.4%**.
- **Sales faces the highest churn:** Sales leads overall departmental attrition (~20.6%), followed closely by HR (~19%) and R&D (~13.8%).

---

## How I Built It

- **Data Wrangling (Excel):** Used standard `=IF()` logic to convert text indicators (`Yes`/`No`) into binary numeric values (`1`/`0`) so I could calculate exact turnover percentages.
- **Pivot Tables:** Summarized employee counts, exit counts, and relative attrition rates across different operational slices.
- **Data Visualization (Datawrapper):** Cleaned up the raw numbers into focused bar charts to clearly communicate takeaways.

---

## Visual Breakdown

### Overtime vs. Turnover
Burnout is real—working extra hours nearly triples the likelihood of an employee walking out the door.

<img width="2760" height="892" alt="RZurZ-working-overtime-increased-attrition-" src="https://github.com/user-attachments/assets/2cf05b08-b525-4284-b66b-404c17a628f8" />


### The Cost of Frequent Travel
Constantly being on the road correlates directly with higher turnover rates.

<img width="2760" height="1044" alt="RZurZ-frequent-business-travels-increased-attrition-" src="https://github.com/user-attachments/assets/766307bf-baa7-4e99-915e-c32c7c3d5316" />


### Turnover Across Age Groups
Early-career professionals are much more mobile. Retention stabilizes significantly as employees reach their late 30s.

<img width="2760" height="1348" alt="RZurZ-younger-age-groups-have-higher-attrition-rates-" src="https://github.com/user-attachments/assets/c7711743-59b3-40dc-8020-dbe6f5704f86" />


### Departmental Overview
Sales leads the organization in percentage of departures, highlighting a potential need for better support or compensation structures in that unit.

<img width="1380" height="522" alt="RZurZ-attrition-rate-by-department-" src="https://github.com/user-attachments/assets/1a9a0015-8c61-4520-b8c3-01e81f3caa80" />


---

## Actionable Recommendations

1. **Re-evaluate Overtime Allocation:** Audit workloads in high-intensity teams to reduce employee burnout.
2. **Target Early-Career Retention:** Build structured career paths and mentorship opportunities specifically for team members under 30.
3. **Flexible Travel Policies:** Reassess travel requirements for high-travel roles and explore remote or hybrid alternatives where possible.
