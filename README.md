# Education and Household Income: NHANES Statistical Analysis

This project explores whether household income can be predicted by educational attainment using data from the U.S. National Health and Nutrition Examination Survey (NHANES). The analysis includes data cleaning, exploratory data analysis, visualization, and a one‑way ANOVA to test for income differences across five education categories.

## Research Question
Does the highest level of education completed significantly impact household income?

- Null hypothesis: Education level has no effect on household income.  
- Alternative hypothesis: Household income differentiates across education levels.

## Data
The dataset includes 6,622 participants, each reporting:
- Education level (5 categories: 8th grade, 9–11th grade, high school, some college, college graduate)
- HHIncomeMid (numeric midpoint of reported income range)

Summary statistics show a clear upward trend in income as education increases.

## Methods
The analysis includes:
- Data wrangling with `tidyverse`
- Summary statistics by education category
- Histograms and boxplots of income distributions
- One‑way ANOVA comparing mean household income across education levels

ANOVA results:  
- F = 419.6  
- p < 2e‑16  

These results provide strong evidence that household income differs significantly by education level.

## Key Findings
- Participants with some college have median incomes above the overall sample median.
- Income distributions widen with higher education levels.
- The ANOVA strongly rejects the null hypothesis, supporting the idea that education is associated with higher household income.


## Technologies Used
- R  
- tidyverse  
- ggplot2  
- NHANES package  

## References
- Pruim, R. (2015). *NHANES: Data from the US National Health and Nutrition Examination Study*.  
- U.S. Bureau of Labor Statistics (2025). *Education pays: Unemployment rates and earnings by educational attainment*.




