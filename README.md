# Tennessee STAR Project - Exploratory Data Analysis

## Overview
This project analyzes the Tennessee Student/Teacher Achievement Ratio (STAR) study dataset, a four-year longitudinal educational experiment conducted in the late 1980s. The study investigated the effect of classroom size on academic achievement by randomly assigning over 7,000 students across 79 schools to one of three interventions:
- Small class (13-17 students per teacher)
- Regular class (22-25 students per teacher)
- Regular-with-aide class (22-25 students with a full-time teacher's aide)

## Dataset
The dataset contains information on:
- Student demographics (gender, ethnicity)
- Test scores (reading and math) across kindergarten through 3rd grade
- Teacher characteristics (experience, education level, ethnicity)
- School information (location type: rural, urban, suburban, inner-city)

## Analysis Approach
The analysis is divided into two main parts:

### 1. Basic Data Visualization
- Examining marginal distributions of key variables
- Visualizing joint and conditional distributions between variables
- Computing numerical summaries to understand proportions and central tendencies

### 2. Advanced EDA Techniques
- Using group_by, summarize, and mutate for aggregated insights
- Implementing filter and select for targeted data exploration
- Creating custom functions to streamline analysis
- Developing advanced ggplot visualizations for multi-dimensional insights

## Key Findings
- Students in small classes consistently demonstrate higher median reading and math scores
- Teacher experience positively correlates with student achievement
- Rural schools show the highest combined math and reading scores in 3rd grade
- Inner-city schools demonstrate lower average academic performance
- Gender distribution is slightly skewed toward male students across all class types
- Academic performance demonstrates correlation patterns with both ethnicity and school type

## Tools Used
- R programming language
- ggplot2 for data visualization
- dplyr for data manipulation and transformation

## Conclusion
The analysis provides evidence that smaller classroom sizes have a positive impact on student achievement, particularly in early grades. The data suggests that this effect is magnified when combined with experienced teachers. The study also reveals educational disparities across different school types and demographics, highlighting the complex interplay of factors affecting student achievement.

## Files in this Repository
- `eda_analysis.R`: R script containing all analysis code
- `report.Rmd`: R Markdown file with detailed findings and visualizations
- `report.pdf`: PDF version of the final report
- `data/`: Directory containing the STAR dataset (from AER package)
- `images/`: Directory containing exported visualizations

## How to Reproduce
1. Ensure R is installed with the following packages:
   - tidyverse
   - AER (for the STAR dataset)
   - knitr (for report generation)
2. Clone this repository
3. Run the R scripts or knit the R Markdown file

## Acknowledgments
This analysis is based on data from Project STAR, which was funded by the Tennessee General Assembly and conducted by the State Department of Education in the late 1980s.
