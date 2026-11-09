# code_samples

Currently, this repo only contains the code I created for the [2021 Progressive Data, Analytics, and Technology Salary Survey](https://www.progressivedatajobs.org/salary-survey-2021/). 

In 2020 and 2021, four other colleagues and I in the progressive data space conducted surveys on employment and salaries. Beyond asking folks about their salary, we asked about the organizations they work for, what they do for their job, the skills and tools they use, and their future career plans.

Here are some of the code I created as part of this project: 

- `salary_survey.Rmd`: R markdown file used to generate https://www.progressivedatajobs.org/salary-survey-2021/  
- `cat_cross.R`: function that generates a crosstab of two categorical variables.
  - Example: https://www.progressivedatajobs.org/salary-survey-2021/#Seniority_by_Demographics 
- `median_hist.R`: function that generates a histogram and plots the median value.
  - Example: https://www.progressivedatajobs.org/salary-survey-2021/#total
- `mult_resp_cross.R`: for questions that allow for multiple responses, breaks down the responses by a categorical variable.
  - Example: https://www.progressivedatajobs.org/salary-survey-2021/#Negotiation_Outcomes_by_Demographics
- `salary_cross.R`: function that generates a crosstab of salary information with a categorical variable.
  - Example: https://www.progressivedatajobs.org/salary-survey-2021/#Salary_Crosstabs 

Data Visualization Highlights: 

- Lines 1092- 1203 in `salary_survey.Rmd`creates a percent stacked barchart of tool proficiency.
  - Final product: https://www.progressivedatajobs.org/salary-survey-2021/#tools

- Lines 550-589 in `salary_survey.Rmd` creates a density plot of the percentage of time writing code by role seniority.
  - Final product: https://www.progressivedatajobs.org/salary-survey-2021/#Time_Writing_Code

