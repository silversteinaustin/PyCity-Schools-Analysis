# PyCity Schools Analysis

## Overview

As the newly appointed Chief Data Scientist for the city's school district, I undertook an in-depth analysis of district-wide standardized test results. By leveraging Pandas DataFrames and Jupyter Notebook, I aggregated data from various sources to unveil trends in school performance. This project served as a cornerstone for strategic decisions regarding future school budgets and priorities.

### Objective

The main objective was to analyze standardized test results across 249 mice with SCC tumors treated with various drug regimens, focusing on Pymaceuticals’ drug, Capomulin. This comprehensive analysis aimed to provide the school board and mayor with actionable insights into school performances, guiding future educational strategies and investments.

### Methodology

#### Data Preparation

- Merged `mouse_metadata` and `study_results` DataFrames.
- Cleaned the data by removing duplicates.
- Created a unified dataset for analysis.

#### District Summary

- Calculated key metrics such as total schools, students, budget, and average scores.
- Derived percentages for passing math, reading, and overall passing rates.

#### School Summary

- Summarized key metrics by school, including type, total students, budget, and scores.
- Calculated percentages for passing math, reading, and overall passing.

#### Performance Analysis

- Identified highest and lowest-performing schools by % overall passing.
- Analyzed math and reading scores by grade for each school.
- Examined school performance based on budget per student, school size, and type.

### Key Findings

1. Capomulin significantly outperformed other drug regimens in tumor reduction.
2. There was a strong correlation between school budgets per student and overall passing rates, with schools having lower per-student budgets performing better.
3. Small to medium-sized schools (less than 2000 students) showed higher overall passing rates compared to larger schools.

### Challenges and Solutions

The analysis involved complex data manipulation tasks, including merging datasets, calculating summary statistics, and categorizing schools based on spending, size, and type. Solutions included the use of advanced Pandas functionalities like `.groupby()`, `.cut()`, and conditional formatting to streamline the analysis process and generate insightful visualizations.

### Conclusion

The PyCity Schools analysis revealed significant insights into the effectiveness of different educational strategies and resource allocations. By focusing on data-driven decision-making, the school district can enhance student outcomes and optimize budgetary spending. The findings of this report will aid in setting future educational priorities and ensuring equitable access to quality education.

### Acknowledgments

I extend my gratitude to the school board and mayor for their trust in my capabilities. Special thanks to my peers and mentors for their support and guidance throughout this project.
