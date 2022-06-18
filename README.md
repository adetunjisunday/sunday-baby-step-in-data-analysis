# Project Name: COVID-19 GLOBAL INSIGHTS

---
# Project Objective:
COVID-19 (The coronavirus disease), a communicable respiratory disease broke in 2019 and has spread to the far ends of the world infecting humans, both young and old. Different countries implemented lockdowns in order to contain the disease and to prevent further spreading while finding medical solution to cure the infected. Over days,months, years and still counting, there are reports of people confirmed to be infected and dead as a result of the outbreak. Accolades to the medical practitioners who have made recovery mostly possible. However, there are data of these reports of cases, deaths and recovery which are available on daily basis. While aspiring to be a data analyst, I have been able to learn to analyse these data- kudos to NG30dayoflearning. This analysis is just to provide an insight into the data provided for different countries.
---

# Data Sourcing:
The data used is being scraped from COVID-19 github data- https://aka.ms/30DLCOVID19GitHubData while the analysis is done with microsoft excel.

# Data Transformation:
The data is being loaded from web with its source code copied into Microsoft Excel- in order confirmed cases, deaths and recovered. It was transformed into Power Query. Changed the query name, editted the source to remove the column load limit in order to enable update. Made first row as column header and select state/province, country/region, long, lat then unpivot other columns. Deleted Attribute, changed data types and renamed columns from value to confirmed. I duplicated the query and then changed the source with deaths and recovery in other to apply the previous changes then renamed their columns to death and recovered. Also renamed the query name as appropriate. On home tab, I merged query as new for confirmed and death by clicking soen on provincce, country and date. Combined recovered and renamed as consolidated data. Removed unwanted columns such as long, lat, province etc. Changed the data type for date and worked on pivot tables and charts. Then created a dashboard.
---

# Findings
Total number of confirmed cases is 525963892	while Total Deaths is 6268256 as at 16th June, 2022
	


![image](https://user-images.githubusercontent.com/107109434/174424218-b0cec7ff-6824-45a9-90b2-549b52ca34aa.png)
		





The United States has the highest number of confirmed cases

![image](https://user-images.githubusercontent.com/107109434/174424382-6f9ade21-3c95-4b76-a575-79fd47a03d7f.png)


Countries with least cases
![image](https://user-images.githubusercontent.com/107109434/174424403-7417c39f-417f-4edc-bdec-f2eaabe6e0ea.png)




However, the countries are subject to change when month and year filter is being applied.


In Nigeria,
Total Confirmed	cases is 256,352, Reported Deaths is 3,148	while Death Rate is 1.33%
![image](https://user-images.githubusercontent.com/107109434/174139917-97148845-f929-4ae2-926a-6f4c16968323.png)
![nig](https://user-images.githubusercontent.com/107109434/174140266-ff0f579e-201f-4198-95be-b90490e633f7.PNG)

It is also noticeable that confirmed cases correlates with deaths and recovery steeps back to zero in August 2021 because no data has been recorded since then.






