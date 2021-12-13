# A Complete Analysis of the Kickstarter Challenge - Module 1
Performing analysis on Kickstarter data to uncover trends
## Overview of the Analysis:
With 694 Successful campaigns reaching their goal over a 9 year period – I would say that is a major cause for celebration! I must also note that there is obvious room for improvement for campaigns that didn’t quite meet their mark - such as the 146 that set their goal amount for $1000 - $4,999!
## Analysis and Challenges
1. The first analysis was to identify which campaigns met their financial goals based on Successful, Failed, and ultimately campaigns that were Cancelled. 
#### There are a Total of 1,047 Theater based Campaigns:
- 694 Campaigns Successfully met their financial goal
- 353 Campaigns Failed to meet their financial goal

To determine this, I created groupings for the Goal amounts. Using the COUNTIFS function, I was able to pull data from the Kickstarter sheet to identify which campaigns were Successful, Failed, and Cancelled – although there were no Cancelled Campaigns for this analysis. After confirming the data pulled in correctly, I then calculated the percentages using the simple formula based on the Total Projects for each dollar grouping. This was completed for Successful, Failed, and Cancelled. 
	
The easiest way to present these findings to the client was to create a Line chart to visualize the data. The Line chart below illustrates the relationship between the Goal amount and the percentage of Successful, Failed, and Cancelled campaigns. 
<img width="800" alt="Screen Shot 2021-12-13 at 1 34 28 PM" src="https://user-images.githubusercontent.com/95304025/145868961-75d31549-9073-4eee-adad-638cbec722cb.png">

2. The second analysis identified how many campaigns were successful, how many failed, and which ones were cancelled based on their launch date. 

Not to anyone’s surprise I’m sure but there were more Successful campaigns in this analysis than the others. With a total of 839 successful campaigns over 9 years, the month of May ranked the highest with 111 and June not too far behind with 100. On the flip side, there were 493 failed campaigns, with May taking the #1 spot with 52.

To determine this, I created a Pivot Table using data from the Kickstarter worksheet. The ‘Parent Category’ and ‘Years’ data were used to help filter out information pertaining to Theaters and the months of the year from the Launch Dates. I also added the ‘Outcome’ to help sort out the Successful, Failed, and Cancelled campaigns. Once completed, I used the Pivot Line Chart to visualize the relationship between the Outcomes and the Launch Month.
<img width="800" alt="Screen Shot 2021-12-13 at 1 43 21 PM" src="https://user-images.githubusercontent.com/95304025/145869885-061e2f2a-b39f-4645-b558-9d5728d733e0.png">

## Conclusions based on 'Theater Outcomes by Launch Date" 
1.	Within the 9-year span of 2009 - 2017, the month of May had the most campaigns for both Successful and Failed. While January, had the most cancelled campaigns over the years. 
2.	Louise and her campaigns are doing very well, as the number of Cancelled campaigns is just a fraction - at a total of 37 - compared to the number of Successful campaigns- at 839.

## Conclusions based on 'Outcomes based by Goals'
1.	The projects that had a goal of Less than $1,000 were the most successful at meeting their goals with a 76% success rate.
2.	It’s harder to raise larger amounts of money as it shows that the goals higher than $19,999 most had more Fails than successes - in particular the goals greater than $50,000.

## Alternative Tables/Graphs for this Dataset
1.	We can use a Pie chart to show the Categories by Success, Failure, and Cancellation by year using the ‘Theater by Launch Date’ sheet.
2.	We can also add a chart to show which campaigns met their targeted deadline.
