# Navigating The Job Market: How Demographics Shape Employment Prospects

## Data Source:
The project utilizes the Survey of Consumer Expectations data, © 2013-2023, provided by the Federal Reserve Bank of New York (FRBNY).

## Objective:
The primary objective of this project is to analyze and understand the mean probability of finding a job in the next three months if an individual loses their job today. This analysis is conducted with a focus on various demographic factors, shedding light on how expectations vary across different segments of the population.

## Demographic Categories:
The project considers the following demographic categories for analysis:

Age: Under 40, 40-60, Over 60
Education: High School or Less, Some College, BA or Higher
Income: Under 50k, 50-100k, Over 100k
Numeracy: Low, High
Region: West, Midwest, South, Northeast

## Key Analysis Points:

Age Groups: Explore how job finding expectations differ across age groups, assessing the impact of age on employment prospects.

Education Levels: Analyze the correlation between educational attainment and job finding expectations, examining whether higher education influences optimism about finding employment.

Income Brackets: Investigate how income levels affect the perceived likelihood of securing a job within the next three months.

Numeracy Skills: Assess the influence of numeracy skills on job finding expectations, comparing responses from individuals with low and high numeracy proficiency.

Regional Variances: Examine regional differences in job finding expectations, highlighting any geographic patterns that may emerge.

## Analysis Approach:
The Jupyter notebook implements the analysis in Python using pandas, matplotlib, seaborn, scikit-learn and other libraries. Key techniques include:
Data inspection, cleaning, preprocessing
Summary statistics and correlation analysis
Visualizations - heatmaps, pairplots, boxplots, time series plots
Regression modeling to predict job finding probabilities

## Key Findings
Some observations from the analysis include:
Job finding expectations tend to be higher for younger individuals
Higher educational attainment correlates with greater employment optimism
High income brackets report higher perceived job finding odds
Numeracy skills are positively associated with job finding outlook
Geographic variations exist in employment expectations

## References
The SCE data is provided by the Federal Reserve Bank of New York under license terms available on their website. This analysis makes no claims on the accuracy of job-finding expectations reported in the SCE survey.
