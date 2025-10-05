# 🎬 Excel Movie Analytics Dashboard – From Raw Data to Actionable Insights  


## 💭 Why I Chose This Dataset
With the rise of OTT platforms like Netflix, Prime Video, and Disney+, I became curious about how the **movie industry trends have evolved globally**.  
I wanted to explore:
- Which **genres** perform the best?  
- Which **countries** dominate box office revenue?  
- How do **budgets, revenues, and ROI** differ across time periods?  

I didn’t start this project as a business case — it was driven purely by **curiosity** and a desire to improve my Excel analytics and dashboarding skills.

---

## ⚔️ Struggles I Faced
One of the biggest challenges was managing **slicers** effectively.  
I wanted some charts to respond to filters while keeping others static — finding that balance took a lot of trial and error.  
I also faced issues with ROI calculations when some movies had **missing or zero budgets**, which caused errors.  
To fix that, I used an error-handling formula and formatted the output properly.

Designing the dashboard layout was another challenge — I experimented with different chart types, colors, and placements to ensure it remained **clear and visually consistent**.

---

## 💼 Business Problem
Without a centralized dashboard, it’s difficult for studios or analysts to:
- Identify **top-performing movies, genres, and countries**.  
- Understand **ROI and critic rating trends** over time.  
- Compare **budget vs. revenue** to assess investment efficiency.  

This dashboard bridges that gap by providing a clear, visual summary of global movie trends.

## 🎯 Project Objective
- Clean and transform raw movie data into a usable format.  
- Analyze **revenue**, **ROI**, and **ratings** across countries, genres, and decades.  
- Create a **fully interactive Excel dashboard** with slicers and KPIs for quick insights.  
- Highlight actionable trends for potential investment or production strategy decisions.

---

**Explore Full Project:** [Download Excel Dashboard](https://drive.google.com/drive/folders/10SxyeZv0Z1VXf1tFwHx7nR9FtLJmwWnT?usp=drive_link)

---

## 1) Dashboard Overview (Preview)
![Dashboard Screenshot](https://github.com/lubhanigola/Excel-Projects/raw/main/Watch%20Now/Watch%20Now%20Dashboard.png)

---

## ⚙️ Techniques & Features Used

### 🧮 Excel Formulas
| Purpose | Formula Used |
|----------|---------------|
| **Extract Month Name** | `=TEXT(Dataset!$G2,"mmm")` |
| **Create Quarter Number** | `=ROUNDUP(MONTH(G2)/3,0)` |
| **Calculate ROI** | `=(Revenue - Budget)/Budget` |

### 📊 Pivot Tables & Charts
- Pivot Tables for **Revenue, ROI, IMDb Ratings, and Countries**.  
- Pivot Charts for:
  - ROI by Genre  
  - Budget vs Revenue  
  - Average Ratings by Decade  
- KPI Cards summarizing:
  - Top Movie  
  - Top Country  
  - Average ROI  
  - Average Ratings  

### 🎛️ Dashboard Design
- Used **Slicers** for Genre, Country, and Year to make it interactive.  
- Maintained a **minimalistic layout** for clarity and storytelling.

---

## 🔍 Key Insights
- 🇨🇦 **Canada** had the highest total box office collection (~$192M).  
- 🎬 *“Media Everyone”* recorded the top revenue (~$501M).  
- 📈 Clear **decade-wise shifts** in ROI and critic ratings were observed.  
- 🎭 Certain genres showed **consistently high ROI**, indicating strong audience demand.  
- 💰 Budget vs Revenue analysis revealed several underdog movies achieving unexpectedly high returns.

---

## 🧠 Learnings & Takeaways
- Improved my **data cleaning and transformation** skills directly in Excel.  
- Understood how **slicers and pivot connections** impact dashboards.  
- Learned to tell a **data story** using simple visuals and formulas.  
- Realized that curiosity-driven projects often teach more than structured assignments.  
---
