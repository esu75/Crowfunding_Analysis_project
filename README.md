### Crowfunding_Analysis_Project_using Excel
---------------------------------------------
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success.

To receive funding, the project must meet or exceed an initial goal, so many organizations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success. For this project, you will organize and analyze a database of 1,000 sample projects to uncover any hidden trends.
Here is the step-by-step explanation of the analysis process:

step 1: 
Used conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live and created a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.
step 2:
Used conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale started at 0 with a dark shade of red, and it transitioned to green at 100 and blue at 200.

step 3:Created a new column called Average Donation that uses a formula to find how much each project backer paid on average.

step 4: Created two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.
![image](https://user-images.githubusercontent.com/118146659/227330391-5c146701-21bb-4257-9108-bec2d6e24700.png)

step 5:
Created a new sheet with a pivot table that analyzes your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

![image](https://user-images.githubusercontent.com/118146659/227333499-6b65ca3e-a61b-42dc-8a45-2b16f1863193.png)

step 6:
Created a stacked-column pivot chart that can be filtered by country based on the table  created in step 4.

![image](https://user-images.githubusercontent.com/118146659/227334013-c54d3b34-02fb-4107-a060-b89843f58f2f.png)

step 7:
Created a new sheet with a pivot table that analyzes the initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

step 8: 
Created a stacked-column pivot chart that can be filtered by country and parent category.

step 9: 
converted deadline and launched_at Unix timestamps to normal date and created new columns: Date Ended Conversionand and Date Created Conversion 


step 10: 
Created a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years.From the created pivot table, a pivot-chart line graph that visualizes this new table has been created.

![image](https://user-images.githubusercontent.com/118146659/227337473-cdc71b77-4588-4c69-a9d4-c9837bf5983d.png)


Crowfunding Goal Analysis
--------------------------------------
step 11:
Created a new sheet with 8 columns: Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed, and 
Percentage Canceled
step 12: 
In the Goal column, created 12 rows with the following headers: Less than 1000, 1000 to 4999, 5000 to 9999, 10000 to 14999, 15000 to 19999

20000 to 24999, 25000 to 29999, 30000 to 34999, 35000 to 39999, 40000 to 44999, 45000 to 49999, and Greater than or equal to 50000

step 13:
Using the COUNTIFS() formula, counted how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populated the Number Successful, Number Failed, and Number Canceled columns with these data points.

step 14:
Added up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, found the percentage of projects that were successful, failed, or canceled per goal range.

step 15: Created a line chart that graphs the relationship between a goal amount and its chances of success, failure, or cancellation.

![image](https://user-images.githubusercontent.com/118146659/227350579-f7e1379c-ab41-4478-9df6-a5a26ccae3f1.png)

Statistical Analysis
--------------------

Most people would use the number of campaign backers to assess the success of a crowdfunding campaign. Creating a summary statistics table is one of the most efficient ways that data scientists can characterize quantitative metrics, such as the number of campaign backers.

For gaining an in-depth understanding of campaign backers, evaluated the number of backers of successful and unsuccessful campaigns by creating a summary statistics table.

step 16:
Created a new worksheet in the workbook, and created one column for the number of backers of successful campaigns and one column for unsuccessful campaigns.

![image](https://user-images.githubusercontent.com/118146659/227355568-0843a428-6aad-4e43-8ecd-32a9e5b14561.png)


step 17:
Using Excel evaluated the following values for successful, and unsuccessful campaigns:

The mean number of backers

The median number of backers

The minimum number of backers

The maximum number of backers

The variance of the number of backers

The standard deviation of the number of backers

![image](https://user-images.githubusercontent.com/118146659/227359263-6964eb80-3a3a-4aa1-a2cb-290058102d1b.png)


step 18:

Using the data determine whether the mean or the median better summarizes the data. also, determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why 
step 19:
An excel box plot was ploted to analyze step 8 questions:

![image](https://user-images.githubusercontent.com/118146659/227358588-cc1d3f41-c1fd-4b93-ba3c-78aaf20b0bae.png)








