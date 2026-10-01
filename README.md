# LMS Analytics & Customer Segmentation Portfolio

## 📌 Project Overview
An end-to-end data analysis project simulating a Learning Management System (LMS) ecosystem. This repository demonstrates a complete data workflow—from raw database extraction and automated Python risk modeling to executive dashboarding—designed to track student engagement, monitor course completion rates, and flag inactivity risks.

---

## 🛠️ Tools & Technologies Used
* **SQL:** Database design, querying relational records, and data extraction.
* **Python (Pandas, Seaborn, Matplotlib):** Data manipulation, business logic implementation, and statistical visualization.
* **Power BI:** Interactive dashboarding and business intelligence reporting.
* **VS Code & Jupyter Notebooks:** Development environment.

---

## 📂 Project Structure & Components

### 1. Database & Extraction (`0eries.1_LMS_Analysis_Qusql.sql`)
* Designed and structured student engagement records.
* Queried core metrics including student IDs, names, course titles, completion percentages, and login timestamps to prepare clean datasets for analysis.

### 2. Risk Classification Logic (`03_lms_python_analysis.ipynb`)
* Implemented a data-driven business logic in Python using `pandas` based on a **14-day inactivity threshold**.
* Automatically segmented students into risk categories (`Active` vs. `High Risk`) to pinpoint disengaged learners who require immediate intervention.
* Generated clean dataframes displaying actionable student statuses.

### 3. Data Visualization & Insights (`lms_inactivity_risk.png`)
* Developed an analytical **Scatter Plot** using `seaborn` and `matplotlib` plotting *Days Inactive* against *Completion Rate (%)*.
* Highlighted the critical 14-day limit using a customized reference line and distinct color palettes to separate active users from high-risk students.
* Exported high-resolution visual outputs (`.png`) for reporting.

### 4. Interactive Dashboard (`LMS_Analytics_Dashboard.pbix`)
* Built a comprehensive Power BI dashboard to synthesize all findings into an executive-level interactive interface.
* Allowed dynamic filtering by courses and student statuses to monitor overall platform health.

---

## 📊 Key Findings & Business Value
* **Inactivity Impact:** Students with more than 14 days of inactivity show a sharp decline in course completion rates, often dropping below 40%.
* **Proactive Interventions:** Automated segmentation allows instructors and platform administrators to target disengaged learners before they drop out.

---

## 🚀 How to Explore This Repository
1. Review the SQL script to understand data extraction.
2. Open `03_lms_python_analysis.ipynb` in VS Code to run the Pandas analysis and regenerate the visualization.
3. Open `LMS_Analytics_Dashboard.pbix` in Power BI Desktop to explore the interactive visual metrics.
