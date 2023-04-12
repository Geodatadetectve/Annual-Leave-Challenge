# Annual-Leave-Challenge
Aims: To create an impactful visual on paternity leave trends and patterns around the business world using crowdsourced information from over 1,500 real companies. For this challenge, I worked as a Data Visualization Specialist at an online business journal and created charts, visuals, and infographics as supporting content for the analysis.


Data source
https://www.mavenanalytics.io/challenges/maven-family-leave-challenge/2 

Skills used
Data aggregation, Data manipulation and cleaning, Desktop design, Data visualization and Data insights, DAX

Process
✅ I reviewed the data to find any bad data points, missing data, and duplicated data to perform accurate analysis, visualize the data, and draw actionable insights.  
✅Then, I cleaned and transformed the data.
✅Performed simple DAX 
✅ Final step was to divide into the cleaned data and obtain important insights.

Data cleaning manipulation and transformation
•	The data used in this analysis is titled ‘Parental Leave Policies’ and include crowdsourced parental leave data from 1,601 companies across different industries, including paid/unpaid maternity and paternity leave weeks. 
•	The schema of the file type (CSV), data structure (single table), # of records (1601) and # of fields (6).
•	During the process of data cleaning, I identified errors in the data types for the fields related to 'Paid Maternity Leave', 'Unpaid Maternity Leave', 'Paid Paternity Leave', and 'Unpaid Paternity Leave'. These fields were originally stored as 'text' format, rather than numerical values. To rectify this, I converted the data to numerical values without decimal points. Additionally, any missing data marked as "N/A" were transformed into "0" to facilitate visualization and streamline the DAX process.
•	As part of the DAX formulas utilized, I calculated the sum, average, and maximum number of days taken for both maternity and paternity leave (paid and unpaid), as well as identified the top 10 industries with the highest number of leave days.
Tools
Excel spreadsheet, Power Query, Pivot Table, Microsoft PowerBI


Insights from the data
•	In the case of Maternity leave, Paid leave makes up 63.82% of all maternal leave, with the remaining 36.18% being unpaid. On the other hand, for Paternity leave, Paid leave makes up 81.06% of all paternal leave, with the remaining 18.94% being unpaid.
•	The total number of Paid Maternity leave days provided by all companies (17,466 days) is greater than the number of Paid Paternity leave days (2,118 days). Similarly, the number of Unpaid Maternity leave days (9,902) is higher than the number of Unpaid Paternity leave days (495 days).
•	At 2026 days, the 'Technology: Software' industry had the highest number of Paid Maternity Leave days, which was 453.42% greater than that of the 'Technology: Manufacturing' industry, the industry with the lowest number of Paid Maternity Leave days, which was only 366. It is important to note that the number of Paid Maternity Leave days and the total number of Paid Paternity Leave days exhibit a positive correlation. Specifically, the 'Technology: Software' industry accounted for 29.49% of the total number of Paid Maternity Leave days.
•	The largest discrepancy between the number of Paid Maternity Leave days and the number of Paid Paternity Leave days was observed in the 'Technology: Software' industry, where the number of Paid Maternity Leave days exceeded the number of Paid Paternity Leave days by 1795.
•	At 921 days, the 'Technology: Software' industry had the highest aggregate number of Unpaid Maternity Leave, surpassing the number of the lowest industry, 'Technology: Manufacturing,' by 509.93% (with only 151 days). Notably, there exists a positive correlation between the numbers of Unpaid Maternity Leave and Unpaid Paternity Leave. The 'Technology: Software' industry accounted for 28.95% of the total number of Unpaid Maternity Leave.
•	The largest difference between the numbers of Unpaid Maternity Leave and Unpaid Paternity Leave was observed in the 'Technology: Software' industry, with Unpaid Maternity Leave exceeding the number of Unpaid Paternity Leave by 831.

Source of background image
•	https://www.moneyunder30.com/paid-maternity-and-paternity-leave 


