# STARTERBOOK
PERFORMING ANALYSIS ON STARTERBOOK DATA TO UNCOVER TRENDS

#Overview of Project: Explain the purpose of this analysis.

The data ustilized in this project displays shows/series, their description along with the monetary goal they hoped to acheive and how much they actually acheived    (pledged). Based on the monetary value they acheived the outcomes are decided whether successful, failed, canceled or live. Each of the show has it's own category (i.e. films, games, food etc) and their subcategory (i.e. televion, science fiction,etc). 


# Analysis and Challenges: Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered.

  ## Analysis:
  ### Theater Outcomes by Luanch Date 
 ![Theater Outcome 1](https://user-images.githubusercontent.com/104603094/168200607-98588d07-e4b9-4a8d-8697-b7290d7f2755.PNG)
Created Pivot table with the date of launch (months) vs summation of the count of outcomes (successful, failed and canceled). while filtering out theater as the parent category. With the help of Pivot table analyze got a graph that displays the total count of outcomes vs the launch months. For geting the launch date correct, date conversion needs to be doen using the epoch converter.
### Outcomes based goals
![theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/104603094/168203018-9ac37ecb-9252-4969-9d89-9a1f09752fbf.png)
Created a table with several ranges displaying the goal (dollar amount) and number of successful, failed, canceled outcomes. to get this count used the COUNTIFS() FUNCTION. and got the respective percentages of the outcomes in each dollar value range.


## Challenges: The excel sheet displays a lot of information and operating with so many coloums gets confusing. The data is extensive and working on it required dliligence. So it was important to understand the data given and what was being asked. Tried using all functions explained in the module 1 and used Microsoft google's help as well.
  
     
# Results: Answer the following questions in complete and coherent sentences.
## What are two conclusions you can draw about the Theater Outcomes by Launch Date?
  1. the most successful outcomes for theater category of shows was in the month of May in all the years.
  2. the most canceled shows were in the month of January in all the years.
  
## What can you conclude about the Outcomes based on Goals?
  1. 76% outcomes were successful when the goal was 1000$ or lesser.
  2. 80% outcomes failed  when the goal was between $25,000 to $29,999.

  
## What are some limitations of this dataset?
In several sections there were daat points missing, so when an operation like ROUND() is applied, an error emerges saying DIV0.
This is a limitation of the dataset.

## What are some other possible tables and/or graphs that we could create?
Instead of line graph we can utilize pie charts, histograms, bar charts and treemaps.
