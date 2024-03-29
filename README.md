# pandas-challenge

# PyCitySchools Analysis

![education](https://github.com/onemanlutta/pandas-challenge/assets/118937365/799f70b7-a77a-4ab5-b425-2fa136e2dc88)


## Project Overview
As the new Chief Data Scientist for the city's school district, the goal is to provide strategic insights and recommendations to the school board and mayor. This involves analyzing district-wide standardized test results, including math and reading scores, as well as various school-related information. The analysis aims to identify trends and patterns in school performance to inform future budget allocation and policy decisions.

## Project Structure
- **Repository**: [pandas-challenge](https://github.com/onemanlutta/pandas-challenge)
- **Folder Structure**:
  - **PyCitySchools**: Contains the main Jupyter Notebook file (`PyCitySchools_starter.ipynb`) for data analysis.
  - **Resources**: Contains the datasets used for analysis (`schools_complete.csv` and `students_complete.csv`).
  - **Analysis Report**: The analysis report in Word format (`PyCitySchoolsAnalysisReport.docx`).

## Data Files
- **schools_complete.csv**: Contains information about each school in the district.
- **students_complete.csv**: Includes data on each student's performance, including math and reading scores.

## Analysis Highlights

### District Summary
- Total number of unique schools: 15
- Total students: 39,170
- Total budget: $24,649,428.00
- Average math score: 78.99%
- Average reading score: 81.88%
- % passing math: 74.98%
- % passing reading: 85.81%
- % overall passing: 65.17%

![District Summary Table](https://github.com/onemanlutta/pandas-challenge/assets/118937365/957f6378-47cb-4b18-bdd2-0a9f9329e225)


### School Summary
- School-specific metrics including average scores, passing rates, and budgets.

![School Summary Results](https://github.com/onemanlutta/pandas-challenge/assets/118937365/07e04ed9-c9ea-4525-be3a-ec4d5df7554d)


### Highest-Performing Schools (by % Overall Passing)
- Top 5 schools with the highest overall passing rates.

![Highest Performing Schools](https://github.com/onemanlutta/pandas-challenge/assets/118937365/9e6939d1-8735-49be-b223-cfe8d052f08e)


### Lowest-Performing Schools (by % Overall Passing)
- Top 5 schools with the lowest overall passing rates.

![Lowest Performing Schools](https://github.com/onemanlutta/pandas-challenge/assets/118937365/5bd68fbc-aa12-4291-8613-45726c1d7639)


### Math Scores by Grade
- Average math scores by grade level for each school.

### Reading Scores by Grade
- Average reading scores by grade level for each school.

### Scores by School Spending
- Breakdown of school performance based on spending ranges per student.

![School Spending](https://github.com/onemanlutta/pandas-challenge/assets/118937365/544bb3e1-49c6-4d90-a934-63aafd800f34)


### Scores by School Size
- School performance categorized by small, medium, and large sizes.

![School Sizes](https://github.com/onemanlutta/pandas-challenge/assets/118937365/cc0d7d0a-cfb7-4aa8-9081-4b17c972b930)


### Scores by School Type
- Comparison of school performance based on school type (charter vs. district).

![School Type](https://github.com/onemanlutta/pandas-challenge/assets/118937365/85c5f766-59cc-41d1-9cf0-f64f9417121c)


## Observations
1. **Spending Impact**: Schools with lower per student budgets (<$585) tend to have higher overall passing rates compared to schools with higher per student budgets.
2. **School Type Effect**: Charter schools consistently outperform district schools in terms of overall passing rates.

## Disclaimer
Data for this analysis was generated by Mockaroo, LLC, and is intended for educational purposes only.