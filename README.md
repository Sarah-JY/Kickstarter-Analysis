# Kickstarter-Analysis
## Overview of Project:
This project aims to analyze how different campaigns work in relation to their launch dates, their funding goals for plays and the theater.  To achieve this, I developed two charts: Theater Outcomes Based On Their Launch Date and Outcomes Based On Goal.

### Analysis and Challenges:
In the Theater Outcomes by Launch Date analysis, I used the Kickstarter dataset to analyze and prepare the data and update the data’s format.  Then I created a pivot table with different categories.  Next I filtered it by the categories (theater) and year, the column labels only showed successful, failed, or canceled. Afterwards, we want to discover the correlation between launch date and outcomes for the theater.  Finally, we visualized the data relationship between outcomes and launch month.

![image](https://user-images.githubusercontent.com/103588178/166174976-9ece0784-ff4a-40f7-8407-6ea63da00542.png)

In the Outcomes Based on Goals, I also used the Kickstarter dataset. I created 8 columns to hold the data. They are Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed, Percentage Canceled. Then I used the COUNTIFS function to populate the data for each player. Additionally, I sumed the project and calculated the percentage of the outcome.  Next, we will visualize the relationship between the goal-amount range and percentage of successful, failed, or canceled projects.

![image](https://user-images.githubusercontent.com/103588178/166178982-1058eb69-e4a3-4512-8d07-4b3150c860fc.png)

#### Challenges and Difficulties Encountered: 
The first challenge I faced was to convert the unix timestamp to readable standard date format. 
Another challenge I faced is deleting the data sheet for Successful US Kickstarters, Failed US Kickstarters will affect the data on the Outcome based on Goals sheet.  Therefore, I decided to use the COUNTIFS function for all the ranges of data from the original dataset. It took me some time to create the equation and get the correct result.  

##### Results:
In the Theater Outcomes by Launch Date analysis, I found the theater is the most successful campaign.  The most successful month of the Kickstarter campaign was launched in May and June; all outcomes had roughly the same number of failed campaigns launched. 
In the Outcome based on Goals, I found the plays with a goal that has less than $5,000 with a 73% success rate. 
Therefore, it is best to launch the theater campaigns in May and June with less than $5000.  

###### Data Limitation:
The data loaded in with a different currency unit, would be more accurate to put in the same unit.  Also, the theater outcomes are based on launch date, but the plays outcome based on the goals.  

####### Additional Tables or Graphs:
The other tables or graph we could consider to review more is the different subcategory for theather in US

![image](https://user-images.githubusercontent.com/103588178/166179112-bb62f592-e5f2-4cbf-8563-1f3252b5fa6a.png)
