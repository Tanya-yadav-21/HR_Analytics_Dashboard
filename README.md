# 📊 HR Analytics Dashboard – Excel Project  

## 📌 Project Overview  
This project analyzes HR data to track employee attrition, salary trends, performance, and at-risk employees. A dynamic **Excel Dashboard** was built using PivotTables, Charts, and Slicers for quick insights.  

## 🎯 Objectives  
- Measure **attrition rate** (overall & by department, gender, tenure).  
- Compare **salary distribution** by job role.  
- Identify **at-risk employees** based on AtRiskScore & AtRiskFlag.  
- Analyze **performance rating vs attrition** trends.  
- Provide an **interactive dashboard** for HR decision-making.  

---

## 🗂 Dataset  
- File: `HR_Analytics_Dataset.xlsx`  
- Records: ~200 employees  
- Key Fields:  
  - `Department`, `JobRole`, `Gender`  
  - `Salary`, `PerformanceRating`, `ExperienceYears`  
  - `Attrition` (Yes/No), `AtRiskScore`, `AtRiskFlag`  


## 🛠️ Tools Used  
- **Microsoft Excel**  
  - PivotTables  
  - Donut, Bar, Column, Stacked Charts  
  - Slicers for Department, Gender, Job Role, Education, PerformanceRating  

---

## 📊 Dashboard Components  
1. **Attrition Summary** → Donut Chart  
2. **Attrition by Department** → Bar Chart  
3. **Salary by Job Role** → Horizontal Bar Chart  
4. **Attrition by Tenure Band (0–2 yrs, 2–5 yrs, etc.)** → Column Chart  
5. **Performance vs Attrition** → 100% Stacked Column  
6. **At-Risk Employees** → Column Chart  
7. **Attrition by Gender** → Donut Chart    
                                                                                                                                                                 ## 📈 Key Insights  
- Higher attrition in **0–2 yrs tenure** group.  
- **Sales & Technical departments** face the most attrition.  
- **Low performance ratings** strongly linked to attrition.  
- Around **15% employees marked at-risk**.  
- Salary gaps visible across job roles.  

---


Dashborad Structure 
---------------------------------------------------------
[ KPI Cards: Headcount | Attrition %]
---------------------------------------------------------
[ Attrition Summary Pie ]    [ Attrition by Dept Bar ]
[ Attrition by Gender Pie ]  [ Performance vs Attrition Column ]
---------------------------------------------------------
[ Headcount by Dept ]   [ Salary by Job Role ]
[ Experience Distribution ]  [ Attrition by Tenure Band ]
---------------------------------------------------------
[ Slicers: Dept | Job Role | Gender | Education | Marital Status ]
