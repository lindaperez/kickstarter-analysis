# An Analysis of Kickstarter Campaigns

## Overview of Project
### Purpose

The project consist in analyze a dataset to generate insights. Based on a excel of Crowdfunding campaigns data with 4113 rows, determine the specific factors that influence the creation of a Play campain with an estimated budget of $10.000. Most specifically, generate sheets that serves as a tool to answer a decisive variety of questions for the creation of a crowdfunding campaign.


## Analysis and Challenges

Before to start developing a solution, it is important to think about possible questions that should be answer. These questions generally come up during the analysis of the project, the requirements and the raw data:

1. When is the best time to lauch the Play campaign? 

2. Is it an strategic decision to create a crowdfunding with that particular budget $10.000, should the budget be less or more? Are there any relationship between the goal and successful campaigns? 

3. Create the campaign in a different country may help funding the goal budget?

4. How long should be the campaign?


### Analysis of Outcomes Based on Launch Date

The way to solve this case is thinking how to answer the questions above, especifically. When is the best time to launch the Play campaign? We inmediatly thought about, how to get a relation between the launch_date and the outcomes. We were able to think that we needed to display the months and see how many projects were successful, failed or canceled over the years.
After it, we could think about that filter by the parent category was very help us to have a more acurate answer.


	The process to solve it was following the steps in the Excel Module, here some images:

	1. Rename the StarterBook.xlsx

![This is an image](https://github.com/lindaperez/kickstarter-analysis/blob/main/Resources/renamed.png)

	2. Create a folder called “resources”.
	3. In the Kickstarter_Challenge.xlsx workbook, create a new column labeled "Years."
	4. In the "Years" column, use the YEAR() function to extract the year from the “Date Created Conversion” column.

![This is an image](https://github.com/lindaperez/kickstarter-analysis/blob/main/Resources/yearsFormula.png)


	5. Create a pivot table from the KickStarter worksheet, and place the pivot table in a new sheet.
	6. Label the sheet "Theater Outcomes by Launch Date."
	7. Filter the pivot table based on "Parent Category" and "Years."
	8. Place the appropriate pivot table fields in the columns, rows, and values.
	9. Filter the column labels to show only "successful," "failed," and "canceled."
	10. Confirm that your pivot table.

![This is an image](https://github.com/lindaperez/kickstarter-analysis/blob/main/Resources/9pivotTable.png)


	11. Filter the "Parent Category" to show only the data for "theater."
	12. Sort the campaign outcomes in descending order so "successful" is first.

![This is an image](https://github.com/lindaperez/kickstarter-analysis/blob/main/Resources/descendingOrder.png)

	13. Confirm that your final pivot table looks correctly.

	14. The final pivot table with successful, failed, and canceled theater Kickstarter campaigns by month.

![This is an image](https://github.com/lindaperez/kickstarter-analysis/blob/main/Resources/pivotTable.png)

	Create a line chart from the pivot table to visualize the relationship between outcomes and launch month.

	Add a title to the line chart, and save it as Theater_Outcomes_vs_Launch.png to the resources folder.

![This is an image](https://github.com/lindaperez/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)




### Analysis of Outcomes Based on Goals


For this case, we thought about the next question that was. Is it an strategic decision to create a crowdfunding with that particular budget $10.000, should the budget be less or more? Are there any relationship between the goal and successful campaigns? 
Initially the proccess to solve it was followint the steps in the Excel module, but during the process we could realize that we were getting the answer displaying the outcomes successful, failed, canceled with the the goal ranges or budget ranges. This help to understand that how many projects were successfull with every range of budget for example, with a budget between $10.000  and $14999 there were 39 successful projects over 72. To have a most readible result we took the percetage succefull, failed and canceled. The we could understand that with a budget between $10.000 to $14999 the percetage of sucefulness would be around 54% and the failness 46%.  


The process to solve it was following the steps in the Excel Module, here some images:

	1. In the KickStarter sheet, create a new sheet and label it "Outcomes Based on Goals."
	2. In the new sheet, create the following columns to hold the data:
	- Goal
	- Number Successful
	- Number Failed
	- Number Canceled
	- Total Projects
	- Percentage Successful
	- Percentage Failed
	- Percentage Canceled

	2. In the “Goal” column group on the goal amounte.

	3. Goal column with twelve rows of ranges

![This is an image](https://github.com/lindaperez/kickstarter-analysis/blob/main/Resources/1wholeView.png)


	4. Use COUNTIFS() functions 

![This is an image](https://github.com/lindaperez/kickstarter-analysis/blob/main/Resources/countIf.png)

	5. Use the SUM() function to populate the "Total Projects" column with the number of successful, failed, and canceled projects for each row.

![This is an image](https://github.com/lindaperez/kickstarter-analysis/blob/main/Resources/5sum.png)


	6. Calculate the percentage of successful, failed, and canceled projects for each row.
	7. Create a line chart titled "Outcomes Based on Goal" to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis.
	8. Confirm that your line chart looks like the following, and save it as Outcomes_vs_Goals.png to the resources folder.


![This is an image](https://github.com/lindaperez/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)



### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	May is the best month to launch a Play campaign. After this the second one would be between April, May and somedays of June. After May the amount of outcomes start falling unitl January of the next year where they start increasing again. 

	The view "Analysis of Outcomes Based on Launch Date" provides the way to answer our first fundamental question that is, What is the best time to create a "Play" Crowdfunding campaign based on the Parent category "Theater" over the years from 2009 and 2017. 

	The way that this view answer this questions and some others is through a pivot table and a pivot chart. 

	* The pivot table shows a pinpoint in May that represent the month where the Play campaigns have overcomed most successfully over the years. 


	The best way to compare how the months are balanced over the years is the pivot chart.

	* The pivot chart image "Theater Outcomes Based on Launch Date" shows a Line Chart with several pinpoints one of them represents the most succefull month to launch a category that is May with 111 over 166, some others worst escenarios like december where the amount of sucessfull campaign is very short around 35 over 75.


- What can you conclude about the Outcomes based on Goals?


	The view Analysis of Outcomes Based on Goals provides the way to answer our second fundamental question that is, Will the campaign be able to reach the goal spected, $ 10.000, is it too much to launch the campaig? Is there any correlation betweeen the goal amount and the succefulness of Play campaigns?

	To answer this questions It was designed a table with the range of possible Goals or bugets and the amount of the successful, failed, canceled projects and their percentages. 

	The countIf function helped to filter the dataset 


- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
