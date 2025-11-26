
# 📊 HR Analytics Dashboard – Power BI

A comprehensive **HR Analytics Dashboard** built using **Power BI**, designed to help organizations monitor workforce performance, analyze employee trends, and make data-driven HR decisions with confidence.

![Hr_analysis](https://wallpaperaccess.com/full/15682437.png)

---


## 🌟 Overview

This dashboard provides an end-to-end view of essential HR metrics, empowering HR teams, managers, and leadership to:

- Track hiring, attrition, and retention patterns  
- Analyze workforce demographics and distribution  
- Evaluate departmental performance and salary trends  
- Identify areas requiring strategic HR attention  

The included `.pbit` template allows seamless integration with your own HR dataset.

---

## 🎯 Key Insights

### 👥 Workforce Composition

<img width="1310" height="729" alt="hr dash 1" src="https://github.com/user-attachments/assets/36cb2eed-a9ad-4227-9d41-57dbbeda7493" />

## 📌 Insights from the Talent Insights Hub Dashboard

- The company has **650 employees** with an **average experience of 11.7 years** and an **average salary of ~$89.78K**.
- Employees are distributed across major U.S. regions, with key locations including **Chicago, Dallas, Los Angeles, Houston, Miami, and New York**.
- The **Sales**, **Marketing**, and **IT** departments show the highest gender representation, indicating strong staffing in both commercial and technical functions.
- **Sales (107 employees)** and **Marketing (98 employees)** are the largest departments, while **HR** represents the smallest workforce group.
- Most departments contribute between **13%–16%** of the workforce, showing a relatively balanced organizational structure.


### 🧭 Department & Role Analytics

<img width="1305" height="730" alt="hr dash 2" src="https://github.com/user-attachments/assets/5aebd8bb-7b3f-481c-aeaa-2e719a0e14c5" />

## 📌 Insights from the Compensation & Salary Overview Dashboard

- The **maximum salary** in the organization is **149.87K**, while the **median salary** stands at **87.85K**, indicating a moderately wide compensation range.
- **IT** and **Marketing** departments have the **highest average salaries**, suggesting strong demand for technical and strategic roles.
- The scatter plot shows a **positive correlation between experience and salary**, with higher experience clusters linked to higher total salary sums.
- The **Decomposition Tree** highlights that salary is influenced most by factors like **department**, **designation**, **experience level**, and **education**.
- Employees with **Master’s degrees**, higher experience (e.g., 12+ years), and roles such as **Analyst** or **Associate** tend to fall in higher salary brackets.
- **HR** and **Customer Support** departments reflect comparatively lower average salaries.


### 📈 Performance & Growth

<img width="1301" height="722" alt="hr dash 3" src="https://github.com/user-attachments/assets/9c9a0713-65ad-4320-a734-6f3a7df0591a" />

## 📌 Insights from the Employee Performance & Growth Dashboard

- Employee performance distribution is relatively balanced, with the highest count in the **Below Average** category (~150 employees), followed by **Poor** and **Excellent** ratings.
- The **Average** and **Good** performance categories show slightly lower employee counts, indicating potential opportunities for performance improvement programs.
- Employees with **Excellent** ratings generally align with higher salary ranges, as shown in the matrix table.
- The dashboard allows deeper filtering by **department**, **location**, and **designation**, enabling targeted performance evaluations across different teams.
- Overall, the dataset shows diverse performance levels, supporting the need for focused talent development and performance enhancement initiatives.


### 🔁 Hiring & Attrition Insights

<img width="1306" height="734" alt="hr dash 4" src="https://github.com/user-attachments/assets/24bf10c2-4f6f-4eb0-b53b-5f35628eb1ef" />

## 📌 Insights from the Workforce Demographics & Diversity Dashboard

- The organization has a **balanced gender distribution**, with all three gender categories (Male, Female, Other) representing roughly **31–34%** each.
- **Sales, Marketing, and IT** have the highest employee counts, showing strong staffing in customer-facing and technical departments.
- **IT** leads in both **average salary (~94K)** and **average experience (~12.3 years)**, indicating a highly experienced and well-compensated workforce.
- Departments such as **HR**, **Operations**, and **Finance** show slightly lower employee counts but maintain competitive salary and experience levels.
- Employees are distributed across major cities including **Chicago, Dallas, Houston, Los Angeles, Miami, and New York**, reflecting a geographically diverse workforce.


---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| **HR Dashboard.pbit** | Power BI template containing report layouts, data model, and visual structure. |

---

## ⚙️ How to Use

1. Download the `.pbit` file from this repository.  
2. Open it using **Power BI Desktop**.  
3. Connect your HR dataset when prompted.  
4. Map your dataset to the required columns.  
5. Refresh the report to visualize your HR analytics.  
6. Customize measures, visuals, or pages based on your organizational needs.

---

## 📌 Recommended Data Structure

The dashboard works best with a dataset containing fields like:

- `Employee ID`  
- `Name` / `Gender` / `Age`  
- `Department` / `Role`  
- `Date of Joining` / `Exit Date`  
- `Salary`  
- `Performance Rating`  
- `Manager`  
- `Experience` or `Tenure`  

---

## 🧩 Customization Options

You can enhance or extend the dashboard by adding:

- Predictive attrition (Python/R in Power BI)  
- Additional DAX measures  
- Drill-through pages and custom tooltips  
- Live SQL/SharePoint/Cloud data connections  
- Role-Level Security (RLS)  
