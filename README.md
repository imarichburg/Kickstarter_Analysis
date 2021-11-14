# Kickstarter_Analysis
Performing analysis on Kickstarter Data to discover trends

### Overview
Analysis of Kickstarter Data set to help a Playwright gain insight on the success of creative projects with similar profiles.  Analysis includes data analysis and visualizations to support the conclusions.

### Purpose
Kickstarter is an online platform that allows projects to create campaigns funded by individual donors.  Louis is a Playwright that created a Kickstarter campaign to fund the play “Fever”.  The 28-day long campaign was only able to raise 86% of the $2885 goal.  This purpose of this analysis is to understand similar but successful campaigns to provide insight for Louis.

### Analysis of Outcomes Based on Launch Date
In order to analyze the Kickstarter campaign outcomes based on Launch date, the data had to be converted and sorted.  Dates were converted to readable formats so they could be filtered and visualized.  A pivot table was used to compare theater campaigns by month of launch date.  More of the theater campaigns were successful than failed.  The highest number, 111, of successful campaigns are launched in May.  The lowest number, 37, of successful campaigns are launched in December.  


### Analysis of Outcomes Based on Goals
The COUNT-IFS function was used to count the Number Successful, Number Failed, Number cancelled in each Goal range.

### Challenges and Difficulties Encountered
The greatest challenge came with the “Outcomes Based on Goals” data and Line graph.  The use of compound inequalities in the COUNT-IFS function produced an error.

### Results
Outcome based on Goals suggest that Goal amounts less than $5000 have a higher success rate.  The Fever play only raised 86% of their goal.  The campaign for “Fever” was launched in June. According to the "Outcome Based on Launch date", Fever would have had more successful if the Kickstarter campaign was launched in May.
![image]()
