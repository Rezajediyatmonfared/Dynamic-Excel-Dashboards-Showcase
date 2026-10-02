# 🛠️ ACRUX After-Sales Service & Support Intelligence Dashboard

## 📌 Executive Summary
The **ACRUX After-Sales Intelligence Dashboard** is an enterprise-grade Business Intelligence (BI) solution built entirely within Microsoft Excel. Designed to provide 360-degree visibility into post-sales operations, this tool enables management to transition from reactive troubleshooting to proactive data-driven decision-making. 

By centralizing data on client behavior, defect categorization, software performance, and temporal trends, this dashboard serves as the single source of truth for the service department’s operational performance.

---

## 🏗️ Dashboard Architecture & Navigation
The dashboard utilizes a **Hub-and-Spoke Navigation Model**, allowing users to navigate seamlessly between specialized analytical modules. The UI is designed with a high-contrast dark-slate theme and intuitive navigation cards to ensure clean UX and minimal cognitive load for stakeholders.

### Navigation Hierarchy:
1. **Client & Visitor Analytics:** High-level overview of service center traffic.
2. **Defect Categorization Matrix:** Macro-level breakdown of service domains.
3. **Software Defect Deep-Dive:** Micro-level granular analysis of technical bugs.
4. **Temporal Trend Analysis:** Seasonal and monthly performance tracking.

---

## 📊 Module Breakdown & Analytical Insights

### 1. Client & Visitor Analytics
*Focus: CRM and Loyalty Tracking*
*   **KPI Tracking:** Monitors **Total Visits (58)**, **Monthly Average (5.3)**, and case resolution efficiency.
*   **Analytical Depth:** Identifies client frequency distributions. A key insight generated is the **Top Client Leaderboard**, which reveals high-retention accounts (e.g., *Mohammadreza Baran* accounting for **19%** of total visits).
*   **Business Application:** Allows the service team to prioritize high-value clients and identify "churn-risk" accounts based on visitation patterns.

### 2. Defect Proportionality Matrix
*Focus: Resource Allocation*
*   **Analysis:** A categorized horizontal bar chart mapping service burden. 
*   **Key Finding:** **Software-related issues (39.81%)** and **Mechanical defects (25.16%)** dominate the service portfolio. Electrical, Pneumatic, and Painting services follow at lower, predictable frequencies.
*   **Business Application:** Directs engineering and workshop resource allocation. Clearly demonstrates the need for specialized software-debugging training for the team.

### 3. Software/Program Defect Deep-Dive (Pareto Analysis)
*Focus: Quality Assurance & Engineering Feedback*
*   **Analysis:** Employs the Pareto Principle to isolate the "vital few" from the "trivial many."
*   **Key Finding:** The dashboard highlights that approximately **70% of all software-related issues** are driven by only 4 primary items: **ECAS-1 (23.3%)**, **Radar Calibration (22.4%)**, **Cabin Adjustment (13.8%)**, and **Generic Bug Types (12.1%)**.
*   **Business Application:** Provides an immediate roadmap for the R&D/Software team to patch recurring systemic glitches, drastically reducing overall support ticket volume.

### 4. Temporal Trend Analysis
*Focus: Capacity Planning*
*   **Analysis:** A multi-dimensional view of ticket inflow trends over the year 1404.
*   **Business Application:** Identifies seasonality in service demands, enabling human resource managers to optimize technician shifts and ensure service level agreements (SLAs) are met during peak traffic periods.

---

## 💻 Technical Implementation Details
*   **Data Architecture:** Developed using an **Extract, Transform, Load (ETL)** workflow via Power Query to clean and normalize raw logs.
*   **Data Modeling:** Utilizes a **Power Pivot Data Model** with star-schema relationships between fact tables (tickets/visits) and dimension tables (clients, categories, dates).
*   **Advanced Calculations:** 
    *   **Dynamic Arrays:** Heavy use of `FILTER`, `UNIQUE`, and `XLOOKUP` for real-time reporting.
    *   **DAX Measures:** Custom DAX measures for calculating MoM (Month-over-Month) growth and resolution velocity.
*   **UI/UX Design:** Implemented dynamic shape-linking and VBA-free hyperlinking for frictionless cross-module navigation.

---

## 📈 Strategic Business Value
This dashboard has successfully:
1. **Reduced Resolution Time:** By identifying the top 4 software bugs, the engineering team could prioritize patches, reducing "mean time to repair."
2. **Optimized Staffing:** Shifted scheduling models based on seasonal ticket inflow trends.
3. **Improved Client Satisfaction:** Proactive identification of repeat visitors allows for better service personalization.

---
*Built by [Your Name]. Expert-level Excel Business Intelligence Portfolio.*

