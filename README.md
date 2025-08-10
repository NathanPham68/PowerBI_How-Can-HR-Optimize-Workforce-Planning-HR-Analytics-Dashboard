# [POWER BI] How Can HR Optimize Workforce Planning? - HR Analytics Dashboard

<img width="1360" height="600" alt="image" src="https://github.com/user-attachments/assets/a15ae8f2-0727-411e-ad5d-b94e4b40565a" />

## I. Introduction
This project is focused on creating a comprehensive HR Workforce Dashboard to help the organization track, analyze, and optimize important human resource metrics. By utilizing employee-level data, such as salary, tenure, absence, performance, and demographics, the dashboard provides insights that support evidence-based decision-making for talent management, employee engagement, and retention strategies.

I’ve developed a data analytics solution that enables HR teams to make more informed decisions when it comes to workforce planning.

👉 This tailored solution equips HR professionals and managers with the tools they need to make data-driven decisions in areas like workforce planning, employee engagement, and talent management strategies.

## II. Design Thinking Method

![image](https://github.com/user-attachments/assets/2dbcf783-46f6-4f09-8bb4-318f936548d9)

![image](https://github.com/user-attachments/assets/3bc52c66-a2e8-423f-872e-000172a6a54f)

![image](https://github.com/user-attachments/assets/91ee742e-4c35-4640-93fb-0d9c807ac641)

![image](https://github.com/user-attachments/assets/1cc13515-2cb6-47d6-8231-4a3b5687176f)

![image](https://github.com/user-attachments/assets/2c084fbc-957a-4c11-821d-6d55ae3ce3db)

![image](https://github.com/user-attachments/assets/9d520bef-8058-453a-8f21-84ce3a90fb86)

## III. Visualization
### 1. Entity Relationship Diagram Model

![image](https://github.com/user-attachments/assets/bf02adf8-835c-48ec-a2ec-c6a2de41b207)

### 2. Executive Summary

<img width="1400" height="826" alt="image" src="https://github.com/user-attachments/assets/93bdf45b-be10-4536-b024-86db79a14cd8" />

* Total Workforce: 311 employees with total salary expenses of $21M.

* Turnover Rate: 33.44%, a relatively high figure indicating potential retention issues.

* Average Tenure: 12.31 years, suggesting long-term employee stability for certain roles.

* Absence Rate: Low at 0.23%, indicating consistent attendance.

* Satisfaction Score: 3.89 out of 5, showing moderate employee contentment.

* Average Age: 46.5 years, pointing to a mature workforce.

* Age Distribution: Majority are aged 35–44 (139 employees), followed by 45–54 (92 employees). Very few in the 25–34 group, signaling limited young talent inflow.

* Gender Distribution: Slightly more females (56.59%) than males (43.41%).

* Turnover by Department: Highest in Production (39.71%) and Admin Offices (30%), lowest in Sales (16.13%).

* Departure Reasons: Top three – “Another position” (20 cases), “Unhappy” (14 cases), and “More money” (11 cases).

### 3. Workforce Database

<img width="1400" height="826" alt="image" src="https://github.com/user-attachments/assets/bda10a4f-8b7c-4114-88bc-fff87a95722d" />

| **Field** | **Style** |
|--------------|-------------|
| **Satisfaction score** | - If 0 <= value <= 3 then ❎<br> - If 3 < value <= 4 then ❗<br> - If 4 < value <= 5 then ✅ |
| **Retention Risk** | - If value is High then ❎<br> - If value is Medium then ❗<br> - If value is Low then ✅ |

* High Earners: Top salaries belong to executives and IT leaders, with Janet King (President & CEO) earning $250,000.

* Retention Risk: Most employees have low retention risk, but a few — such as Peter Monroe (IT Manager) — have a high risk due to low satisfaction and “Needs Improvement” performance.

* Satisfaction Trends: Scores range from 3.0 to 5.0. Low scores are often paired with medium-to-high retention risks.

* Recruitment Sources Impact: Certain recruitment channels (e.g., Employee Referral, Indeed) are linked to both high and low satisfaction outcomes, indicating that hiring source alone is not a guarantee of engagement.

* Employment Status: Includes a mix of active employees, voluntary terminations, and terminations for cause — suggesting the need for consistent retention monitoring.

## IV. Insights & Recommendations

| **Metrics** | **Insight** | **Recommendation** |
|--------------|-------------|--------------------|
| **1. Employee Turnover Risk** | - Length of service appears to have a strong correlation with job satisfaction and retention. Employees in the 1–3 year range are more likely to leave compared to long-tenured staff. | - Implement stay interviews to capture employee concerns before they resign.<br> - Introduce career pathing programs and ensure every employee has a clear 12–18 month development plan.<br> |
| **2. Performance Distribution** | - While top performers are present in all departments, there is a concentration of lower performance ratings in roles with less training investment.<br> - Performance gaps often align with inadequate onboarding and skills development programs. | - Increase investment in role-specific training, particularly for underperforming groups.<br> - Launch peer mentorship programs to transfer skills from high performers to less experienced staff. |
| **3. Compensation & Benefits Alignment** | - Benefits usage data indicates employees are either unaware of certain offerings or find them misaligned with their real needs. | - Adjust salary bands annually based on market trends and performance contribution.<br> - Review benefits packages to align with employee needs (e.g., flexible working, mental health support). |
| **4. Leadership & Engagement** | - Employee satisfaction is significantly higher in departments with visible, communicative leadership.<br> - Lack of regular feedback loops is a recurring issue, especially in larger teams where employees feel disconnected from decision-making. | - Increase skip-level meetings where senior leaders interact directly with employees.<br> - Foster a culture of continuous feedback using quick pulse surveys and regular check-ins. |



