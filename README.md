# HR-attrition-analysis
HR Attrition Dashboard developed in Power BI to analyze employee turnover trends, workforce demographics, department-wise attrition, job role impact, salary insights, and employee retention patterns. Includes interactive filters and KPI tracking to support data-driven HR decision-making and workforce planning

## Project Overview

This project is an interactive *HR Attrition Analysis Dashboard* built in Microsoft Excel to analyze employee attrition patterns across different workforce dimensions. The objective of this project was to help HR management understand why employees are leaving, which departments and job roles have higher attrition, and what workforce factors may be connected with employee turnover.

The project was developed using raw HR employee data, Pivot Tables, Pivot Charts, slicers, KPI cards, and dashboard visuals. The final dashboard gives a complete overview of employee attrition by gender, department, education field, job role, age group, training times, performance rating, average salary, and average salary hike. This dashboard is designed from a business analyst perspective, where the focus is not only on showing numbers but also on identifying workforce risk areas and recommending practical HR solutions.

---

## Dataset Overview

The dataset contains employee-level HR records with demographic, job-related, compensation, performance, training, and attrition information.

Main fields used in the analysis:

- Employee Number

- Attrition

- Department

- Gender

- Age

- Age Band

- Education Field

- Job Role

- Marital Status

- Business Travel

- Over Time

- Training Times Last Year

- Performance Rating

- Monthly Income

- Percent Salary Hike

- Job Satisfaction

- Environment Satisfaction

- Work Life Balance

- Years at Company

- Years in Current Role

- Years Since Last Promotion

- Years With Current Manager

---
## Dashboard Preview

![HR Attrition Dashboard](dashboard/HR-ATDA.png)

---


## Key Performance Indicators

The dashboard includes the following main HR KPIs:

| KPI | Value |
|---|---:|
| Total Employees | 1,470 |
| Active Employees | 1,233 |
| Attrition Employees | 237 |
| Attrition Rate | 16.12% |
| Average Age | 36.92 years |
| Average Monthly Income | 6,502.93 |
| Average Percent Salary Hike | 15.21% |

These KPIs provide a quick executive-level view of workforce stability and employee retention performance.

---


The Excel workbook contains multiple sheets for data analysis and dashboard building.

### 1. DataSet Sheet

The DataSet sheet contains the main employee-level HR dataset. This sheet was used as the base data source for all Pivot Tables and dashboard visuals.

### 2. Pivot Sheet

The Pivot sheet contains high-level HR summaries such as:

- Total employee count

- Attrition count

- Active employee count

- Average age

- Attrition rate

- Gender-based employee count

- Education-based attrition

### 3. Pivot 2 Sheet

The Pivot 2 sheet focuses on age-based attrition analysis. It summarizes attrition across age groups such as:

- 18–27

- 28–37

- 38–47

- 48–57

- 58–67

### 4. MY PIVOT Sheet

The MY PIVOT sheet contains additional Pivot Table calculations used to support the dashboard KPI cards and visual analysis.

### 5. Dashboard Sheet

The dashboard sheet presents the final interactive HR Attrition Dashboard with slicers, KPI cards, charts, and business-focused visuals.

---

## Dashboard Features

### Executive KPI Cards

The dashboard includes top-level KPI cards for:

- Total Employee

- Attrition

- Active Employee

- Attrition Rate

- Average Age

- Average Salary Hike

These KPI cards make it easy for HR managers to quickly understand the overall workforce condition.

---

### Attrition by Gender

Gender-based attrition was visualized using a donut chart.

| Gender | Attrition Count | Share of Attrition |
|---|---:|---:|
| Male | 150 | 63% |
| Female | 87 | 37% |

Male employees show a higher attrition count than female employees. However, since the organization also has more male employees overall, HR should compare both count and attrition rate before making a final decision.

---

### Department-Wise Attrition

Department-wise attrition was analyzed to identify which business areas are facing higher employee turnover.

| Department | Attrition Count | Total Employees | Attrition Rate |
|---|---:|---:|---:|
| R&D | 133 | 961 | 13.8% |
| Sales | 92 | 446 | 20.6% |
| HR | 12 | 63 | 19.0% |

R&D has the highest number of employees leaving, but Sales has the highest attrition rate among the major departments. This means Sales is a critical retention risk area.

---

### Education-Based Attrition

Education field analysis was used to understand which academic backgrounds have higher employee attrition.

| Education Field | Attrition Count | Attrition Rate |
|---|---:|---:|
| Life Sciences | 89 | 14.7% |
| Medical | 63 | 13.6% |
| Marketing | 35 | 22.0% |
| Technical Degree | 32 | 24.2% |
| Other | 11 | 13.4% |
| Human Resources | 7 | 25.9% |

Life Sciences has the highest attrition count, but Human Resources and Technical Degree employees have higher attrition rates. This shows that HR should look beyond only the highest count and also focus on proportional risk.

---

### Attrition by Job Role

Job role analysis helps identify which roles are losing employees most frequently.

| Job Role | Attrition Count | Attrition Rate |
|---|---:|---:|
| Laboratory Technician | 62 | 23.9% |
| Sales Executive | 57 | 17.5% |
| Research Scientist | 47 | 16.1% |
| Sales Representative | 33 | 39.8% |
| Human Resources | 12 | 23.1% |
| Manufacturing Director | 10 | 6.9% |
| Healthcare Representative | 9 | 6.9% |
| Manager | 5 | 4.9% |
| Research Director | 2 | 2.5% |

Sales Representative has the highest attrition rate, while Laboratory Technician has the highest attrition count. These two roles should be treated as priority areas for HR retention planning.

---

### Attrition by Age Group

Age-group analysis was used to identify which employee groups are more likely to leave.

| Age Group | Attrition Count | Attrition Rate |
|---|---:|---:|
| Under 25 | 38 | 39.2% |
| 25–34 | 112 | 20.2% |
| 35–44 | 51 | 10.1% |
| 45–54 | 25 | 10.2% |
| Over 55 | 11 | 15.9% |

The highest attrition count comes from employees aged 25–34, while the highest attrition rate is among employees under 25. This indicates that younger employees are more likely to leave the organization.

---

### Attrition by Training Times Last Year

Training frequency was analyzed to understand whether employee development has any relationship with attrition.

| Training Times Last Year | Attrition Count | Attrition Rate |
|---|---:|---:|
| 0 | 15 | 27.8% |
| 1 | 9 | 12.7% |
| 2 | 98 | 17.9% |
| 3 | 69 | 14.1% |
| 4 | 26 | 21.1% |
| 5 | 14 | 11.8% |
| 6 | 6 | 9.2% |

Employees with no training show a high attrition rate. Employees with higher training exposure, especially 5–6 training sessions, show lower attrition. This suggests that learning and development may support retention.

---

### Attrition by Performance Rating

Performance rating was analyzed to see whether high-performing employees are leaving more often.

| Performance Rating | Attrition Count | Attrition Rate |
|---|---:|---:|
| Rating 3 | 200 | 16.1% |
| Rating 4 | 37 | 16.4% |

The attrition rate is almost similar between performance rating 3 and 4. This means attrition is not only a performance issue; it may be more connected with job role, department, age, salary, overtime, work-life balance, or career growth.

---

### Average Salary by Department

Average salary was compared across departments.

| Department | Average Monthly Income |
|---|---:|
| HR | 6,654.51 |
| R&D | 6,281.25 |
| Sales | 6,959.17 |

Sales has the highest average monthly income but still has a high attrition rate. This shows that salary alone may not be enough to retain employees in Sales.

---

## Additional Business Insights

### Overtime and Attrition

Overtime has a strong relationship with attrition.

| Overtime | Attrition Count | Attrition Rate |
|---|---:|---:|
| Yes | 127 | 30.5% |
| No | 110 | 10.4% |

Employees who work overtime are almost three times more likely to leave than employees who do not work overtime. This is one of the strongest risk indicators in the dataset.

---

### Marital Status and Attrition

| Marital Status | Attrition Count | Attrition Rate |
|---|---:|---:|
| Single | 120 | 25.5% |
| Married | 84 | 12.5% |
| Divorced | 33 | 10.1% |

Single employees have the highest attrition rate. This may indicate higher career mobility, lower family responsibility, or greater willingness to change jobs.

---

### Business Travel and Attrition

| Business Travel | Attrition Count | Attrition Rate |
|---|---:|---:|
| Travel Frequently | 69 | 24.9% |
| Travel Rarely | 156 | 15.0% |
| Non-Travel | 12 | 8.0% |

Employees who travel frequently have higher attrition. Travel workload may be affecting work-life balance and employee satisfaction.

---

### Job Satisfaction and Attrition

Employees with the lowest job satisfaction level have the highest attrition risk.
| Job Satisfaction | Attrition Count | Attrition Rate |
|---|---:|---:|
| 1 | 65 | 23.2% |
| 2 | 54 | 14.4% |
| 3 | 62 | 14.4% |
| 4 | 56 | 14.5% |

Low job satisfaction is a major warning sign for employee turnover.

---

### Work-Life Balance and Attrition

| Work-Life Balance | Attrition Count | Attrition Rate |
|---|---:|---:|
| 1 | 25 | 31.2% |
| 2 | 58 | 16.9% |
| 3 | 127 | 14.2% |
| 4 | 27 | 17.6% |

Employees with poor work-life balance have the highest attrition rate. This supports the overtime and frequent travel findings.

---

### Job Level and Attrition

| Job Level | Attrition Count | Attrition Rate |
|---|---:|---:|
| Level 1 | 143 | 26.3% |
| Level 2 | 52 | 9.7% |
| Level 3 | 32 | 14.7% |
| Level 4 | 5 | 4.7% |
| Level 5 | 5 | 7.2% |

Entry-level employees have the highest attrition risk. This suggests that early-career employees may need stronger onboarding, mentoring, career planning, and growth opportunities.

---

## Business Problems Identified and Business Solutions

### Problem 1: Sales Department Has a High Attrition Rate

The Sales department has a 20.6% attrition rate, which is higher than R&D. Sales roles often involve pressure, targets, customer handling, and performance expectations.

### Business Solution

The company should improve Sales retention by reviewing sales targets, commission structure, workload, manager support, and career progression. Sales employees should receive structured coaching, realistic targets, and performance-based incentives.

---

### Problem 2: Sales Representative Role Has the Highest Attrition Rate

Sales Representatives have a 39.8% attrition rate, which is the highest among all job roles. This indicates a serious retention risk in frontline sales roles.

### Business Solution

HR should conduct exit interviews for Sales Representatives, review compensation and incentive plans, provide better onboarding, and create a clear promotion path from Sales Representative to Sales Executive.

---

### Problem 3: Laboratory Technicians Have the Highest Attrition Count

Laboratory Technicians recorded 62 attrition cases, the highest among all job roles. This creates operational risk because frequent replacement may affect productivity and training costs.

### Business Solution

The company should investigate workload, job satisfaction, supervisor relationship, and career development opportunities for Laboratory Technicians. Retention bonuses, skill development programs, and internal promotion opportunities may reduce turnover.

---

### Problem 4: Younger Employees Are Leaving More Frequently

Employees under 25 have the highest attrition rate, and employees aged 25–34 have the highest attrition count. This shows a clear early-career retention issue.

### Business Solution

The company should introduce graduate development programs, mentorship, learning paths, internal mobility, and fast-track career progression for young employees.

---

### Problem 5: Overtime Is Strongly Connected with Attrition

Employees working overtime have a 30.5% attrition rate, compared with 10.4% for employees who do not work overtime.

### Business Solution

Management should monitor overtime workload, redistribute tasks, improve staffing levels, and encourage better work-life balance. Overtime should be tracked as an early warning signal for attrition risk.

---

### Problem 6: Employees with Poor Work-Life Balance Are More Likely to Leave

Employees with the lowest work-life balance score show a 31.2% attrition rate.

### Business Solution

HR should introduce flexible scheduling, workload review, wellness programs, and manager training to reduce burnout and improve employee satisfaction.

---

### Problem 7: Frequent Business Travel Increases Attrition Risk

Employees who travel frequently show a 24.9% attrition rate.

### Business Solution

The company should review travel policies, offer travel allowances, rotate travel responsibilities, and provide remote meeting alternatives where possible.

---

### Problem 8: Employees with No Training Have High Attrition

Employees who received no training had a 27.8% attrition rate.

### Business Solution

HR should ensure every employee receives structured training each year. Training should be linked with career development, promotion readiness, and employee engagement.

---

### Problem 9: Salary Alone Does Not Reduce Attrition

Sales has the highest average monthly income, but also a high attrition rate. This means compensation is not the only reason employees leave.

### Business Solution

The company should focus on non-salary factors such as workload, leadership quality, career growth, recognition, job satisfaction, and work-life balance.

---

### Problem 10: Entry-Level Employees Have High Attrition

Job Level 1 employees have a 26.3% attrition rate, showing that entry-level employees are more likely to leave.

### Business Solution

The company should improve onboarding, create role clarity, provide training, assign mentors, and build a clear career growth roadmap for entry-level employees.

---

## Key Business Recommendations

- Build a retention strategy for Sales Representatives and Laboratory Technicians.

- Track overtime as an attrition risk indicator.

- Improve work-life balance through workload planning.

- Create training programs for employees with low training exposure.

- Develop mentorship and career growth plans for young employees.

- Conduct department-specific exit interviews.

- Improve Sales department compensation and incentive structure.

- Monitor frequent travelers and reduce unnecessary business travel.

- Create early-warning HR dashboards using overtime, job satisfaction, training, and age group.

- Use employee engagement surveys to identify hidden dissatisfaction.

---

## Tools Used

- Microsoft Excel

- Pivot Tables

- Pivot Charts

- Slicers

- KPI Cards

- Donut Chart

- Bar Chart

- Pie Chart

- Tree Map

- Line Chart

- Conditional Formatting

- Dashboard Design

- Data Cleaning

- HR Analytics

- Business Analysis

---

## Excel Techniques Applied

### Data Cleaning

The raw HR dataset was organized and structured to make it suitable for analysis. Employee-level records were cleaned and prepared for Pivot Table reporting.

### Pivot Table Analysis

Pivot Tables were used to summarize attrition by department, gender, job role, education field, age group, training frequency, and performance rating.

### KPI Development

Key HR metrics were calculated and displayed as dashboard cards, including total employees, active employees, attrition count, attrition rate, average age, and average salary hike.

### Interactive Dashboard Design

Slicers were added to make the dashboard interactive. Users can filter the dashboard by:

- Training Times Last Year

- Performance Rating

- Department

### Visual Analytics

Multiple visuals were used to make the analysis easy to understand:

- Donut chart for gender attrition

- Bar chart for education-based attrition

- Column chart for job role attrition

- Pie chart for department-wise attrition

- Tree map for age-group attrition

- Line chart for average salary comparison

---

## Business Value of This Project

This dashboard helps HR management:

- Understand overall attrition performance

- Identify high-risk departments and job roles

- Track employee turnover by demographic groups

- Analyze training and performance factors

- Evaluate salary and attrition patterns

- Improve employee retention strategies

- Reduce hiring and replacement costs

- Support data-driven HR decision-making

---

## Recruiter-Focused Project Highlights

This project demonstrates my ability to:

- Build an interactive Excel dashboard from raw HR data

- Create Pivot Tables and Pivot Charts

- Develop KPI cards for executive reporting

- Analyze employee attrition patterns

- Identify business problems from HR data

- Recommend practical retention strategies

- Communicate insights clearly for business decision-making

- Apply business analyst thinking to real-world HR challenges

---


## Conclusion

The HR Attrition Analysis Dashboard provides a complete view of workforce attrition and employee retention risk. The analysis shows that attrition is not caused by one single factor. Instead, it is connected with job role, department, age group, overtime, training, business travel, job satisfaction, and work-life balance.

Through this project, I used Excel-based business intelligence techniques to transform raw HR data into meaningful insights and actionable business recommendations. This project demonstrates practical HR analytics, dashboard development, and business problem-solving skills.
