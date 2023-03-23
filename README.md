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


##Crowfunding Goal Analysis
--------------------------------------





