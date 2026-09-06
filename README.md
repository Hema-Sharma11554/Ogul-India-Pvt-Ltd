Ogul India Pvt Ltd - HR Attrition & Retention Analytics | Power BI

# Ogul India Pvt Ltd - HR Attrition & Retention Analytics | Power BI

## 📊 Dashboard Walkthrough

### 1. KPI Overview - Corrected (19% | 38 Left | ₹4.38 Cr Loss)
<img width="1059" height="110" alt="KPI" src="https://github.com/user-attachments/assets/e40c2817-09de-4a5c-9401-a7647e85f773" />

### 2. Reasons for Leaving
<img width="977" height="317" alt="Reason for Leaving" src="https://github.com/user-attachments/assets/2067092f-4bb2-4922-adb9-a2693ae0e0af" />

### 3. Average Salary Analysis
<img width="775" height="456" alt="Avg salary for leaving" src="https://github.com/user-attachments/assets/1b36cfdb-98a9-4ca5-9f06-6f080619bd9b" />

### 4. Full Dashboard View
<img width="936" height="527" alt="Dash1" src="https://github.com/user-attachments/assets/2c60a20e-0933-43f2-99fc-77fb203acfc2" />

### 5. Attrition by Department & Salary Loss (Corrected)
<img width="1059" height="596" alt="Attrition Overview Corrected" src="PASTE_YOUR_NEW_LINK_HERE" />

### 6. Forecast & Action Needed
<img width="936" height="527" alt="Action Needed" src="PASTE_YOUR_NEW_LINK_HERE" />

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge)
![People Analytics](https://img.shields.io/badge/People%20Analytics-0F2C3E?style=for-the-badge)

📌 Project Overview
An end-to-end People Analytics project built to diagnose **why employees are leaving Ogul India Pvt Ltd in 2025-26
and to predict who is at risk of leaving next. The dashboard moves beyond reporting attrition % to quantifying business 
impact and providing actionable retention lists.

> Live Dashboard PDF: [View Full PDF](Ogul india pvt ltd1.pdf)

---

🎯 Key Business KPIs 

| Metric | Value |
| Total Employees | 200 |
| Employees LEFT  | 38 |
| Active Employees | 162 |
| Attrition % | 19% |
| Salary Loss in 2025-26 | ₹4.38 Cr |
| Avg Salary Left | ₹11.5L |
| Avg Tenure Left | 2 Years |
| High Risk Active Count | 10 |

🔍 Key Insights & Storytelling

1. Why People Leave:
- Work Culture: 39.5% (15) - #1 driver
- Work-Life Balance: 26.3% (10)
- Better Salary: 18.4% (7)
- **Insight:** Culture + WLB alone = 65.8% of all exits. Not just compensation.

2. Early Attrition Crisis:
- 93.33% attrition in 0-1 Year tenure bucket.
- New hires are leaving before becoming productive.

3. Overtime = Burnout:
- Employees with 16-30 hrs overtime have higher attrition than 0-5 hrs group.
- Indicates burnout risk is not tracked.

4. Department Impact:
- Human Resources: ₹1.2 Cr loss (Highest)
- Sales: ₹1.0 Cr loss
- Engineering: ₹0.9 Cr loss

5. Predictive Risk Model:**
Built Attrition Risk Priority Score using Overtime, Job Satisfaction (1-2), Tenure <3 Yrs, No Promotion, Distance. Flagged **10 active employees** currently at High Risk.

---
 📊 Dashboard Walkthrough

 1. Attrition Overview - Corrected KPIs
![Attrition Overview](readme_assets/Attrition_Overview_Corrected.png)

2. Attrition by Tenure, Gender, Marital Status, Department
![Page 2](readme_assets/page_2.png)
![Page 3](readme_assets/page_3.png)

3. Workforce, Salary & Performance Analysis
![Page 4](readme_assets/page_4.png)
![Page 5](readme_assets/page_5.png)
![Page 6](readme_assets/page_6.png)

4. Forecast & Drivers - Distance, Overtime, Age Group
![Page 7](readme_assets/page_7.png)
![Page 8](readme_assets/page_8.png)

5. Storytelling - Why People Leave & Action Needed
![Page 9](readme_assets/page_9.png)
![Page 10](readme_assets/page_10.png)

---

🛠️ Tech Stack
- Tool:Power BI Desktop
- Data Prep: Power Query (Data Cleaning, Merging)
- Modeling: DAX Measures - Attrition %, Avg Tenure Left, Salary Loss, Risk Score
- Visuals: Donut, Bar, Stacked, KPI Cards, Matrix

Key DAX Measures Used:
```DAX
Attrition % = DIVIDE([Employees LEFT], [Total Employees])
Avg Salary Left = AVERAGE(Leavers[Salary])
Salary Loss = SUMX(Leavers, Leavers[Salary])
High Risk Active = COUNTROWS(FILTER(Active, [Risk Score] > 7))
Avg Tenure Left = AVERAGE(Leavers[Tenure])
```

---
💡 Business Recommendations

1.  Fix 0-1 Year Onboarding: 93.33% early attrition indicates onboarding & expectation mismatch. Introduce 30-60-90 day check-ins.
2.  Culture Audit:Work Culture is #1 reason. Conduct anonymous pulse surveys for HR, Sales, Engineering.
3.  Overtime Cap: Cap overtime at 15 hrs/month. Hire support for 16-30 hrs group.
4.  Proactive Retention: Immediate 1:1 with 10 High-Risk flagged employees. Offer growth plan & WLB support.
5.  Sales & HR Focus: These 2 depts = 50% of salary loss. Create retention bonus.

---

📁 Files in this Repo
- `Ogul_India_Pvt_Ltd.pdf` - Original Dashboard Export
- `Attrition Overview.png` - KPI Screenshot
- `/readme_assets` - All dashboard screenshots

---

👩‍💻 Author
Hema Sharma | Data Analyst | HR Analytics | Power BI

- LinkedIn: https://www.linkedin.com/in/hemlataa-sharrma/
- Portfolio: [Add Portfolio URL]

⭐ If you found this useful, please give a star to the repo!
