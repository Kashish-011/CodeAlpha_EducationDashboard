# CodeAlpha Power BI Internship — Task 4: Educational Performance & Resource Allocation

## Objective
Develop an interactive Power BI dashboard to evaluate student academic performance and identify resource allocation gaps, supporting data-driven decisions in education management.

## Dataset
UCI Machine Learning Repository — Student Performance Dataset (Portuguese language course), 649 student records covering demographics, family background, study habits, and grades across three grading periods.

## Tools Used
- Power BI Desktop
- Power Query (data cleaning, custom columns, and readable category labels)
- DAX (custom measures for Pass Rate, At-Risk count, and grade progression)

## Dashboard Overview
The dashboard includes:
- **KPI Summary Row**: Average Final Grade, Total Students, Pass Rate %, and At-Risk Student Count
- **Performance Band Breakdown**: Segmenting students into High Performer / Average / At Risk
- **Study Time Impact**: Average grade by weekly study hours
- **Grade Progression**: Trend across the three grading periods (Period 1 → Period 2 → Final)
- **Parental Education Impact**: Average grade by mother's education level
- **Support Type Comparison**: Average grade by type of academic support received (family, school, both, or none)
- **Interactive filtering** by school

## Key Insights
1. **Grades improve steadily across the year** — average grade rises from 11.40 (Period 1) to 11.91 (Final).
2. **Study time correlates with performance** — students studying 3+ hours/week average notably higher grades than those studying under 2 hours.
3. **Parental education matters** — students whose mothers completed higher education average meaningfully higher final grades.
4. **Family support outperforms school-only support** — students receiving family support alone show higher average grades than those relying on school support alone, suggesting a resource allocation consideration for institutions.
5. **84.6% overall pass rate**, with 100 of 649 students (about 15%) falling into the At-Risk category, indicating a clear group for targeted intervention.

## Files
- `CodeAlpha_EducationDashboard.pbix` — Power BI project file
- `CodeAlpha_EducationDashboard.pdf` — Exported dashboard view

---
Submitted as part of the CodeAlpha Power BI Internship (Task 4).
