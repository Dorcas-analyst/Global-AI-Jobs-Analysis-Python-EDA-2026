# Global-AI-Jobs-Analysis-Python-EDA-2026
An exploratory data analysis of 90,000 AI job records and 35 variables covering salary, bonuses, experience, education, work arrangements, hiring activity and workplace indicators from 2020 to 2026.

## Project Overview
This project investigates patterns in AI-related employment using Python. The analysis focuses on compensation, career progression, work modes, hiring activity and relationships among selected numerical variables.
The project is descriptive and exploratory. It does not train or evaluate a machine-learning model.

## Objectives
- Assess dataset completeness, structure and data types.
- Compare salary distributions across experience and education levels.
- Examine salary and bonus trends from 2020 to 2026.
- Analyse job openings by industry, country and company size.
- Explore work-mode distribution and industry hiring difficulty.
- Evaluate correlations between salary, bonus and company rating.

## Dataset
- **Records:** 90,000
- **Variables:** 35
- **Period:** 2020–2026
- **Missing values:** None reported in the initial audit
- **Duplicate rows:** None reported in the initial audit
The dataset includes job roles, AI specialisations, experience levels, salary, bonuses, education requirements, countries, industries, company size, work mode and employee-related indicators.
> **Data limitation:** The dataset's source was not documented in the report. Its unusually uniform distributions suggest it may be simulated, so the findings should not be generalised to the real global labour market without validation.

## Tools and Libraries
- Python
- pandas
- NumPy
- Matplotlib
- seaborn
- Jupyter Notebook

## Analytical Workflow
1. Imported and inspected the dataset.
2. Examined data types, descriptive statistics, missing values and duplicates.
3. Grouped variables into five thematic segments.
4. Profiled distributions using histograms, KDE plots, count plots and bar charts.
5. Compared salaries using box plots.
6. Aggregated job openings by industry and country.
7. Analysed salary and bonus trends over time.
8. Calculated correlations and visualised relationships using a heatmap and pair plot.
9. Documented findings, limitations and recommendations.

## Key Findings

| Analysis | Finding |
|---|---|
| Salary by experience | Approximate median rose from $63,000 at Entry level to $147,000 at Lead level. |
| Salary and bonus | Positive correlation of 0.75. |
| Salary by education | Median salaries were approximately $87,000–$88,000 across education categories. |
| Company rating | Near-zero correlation with salary (-0.0004) and bonus (0.0017). |
| Annual trends | Average salary and bonus varied by less than 1% over 2020–2026. |
| Work mode | On-site, remote and hybrid roles were nearly evenly represented. |

These findings describe the dataset, not verified global employment trends.

## Limitations and Technical Improvements
- Verify the dataset's source and whether its records are real or simulated.
- Correct the `weekly_hours` conversion; working hours should remain numeric rather than being converted to datetime.
- Review figure-export logic so charts are saved correctly.
- Extend correlation analysis to additional numerical variables.
- Use formal statistical tests and effect sizes to evaluate group differences.
- Consider cost-of-living and tax adjustments before comparing compensation across countries.

## Future Work
- Statistical hypothesis testing
- Salary and bonus regression analysis
- Machine-learning experiments after validating the data
- Time-series analysis by country and industry
- SQL-based aggregations
- Interactive Power BI dashboard development

## Skills Demonstrated
Python programming, pandas data manipulation, NumPy, exploratory data analysis, descriptive statistics, data visualization, correlation analysis, data quality assessment and technical reporting.

## Author's Contribution
I independently wrote and executed the Python code for this project, conducted the exploratory analysis, interpreted the results and documented the findings and limitations.
**Project Status:** Phase 1 — Exploratory and Descriptive Analysis
