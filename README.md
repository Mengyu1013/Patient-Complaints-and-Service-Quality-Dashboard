# Patient Complaints and Service Quality Dashboard

This repository presents a redesigned Tableau dashboard focused on analyzing patient complaints and improving service quality monitoring in healthcare.



## 📌 Overview

Originally adapted from the *Big Book of Dashboards*, this project transforms a general complaints dashboard into a purpose-driven, healthcare-context visualization. The redesign aims to:

- Improve visual clarity and color consistency
- Support interactive filtering by region and party
- Highlight prioritization insights via Pareto analysis
- Track responsiveness trends using open rate vs. volume scatter plot

## 🧩 Features

### 1. Dashboard Components
- **BANS (Big Numbers)** for complaint status overview (Open, Closed, Total)
- **Complaints by Month** bar chart to view time trends
- **Scatter Plot** showing Monthly Complaint Volume vs. Open Rate
- **Hexbin Map** visualizing open complaints across US states
- **Complaints by Reason and Status** horizontal bar chart
- **Complaints by Party** stacked bar chart for issue origin tracking
- **Pareto Chart** emphasizing key complaint types using 80/20 principle
- **Pie Chart** to show complaint source (company vs third party)

### 2. Interactivity
- Filters: Date range, complaint status (open/closed), and source type
- Click-to-filter on state map and party chart
- Dynamic tooltips and labeled insights on all visualizations

### 3. Calculated Fields & Parameters
- `Monthly Open Rate` for responsiveness tracking
- `Running Sum` and `% of Total` for Pareto analysis
- Parameterized toggle for open/closed filtering

## 🛠️ Tools Used

- **Tableau Desktop**
- Data source: Synthetic healthcare complaints dataset (CSV)
- Design principles based on data visualization best practices (e.g., Stephen Few, Cole Nussbaumer Knaflic)

## 📈 Redesign Highlights

| Before | After |
|--------|-------|
| Generic title | Clear, healthcare-focused naming |
| No prioritization insight | Added Pareto for actionable focus |
| Static charts | Enabled interactivity and filtering |
| Muted color scheme | Improved color palette and contrast |
| No contextual guidance | Added annotations, tooltips, legends |

## 📁 Files

- `Redesigned Dashboard.twbx`: Tableau packaged workbook
- `Dashboard Redesign Report.pdf`: Full documentation of the design process
- `*.png`: Screenshots of dashboard components

## ✨ Future Improvements

- Real-time data integration (e.g., live feedback feeds)
- Predictive modeling for risk detection
- Dynamic alerts and escalation flags for unresolved issues

## 📄 License

MIT License (or add your own terms)

---

Designed with care to help healthcare teams track and resolve patient complaints more effectively.
