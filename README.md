# Cyclistic Project - Overview
This project was part of the Google Data Analytics Certification that I completed in January, 2022. The dataset provided by Google, contains records of a bike share company for the past 12 months, grouped together for each month of 2021.
## Background
Cyclistic is bike share company that has two types of users - annaual members and casual riders. The goal of the project is to analyze the data and compare the two types of users. It has been determined that the annaual users are more profitable for the company. With the help of the analysis a new marketing strategy would be devised to convert the casual riders into annual members.
## Methodology
The data was provided in csv format. Microsoft Excel was used to clean and analyze the data and Tableau to vizualize the results. 
After perusing the data, the Lats and Longs were removed as they were not required for the analysis.
Formatted the data to make it more presentable and easier to see
  - Fixed column widths
  - Made headings bold
Quite a few Starting and Ending Station values were missing. Those columns were removed along with the station id column as they weren't required for the analysis.
Ride id column was removed.
Moved all data to one file with each month's data in individual tabs.
Checked for any missing values.
Added ride-length column and calculated the length of rides.
Added day-of-week column and calculated day of the week.
Two rows in the month of March were removed because the end time was earlier than the start time.
One row was removed because the bike was gone for 22 days.
## Analysis
1. Casual users volume increases during the summer months and peaks in the month of July.
2. Annaual members use bikes for commute. This fact is supported by usage times of 7am-8am and 5pm-6pm.
3. Febraury has the lowest volume, perhaps because of the weather. The program is based in the city of Chicago.
4. Casual users have average ride lengths of 32 minutes whereas the annual users have an average ride length of almost 14 minutes.
5. Casual users mostly take rides over the weekends.
## Recommendations
1. Introduce weekend only memberships.
2. Introduce memberships that reward longer bike trips.
3. Run promotional campaigns during the summer months.
## Data Vizualizations
The compelete vizualizations can be viewed on the Tableau Public website using the link below
[https://public.tableau.com/app/profile/saad.ijaz2421/viz/CyclisticCaseStudyGoogleProject/UsageDashboard]<br/>
![Tableau Dashboard](https://github.com/saadijaz1/Exploratory-Data-Analysis-Project---Cyclistic/blob/main/Cyclistic.png)
## Interesting Facts
This was the first time I realized the limitations of spreadsheet programs. Excel only supports 1,048,576 rows whereas Google Sheets supports only 5 million cells. Initially I wanted to have all the data on one sheet but it wasn't possible so I kept the monthly data on separate tabs.  
