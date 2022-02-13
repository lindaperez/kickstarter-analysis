# An Analysis of Kickstarter Campaigns

## Overview of Project
### Purpose

The project consist in analyze a dataset to generate insights. Based on a excel of Crowdfunding campaigns data with 4113 rows, determine the specific factors that influence the creation of a Play campain with an estimated budget of $10.000. Most specifically, generate sheets that serves as a tool to answer a variety of possible questions decisive to create a crowdfunding campaign.

## Analysis and Challenges

Before have started developing a solution, it was important to think about possible questions that should be answer. These questions came up during the analysis of the project, the requirements and the raw data:

1. When is the best time to lauch the Play campaign. 

2. Is it an strategic decision to create a crowdfunding with that particular budget, should the budget be less or more? Are there any relationship between the goal and successful campaigns? 

3. Create the campaign in a different country may help funding the goal budget?

4. How long would be the campaign?

 
Part of the challeging things could be to understand the business, the requirements and how to get to the solutions without the module guidance. 



### Analysis of Outcomes Based on Launch Date
The way to solve the exercise was following the steps mentioned in the Excel Module. 

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
https://github.com/lindaperez/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png




### Analysis of Outcomes Based on Goals






### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?









The view Analysis of Outcomes Based on Launch Date provides the way to answer our second fundamental question that is, What is the best time to create a "Play" Crowdfunding campaign. 

The way that this view answer this questions and some others is through a pivot table and a pivot chart. 

* The pivot table shows a pinpoint in May that represent the month where the Play campaigns have overcomed most successfully over the years with 111 campaigns. 


The best way to compare how are the months balanced over the years is the pivot chart.

* The pivot chart image "Theater Outcomes Based on Launch Date" shows a Line Chart with several pinpoints one of them represents the most succefull month to launch a category that is May with 111, some others worst escenarios like may and october with 52 and 50 failed campaigns respectively.


Definitely, It may help to define when the Play campaign should be launch based on the history of the campaigns. 




The view Analysis of Outcomes Based on Goals provides the way to answer our thrid fundamental question that is, Will be able the campaign to reach the goal spected, $ 10.000, is it too much to launch the campaig? Is there any correlation betweeen the goal amount and the succefulness of Play campaigns?

To answer this questions It was designed a table with the range of possible Goals or bugets and the amount of the successful, failed, canceled projects and their percentages. 




Perform an analysis of Crowdfunding projects to uncover hidden trends.
Analyze and create insights based on the data collected from Crowdfunding projects
### Purpose
Make conclusions that can show up the trends 

### Questions 



From a previous analysis it was possible to conclude that the most successful campaigns were over the years the "Plays" campaigns. Then, sounded very acertive to launch a campaign about that subject. 

Now its time to answer the remain of the previous questions.