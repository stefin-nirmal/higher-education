# EduVision_DV: Complete Dashboard Links & Live Demonstration Guide

This document contains the official dashboard access links, deployment options, and presentation guidelines for the **EduVision_DV (Higher Education Performance Dashboard)** final project evaluation.

---

## 1. Dashboard Access & Demonstration Links

| Platform / Medium | Access Method / Path | Description | Status |
| :--- | :--- | :--- | :---: |
| **Official Tableau Public Dashboard (Primary)** | **https://public.tableau.com/app/profile/stefin.nirmal/viz/EduVision_Midnight_Royal/UniversityOverview** | Official live Tableau Public cloud deployment with all 4 interconnected dashboards. | **OFFICIAL LIVE LINK** |
| **Tableau Public - Research Analytics Tab** | https://public.tableau.com/app/profile/stefin.nirmal/viz/EduVision_Midnight_Royal/ResearchAnalytics | Direct link to Research Analytics quadrant & citation velocity. | **Active** |
| **Tableau Public - Student Analytics Tab** | https://public.tableau.com/app/profile/stefin.nirmal/viz/EduVision_Midnight_Royal/StudentAnalytics | Direct link to international diversity & faculty mentorship analytics. | **Active** |
| **Tableau Public - Country Comparison Tab** | https://public.tableau.com/app/profile/stefin.nirmal/viz/EduVision_Midnight_Royal/CountryComparison | Direct link to global choropleth map & national benchmark scoreboard. | **Active** |
| **Live Interactive Web Twin** | https://eduvision-higher-education.surge.sh | Zero-dependency high-speed web mirror of the entire suite. | **Active** |
| **Tableau Packaged Workbook (.twbx)** | `EduVision_DV.twbx` (Root / Milestone 3) | Master packaged workbook archive with embedded extract. | **Production Ready** |
| **GitHub Repository Master** | https://github.com/stefin-nirmal/higher-education | Complete 5-folder documentation and deliverable repository. | **Online** |

---

## 2. Live Presentation Demonstration Protocol

During the final presentation, use either **Tableau Desktop / Tableau Public** with `EduVision_DV.twbx` or double-click `EduVision_Dashboard.html` to demonstrate the following 5 requirements specified by the Mentor:

### A. The Complete Dashboard
* **Macro Performance Strip:** Point out the **6 Executive KPI Cards**:
  1. **#1 Global Rank:** MIT (Score: 100.0)
  2. **Total Universities:** 1,503 institutions across 42 countries
  3. **Average Overall Score:** 72.6 (+2.4 YoY)
  4. **International Students Share:** 28.7% (+1.8% YoY)
  5. **Faculty-to-Student Ratio:** 1 : 17.3 (+0.6 YoY)
  6. **Total Global Publications:** 2.45 Million (+6.3% YoY)

### B. The Interlinked Dashboards
Demonstrate how the 4 distinct views connect:
1. **University Overview Dashboard:** Executive global leaderboard, 5-year trends, and regional shares.
2. **Research Analytics Dashboard:** Research Impact vs. Productivity quadrant scatter plot and citation velocity.
3. **Student Analytics Dashboard:** Campus diversity distribution, international student mobility, and mentorship ratios.
4. **Country Comparison Dashboard:** Global choropleth map and country-level education benchmarks.

### C. Important Visualizations and Insights
* **Research Impact Quadrant:** Explain how MIT, Harvard, and Stanford occupy the top-right quadrant (High Impact + High Productivity), while specialized institutions like Caltech achieve elite impact with focused faculty size.
* **International Diversity Mobility:** Highlight that Oceania (39.5%) and Europe (33.2%) lead in global student mobility, while Asia (18.5%) retains a largely domestic student base.
* **Teaching Mentorship vs. Scale:** Demonstrate that top 20 universities maintain tight faculty ratios (< 1:8), directly correlating with academic prestige.

### D. Interactivity & Cross-Filtering Functionality
* **Filter by Year (2020–2024):** Show how historical trends dynamically shift overall scores.
* **Filter by Region:** Click any slice of the Regional Donut Chart (e.g., *Europe 37.6%*) to filter all cards and rankings.
* **Single University Selection:** Click on **MIT** or **Cambridge** in the Top 10 table—notice how the entire dashboard filters down to that specific institution’s trajectory.

### E. How Components are Connected
* Explain that the dashboards share a **unified denormalized Star Schema dataset** (`university_final_dataset.xlsx`) with identical dimension definitions.
* Tableau **Filter Actions** and **Parameter Controls** pass the selected institutional context across worksheets seamlessly without requiring page reloads or broken links.

---

## 3. Contact & Submission Details
* **Student Name:** Stefin
* **Project:** EduVision_DV Higher Education Analytics Suite
* **Submission Date:** October 2026 (Submitted Ahead of October 7 Deadline)
* **Status:** 100% Complete (Milestones 1, 2, 3, 4 + Final Project)

