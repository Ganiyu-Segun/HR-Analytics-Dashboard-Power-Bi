# 📊 HR Analytics Dashboard – Power BI Mini Project

This project presents a comprehensive **Human Resources (HR) dashboard** built in Power BI using an HR Analytics dataset. It is designed to help HR professionals and stakeholders uncover patterns in **employee attrition**, **workforce demographics**, **performance**, and **engagement metrics**—all through clear, interactive visuals.

---

## 🔍 Overview

This Power BI dashboard answers key HR questions such as:
- What factors are driving attrition?
- Which departments or demographics are most affected?
- How do employee satisfaction and performance relate to compensation?
- Are training and development efforts aligned with retention goals?

Built for data-driven HR decision-making, this project showcases your ability to clean, model, analyze, and communicate insights through business intelligence tools.

---

## 📌 Key Insights

### 📈 Page 1 – Workforce Overview
- **Total Employees:** 1,470  
- **Attrition Rate:** 16.1% (Moderate turnover pressure)  
- Most employees are aged 26–41, indicating a prime working-age population.  
- **Commute Distance (7–12 km)** is a key attrition driver—suggesting lifestyle or stress factors.  
- R&D shows **gender imbalance**, while other departments are more balanced.

### 🧠 Page 2 – Exit Demographics & Sentiment
- **110 employees** have left, mostly from **Sales** and **R&D**.
- **Work-Life Balance** and **Relationship Satisfaction** both average ~3/5.
- Single/divorced employees attrit more—indicating stress or lack of workplace support.
- **Environment Satisfaction** differs slightly across departments.

### 💼 Page 3 – Performance & Retention Investment
- **Salary hike (avg: 15.1%)** and **stock options** are generally low—potential retention challenges.
- Sales team receives more **training** than R&D or HR.
- Performance correlates with pay for some roles but not all, pointing to possible compensation inconsistencies.
- R&D shows **higher salary hikes**, aligning with performance-based incentives.

---

## ⚙️ Challenges & Solutions

**Challenge**: Inconsistent column naming and numeric category codes  
✅ **Solution**: Relabeled using calculated columns (e.g., Job Level → “Entry Level,” Education → “BSc,” etc.)

**Challenge**: Raw numeric metrics lacked meaning (e.g., Satisfaction = 3.8)  
✅ **Solution**: Reframed KPIs into intuitive formats like `4.3 / 5` with helpful emojis and tooltips

**Challenge**: Toggle buttons were hard to interpret  
✅ **Solution**: Built bookmarks and selection panes with clear layer naming, plus hover tooltips for context

**Challenge**: Title space constraints for detailed visuals  
✅ **Solution**: Used compact, emoji-labeled titles and logical layout grouping

---

## 🧰 Tools & Technologies

- **Power BI Desktop**
- **DAX (for measures and calculated columns)**
- **Power Query (data cleaning & transformation)**
- **Bookmarks & Selection Pane (for interactivity)**

---

## 📁 Project Structure

```bash
📦 HR-Dashboard-Project/
├── 📄 README.md
├── 📊 HR Dashboard Summary.pdf
├── 📂 Screenshots/
│   ├── Dashboard-Page1.png
│   ├── Dashboard-Page2.png
│   └── Dashboard-Page3.png
├── 📂 Data/
│   └── HR Analytics Dataset.excel
└── ⚙️ HR_Analytics_Dashboard.pbix  # (not included in repo – available upon request)
