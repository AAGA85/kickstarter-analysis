# An Analysis of Kickstarter Campaigns

## Overview of Project
Excel is a powerful tool where we as users and data analysts can organize and calculate data to make information easier to view. The scope of this project was to execute some of the functions that this tool has available to help Louise to get the information that she needs to answer specific questions by taking her through the data using visualizations and the insights that we got from this analysis. 

Louise is a playwriter and she has been crowdfunding a campaign to fund her play, Fever and now she is very close to the fundraising goal. The data base used for this study is called Kickstarter. This data base includes tons of data related to similar crowdfunding projects; we need to figure out the way to get the information that she needs to know how different campaigns fared in relation to their launch dates and their funding goals.  

## Analysis and Challenges

### Overview of the analysis: Project’s funding performance in relation to their launch dates

In order to have a clear understanding of the data, it was required to uncover the trends behind the numbers. The key information to do that was the launch dates and based on this data then we can account the number of projects based on their performance. The easy way to provide this information was creating a graph (pivot table) and then filtering by the same Louise’s project category.

Here a visualization of the origin of the data and how it was alocated in the PivotTable Fields

![Years and filters](https://user-images.githubusercontent.com/106939511/174207632-c1daf75f-ecd1-4470-abd0-2ea7553fd6fc.PNG)


### Overview of the analysis: Project’s funding performance in relation to their funding goal

For this analysis I used the function COUNTIFS that help me to count the number of cells that meet multiple criteria in different ranges. To simplify the analysis, the first step was to split the multiple goals in ranges, then using the COUNTIFS, I was able to count the same subcategory projects as Louise’s project, per ranges and per outcome.

Here a visualization of the origin of the data and how it was alocated in the new table to get the graph Outcomes Based Goals

![countifs](https://user-images.githubusercontent.com/106939511/174208159-e8e6fb92-d84b-4158-9395-4bcfba4c7970.PNG)


### Challenges

Excel has been a powerful tool to develop the required analysis and get the answers that Louise is expecting but it is important to highlight that Excel could be limiting too. The first challenge as user of Excel is the human error, because a lot of typos can be occurred as misspell words or mess up punctuation accidentally. The second challenge is the clear understanding of the parameters or arguments that every type of function needs to run properly. Sometimes the descriptions of those arguments are ambiguous. Finally, the capability of visualization when complex data modeling. If multiple variables are needed to explain the story in one single graph, Excel is limited then the user must split the analysis on several graphs and that could be difficult to see the dependability of certain variables. 


## Results

**What are two conclusions you can draw about the Theater Outcomes by Launch Date?**
Based on the analyzed data, the report shows that the most successful theater projects are launched in May and June but also the rate of failed projects is high in the same months. Nevertheless, the variability of failed projects is minimal across the year. The month with the lowest number of successful projects is December then this month should be avoided to launch a project.

**What can you conclude about the Outcomes based on Goals?**
Based on the analyzed data, the line chart shows that projects with a funding goal less than $5000 have a high rate to be successful but projects over $45000 have the highest rate to fail. 

**What are some limitations of this dataset?**
The limitation of this dataset is the capability to match several variables in one single graph. Then the data need to be split on several graphs and then the user or analyst would need to match the different results to get the big picture. Besides that, the existed templates that we can use to explain the data are not intuitive, so the user hast to spend a lot of time correcting the format of the template and verifying data entry to get the expected visualization of the data. 

**What are some other possible tables and/or graphs that we could create?**
We could create a pie chart to show the rate of all types of subcategories and get the most popular type of theater project also we could create a pivot table and linear chart in order to show what type of subcategory is the most successful the last 5 years. 

