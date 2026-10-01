# Sri Lanka Grade 5 Scholarship Performance Analysis
 
## Project Overview

This project analyzes district-level and national trends in Sri Lanka's Grade 5 Scholarship Examination performance using official public data.

The project also explores whether selected basic household infrastructure conditions are associated with educational performance at the district level. Grade 5 Scholarship Examination results are used as a measurable indicator of educational achievement for this analysis.

The analysis was conducted using Python, Pandas, NumPy, Matplotlib, Microsoft Excel and Jupyter Notebook.

## Project Objectives

- Analyze Grade 5 Scholarship Examination performance across all 25 districts in Sri Lanka.
- Examine national performance trends from 2021 to 2026.
- Identify districts with higher and lower examination performance.
- Compare district-level educational performance with selected basic household infrastructure indicators.
- Explore the relationship between grid electricity, pipe-borne water, exclusive toilet facilities, and    educational performance.
- Present the findings using statistical analysis and data visualizations.

## Datasets Used

### 1. Grade 5 Scholarship Examination Performance Data - 2026
District-level examination performance data for all 25 districts in Sri Lanka, including:
- Number of candidates who sat the examination
- Number and percentage of candidates reaching the scholarship cutoff
- Number and percentage of candidates scoring 100 or above
- Number and percentage of candidates scoring 70 or above

### 2. National Grade 5 Scholarship Performance Data - 2021 to 2026
National-level examination performance data used to analyze trends over time, including:
- Candidates who sat the examination
- Percentage reaching the scholarship cutoff
- Percentage scoring 100 or above
- Percentage scoring 70 or above
- Mean marks
- Standard deviation of marks

### 3. Basic Household Infrastructure Data - 2024
District-level household infrastructure data from the Census of Population and Housing 2024, including:
- Grid electricity usage
- Pipe-borne water supply
- Exclusive household toilet facilities

## Project Workflow

1. Collected official Grade 5 Scholarship Examination performance data.
2. Prepared and organized the district-level and national datasets using Microsoft Excel.
3. Loaded the datasets into Jupyter Notebook using Pandas.
4. Checked the datasets for missing values, duplicates and data-type issues.
5. Performed district-level exploratory data analysis for the 2026 examination.
6. Analyzed national performance trends from 2021 to 2026.
7. Collected district-level household infrastructure data from the 2024 Census of Population and Housing.
8. Merged the education and household infrastructure datasets using district names.
9. Created scatter plots to visually examine relationships between infrastructure indicators and educational performance.
10. Calculated Pearson correlation coefficients for grid electricity, pipe-borne water and exclusive toilet facilities against three examination performance indicators.
11. Summarized the findings using tables, charts and a correlation heatmap.
12. Documented the key findings, limitations and final conclusions.

## Key Findings

### District-Level Performance - 2026
- Kurunegala recorded the highest percentage of candidates scoring 70 or above at 79.72%, while Trincomalee recorded the lowest at 59.44%.
- Hambantota recorded the highest percentage of candidates reaching the scholarship cutoff at 27.53%, while Mannar recorded the lowest at 10.38%.
- Considerable differences in examination performance were observed across districts.

### National Performance Trends - 2021 to 2026
- The percentage of candidates scoring 70 or above reached its highest level in 2022 at 82.97% and its lowest level in 2025 at 70.43%.
- The percentage scoring 100 or above declined from 48.10% in 2021 to 31.39% in 2026.
- The percentage reaching the scholarship cutoff increased from 14.18% in 2021 to 19.32% in 2026.
- Mean marks fluctuated over the period, reaching the highest value in 2022 and the lowest in 2025.

### Household Infrastructure and Educational Performance
- Grid electricity showed the strongest positive relationship with the selected educational performance indicators.
- The strongest correlation was between grid electricity usage and the percentage of candidates scoring 100 or above (r = 0.61).
- Pipe-borne water showed very weak positive relationships with all three performance indicators.
- Exclusive toilet facilities showed weak to moderate positive relationships with educational performance.
- Overall, the results suggest that basic household infrastructure has some district-level association with educational performance, although the strength of the relationship varies by indicator.

## Technologies and Tools Used

- **Python** – Data analysis and statistical calculations
- **Pandas** – Data loading, cleaning, merging and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Interactive analysis and documentation
- **Microsoft Excel** – Initial data preparation and percentage calculations
- **Visual Studio Code** – Project development environment
- **Power BI** – Planned for interactive dashboard development


## Project Structure

```text
SriLanka_Grade5_Scholarship_Analysis/
│
├── Data/
│   ├── district_basic_infrastructure_2024.csv
│   ├── district_performance_2026.csv
│   └── national_performance_2021_2026.csv
│
├── Images/
│
├── Notebook/
│   └── grade5_scholarship_analysis.ipynb
│
├── Sources/
│   ├── households_drinking_water_2024.xlsx
│   ├── households_lighting_2024.xlsx
│   ├── households_toilet_facilities_2024.xlsx
│   └── grade5_scholarship_2026_report.pdf
│
└── README.md
```


## Limitations

- The Grade 5 Scholarship performance data are from 2026, while the household infrastructure data are from 2024. Therefore, the datasets do not represent exactly the same time period.
- The analysis is based on district-level aggregated data and does not represent individual students or households.
- Correlation does not imply causation. The relationships identified in this project do not prove that infrastructure conditions directly cause differences in educational performance.
- Only three household infrastructure indicators were included: grid electricity, pipe-borne water and exclusive toilet facilities.
- Educational performance can also be influenced by many other factors such as household income, parental education, school resources, teaching quality and access to learning materials.
- Grade 5 Scholarship Examination performance was used as one measurable indicator of educational achievement and should not be considered a complete representation of Sri Lanka's education system.

## Data Sources and References

- [Department of Examinations, Sri Lanka - Statistics](https://www.doenets.lk/statistics)
  - Grade 5 Scholarship Examination performance data and statistics.

- [Department of Examinations, Sri Lanka - Examination Results](https://www.results.exams.gov.lk/home.htm)
  - Official Grade 5 Scholarship Examination results portal.

- [Department of Census and Statistics, Sri Lanka - Census of Population and Housing 2024](https://www.statistics.gov.lk/Population/StaticalInformation/CPH2024/)
  - District-level household data on source of lighting.
  - District-level household data on main source of drinking water.
  - District-level household data on toilet facilities.

## Conclusion

This project explored Grade 5 Scholarship Examination performance across Sri Lanka using district-level and national data, and then examined whether selected household infrastructure indicators were associated with educational performance.

The analysis found noticeable differences in examination performance across districts and changes in national performance over time. Among the infrastructure indicators considered, grid electricity showed the strongest positive relationship with the selected educational performance measures, while pipe-borne water showed very weak relationships and exclusive toilet facilities showed weak to moderate relationships.

These findings suggest that basic household infrastructure may have some association with educational outcomes, but it is only one part of a much broader picture. Educational performance can also be influenced by many other social, economic, school-related and individual factors.

The Grade 5 Scholarship Examination was used in this project as a measurable indicator of educational achievement, and the results should be interpreted as associations rather than evidence of causation.

## Future Improvements

- Develop an interactive Power BI dashboard to present the main findings more clearly.
- Include additional socioeconomic indicators such as household income, parental education and poverty-related measures if suitable district-level data become available.
- Explore school-level variables such as school resources, teacher availability and access to learning materials.
- Apply statistical techniques such as regression analysis to study relationships between multiple factors and educational performance.
- Extend the analysis to other years and examinations to identify longer-term patterns.
- Compare district-level results with other educational indicators to obtain a broader view of educational outcomes in Sri Lanka.