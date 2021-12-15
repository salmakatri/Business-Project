# Abstract
The goal of this project is to help newly resettled refugees find employment faster. By identifying insights and factors impacting a refugee’s chance of employment, UNHCR can prioritize resources and trainings to better equip those individuals at risk of unemployment with a better chance to succeed in the new environment. I worked with published survey data from the 2016 Annual Refugee Survey conducted by the Office of Refugee Resettlement. I have cleaned and explored the data using Excel. I also built an interactive dashboard to visualize and communicate my results using Tableau.

# Design
Data usually shows a “refugee gap” when comparing resettled refugees to other immigrants in terms of labor market integration. The published survey data from 2016 contains individual characteristics and tracks various attributes for refugees who entered the US between 2011 and 2015. By analyzing this data to understand what factors affect a refugee’s chance in finding employment and ultimately creating a classification model, UNHCR can provide additional resources and tailored solutions for those individuals identified to be at risk of unemployment. 

# Data
The dataset contains 4,776 rows representing survey respondents. The original dataset contained over 300 columns, but only 58 were kept for data analysis. Main features of interest include gender, age, education, English proficiency, degree, state of resettlement, total earnings, date of first job and job status. 

# Algorithms
As part of the data manipulation step, I have applied some feature engineering and created three new metrics:
* HH Head: Binary variable with values “Yes” and “No” indicating whether an individual is the head of his household
* At work age when entered:  Binary variable with values “Yes” and “No” indicating whether an individual was older than 22 when first arrived to the US
* Job within 1 year (Main Variable of Interest): Binary variable with values “Yes” and “No” indicating whether an individual found employment within his first year after resettlement 

Data analysis focused on exploring the impact of various features on the variable of interest (Job within 1 year) to examine any trends or emerging relationships. 

As next steps, we need to build a classification model to determine if a refugee is at risk of unemployment. UNHCR can then focus its resources to help those who are most in need. Further work might also be done with unsupervised clustering to better understand if different clusters might reveal different characteristics. 

# Tools
*	Python to read data, convert from .dta format and download as excel file 
*	Excel for data cleaning and exploratory data analysis
*	Tableau for data visualization

# Communication
A slide deck is included in the repository as well as a link to an interactive [Tableau dashboard](https://public.tableau.com/views/BusinessProjectDashboard/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link/)
