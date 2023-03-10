# nurse resaerch study

## Project Details
### Purpose of Study
Nursing shortage and turnover have been the major challenges in the healthcare industry. Many research studies have investigated the intention in terms of the factors that cause turnover and shortage with the purpose of helping healthcare administrators understand the root cause of the nurse turnover phenomenon in order to be better prepared for the ongoing challenge in nurse staffing. This research aims to study nurses’ behavior towards turnover and shortage based on the survey data, which intends to answer questions such as: “Where did the acute nurses go? Did they quit nursing care, leave for another position within the organization or leave for another position outside of the organization?”
### Scope
A survey was designed and then published to reach out to the target participants (current US active nurse). Analysis is performed to seek for insights to answer the question “where did the nurse go?”
### Data Cleaning
1.	Data header is simplified into a structured format where better readability is the goal. To ensure the data quality, only current licensed nurses who are living or working in the US are selected for the study. 
2.	Data was cleaned by:
a.	dropping nulls in "is_job_change_since_2019" and "cur_annual_range"
b.	removing unrelated columns: columns after “job4”
c.	filling null value in “cur_type_of_facility” with “Acute care hospital”
d.	standardizing gender column
3.	Creating derived variables: total of 18
a.	License types and quantities are grouped
b.	Facilities are grouped
c.	Units are grouped
d.	Years in profession is grouped
e.	Job change is grouped
f.	License level change is grouped
g.	Salary level is grouped
h.	Along with other basic calculations
4.	Selecting variables: total of 26. 
5.	Removing rows that jobs change is “Yes”, and total job changes is 0
6.	Converting categorical variables to category
### Analysis
1.	Descriptive
a.	 Continuous: correlation & histogram
b.	 Categorical: categories and count
2.	EDA
3.	Chi-Square: test for independence
### Result
2019 unit is associated with current unit, meaning there are patterns where nurses go from one unit to another (See 3.2.2 Where Did the Nurses go?). The result also shows that changes in license type, changes in salary and level of years in profession are associated with job change and unit change.
### Notes
Additional Analyses are done. Codes and results are stored in other documnetation. I may uplaod here later.
