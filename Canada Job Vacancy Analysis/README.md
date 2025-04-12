# Project Background
Here I looked to examine data regarding job vacancies in Canada in order to determine if there are any trends that may positively or negatively impact certain demographics.
Insights are provided based on the following data:
-	Job Vacancies: At the core of this analysis, the total number of jobs available was examined, focusing on necessary job requirements including minimum education and experience.
-	Unemployment Rate: The percentage of participating Canadian workers unable to find jobs.
-	Total Workers in Canada: An evaluation of how much the total workforce is increasing.

The Excel Workbook used for exploring the data for this analysis can be found here [link].

Python was used to scrap some of the data used for analysis, the code can be found here [link]

A Tableau dashboard containing the relevant visualizations can be found [here](https://public.tableau.com/app/profile/jack.lemere5367/viz/CanadaJobTrends/Dashboard1?publish=yes).

# Data

The data used in this analysis examined 3 different tables:
-	Statistics Canada. Table 14-10-0443-01  Job vacancies, proportion of job vacancies and average offered hourly wage by occupation and selected characteristics, quarterly, unadjusted for seasonality
-	Statistics Canada. Table 14-10-0020-01  Unemployment rate, participation rate and employment rate by educational attainment, annual
-	Statistics Canada. Table 14-10-0288-02  Employment by class of worker, monthly, seasonally adjusted (x 1,000)

# Summary

### Overview of Findings

The following insights have been noted:
-	Total job vacancies have been declining since a strong peak in 2022
-	Job vacancies requiring less previous experience are declining at a faster rate than all other prior experience requirements
-	Jobs with lower education requirements are declining at a faster rate than all other minimum education requirements
-	Growth rate of employment in Canada has not changed significantly in recent years
-	Unemployment rate in Canada has increased in 2024 from previous years

# Insights Deep Dive

The first analysis done was on job vacancies in relation to the necessary experience required for those jobs. The first dataset breaks down the total job vacancies by the amount of experience required by each job. They are split into categories Less than 1 year, 1-3 years, 3-5 years, 5-8 years, and 8+ years. By examining these job vacancies by their required experience, it was found that the number of jobs that require no experience has been declining particularly heavily over the past two years. The total number of job vacancies for all other experience levels appears to reflect the general growth of employment in Canada, though the number of job vacancies requiring no experience has fallen to its lowest tally since 2017 despite a growing population of workers. This may be an indication that jobs that fall into these categories are becoming increasingly competitive. Having a more competitive job market is generally good for businesses, however it may lead to more barriers for job applicants in these affected demographics to feel more obstacles when job seeking, leading to a decrease in economic opportunities.

[Visualization, including a graph of overall trends or snapshot of a dashboard]

A similar comparison can be made when it comes to education. The dataset also breaks down job vacancies by their minimum education requirements. These requirements are broken down into no minimum education required, high school diploma, non-university certificate, university certificate below bachelor’s degree, bachelor’s degree, and university certificate above bachelor’s degree. What was found was that jobs with lower education requirements are seeing a stronger decrease in vacancies than jobs with higher education requirements. Since 2016, jobs with no education requirements followed by high school diploma jobs have seen the highest number of vacancies than any other category. As of 2024, the jobs that have highest proportion of vacancies are those that require at least a non-university certificate. Similarly to the experiential analysis, having a lack of education may lead to increased competition from some people when searching for work, resulting in lowered economic opportunities. 

The trends identified so far also coincide with a small increase in unemployment rate. Apart from the large increase in unemployment during the COVID-19 lockdown periods, the unemployment rate in Canada had been steadily decreasing. However, 2024 saw an increase in unemployment rate for the first time since 2020. Despite a consistent increase in the number of workers in Canada over the years, the number of total job vacancies in all areas has seen a decline in recent years. This may indicate higher job market competition in general, though the previous analysis would indicate those with low education or experience are likely the most affected.

[Visualization specific to category 1]

# Recommendations:

Although there is a host of potential additions that would help to enrich this analysis, I believe the following should be further explored: 
-	What is causing the total number jobs vacancies with little education or experience to decline in recent years? Some possibilities may include evolving education demographics, emerging and declining business sectors, policy changes, etc.
-	How much of an impact do these changing trends have on economic opportunity for those who fall in these demographics? Further analysis on whether these types of jobs are now more competitive and causing difficulty in securing employment would be beneficial.
-	If these trends are indicators of lower economic opportunity, what can be done to mitigate it? Having a clearer picture of the job market would help further initiatives such as getting people better access to job experience and education or creating more jobs in which these potential barriers are not required.
