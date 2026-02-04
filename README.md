# DDA Contest Analysis

## Project Overview
DDA Contest Analysis is a data analytics project focused on evaluating student performance across multiple coding contests. The project consolidates data from different contest formats, normalizes scoring systems, and generates branch-wise insights through analysis and visualization. An interactive Power BI dashboard is used to present results to stakeholders.

The objective is to identify performance gaps, assess practical coding proficiency, and provide data-driven recommendations for academic improvement.

---

## Problem Statement
Despite participation in coding contests, overall programming performance among students remains inconsistent across branches. Differences in contest structure and scoring methods make direct comparison difficult. This project addresses these challenges by standardizing data, normalizing scores, and analyzing outcomes in a unified framework.

---

## Objectives
- Consolidate contest data from multiple sources into a single dataset
- Clean and standardize academic and performance-related attributes
- Normalize scoring across different contest formats
- Perform branch-wise performance analysis
- Visualize insights using Power BI
- Provide actionable academic and training recommendations

---

## Dataset Description
The dataset contains student-level performance records with the following key attributes:

### Academic Information
- `student_id`
- `student_name`
- `college`
- `branch`
- `passout_year`

### Contest Performance
- `programming_score`
- `mcq_correct`
- `mcq_total`
- `total_points`
- `rank`

Multiple contest datasets (Contest 1, Level 1, Level 2) are combined and analyzed.

---

## Data Processing & Methodology
- **Data Cleaning**
  - Standardized branch and college names
  - Removed duplicates and invalid entries
  - Handled missing and inconsistent values

- **Score Normalization**
  - Applied weight multipliers to equalize contests with different MCQ counts
  - Ensured fair comparison across all participants

- **Data Modeling**
  - Implemented a star schema
  - Central student table with contest-specific fact tables

---

## Tools & Technologies
- Microsoft Excel (raw data handling)
- Python (data cleaning and analysis)
- Power BI (dashboard and visualization)

---

## Key Insights
- Average programming scores across branches are significantly low
- MCQ performance is comparatively higher than coding performance
- Indicates lack of hands-on coding practice and real-world problem-solving exposure

---

## Recommendations
- Introduce mandatory daily coding practice
- Conduct weekly internal coding contests
- Shift curriculum focus to 70% practical and 30% theory
- Increase faculty and infrastructure before scaling batch sizes
- Provide early exposure to competitive programming

---

## Dashboard
An interactive Power BI dashboard presents:
- Branch-wise performance comparison
- Programming vs MCQ score trends
- Student ranking distribution

Dashboard files are available in the `dashboard/` directory.

---


---

## Contributors
- Nitu singh
- Tanishq Sharma  
- Sejal Chawla 
- Divya Thakur
- kashish 




---

## License
This project is intended for academic and educational purposes. Add a license file if publishing publicly.

---

## Acknowledgements
Special thanks to mentors and evaluators who provided guidance and feedback during the project.
