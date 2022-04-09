# kickstarter-analysis
Performing analysis on Kickstarter date to uncover trends
## Overview of Project
Data analysis for several hundred crowd funding projects is performed to help Louise with her project campaign by looking into how different campaigns fared in relation to their launch dates and their funding goals. Using the crowd funding dataset, we visualize the campaign outcomes based on their launch dates and their funding goals. 
### Purpose
The purpose of the project is to use the knowledge of the pivot tables and graphing in Excel to visualize the campaign outcomes based on the launch date. Additionally, Excel is used to visualize the percentage of successful, failed, and canceled “theater plays” based on the funding goal amount. 
## Analysis and Challenges
The first analysis uses the pivot tables to present the outcomes of the “theater/plays” projects during the year.  The column and the row fields in the pivot table includes the “outcomes” and the “converted dates”, respectively.  The pivot table is filtered based on the “parent category” and the lunched “year”.  The total number of successful, failed, and canceled projects are presented. 
### Analysis of Outcomes Based on Launch Date
A subset of total crowd funding projects in “theater” category, and “plays” subcategory are selected to be analyzed. The total number of successful, failed, and canceled projects versus launch date is presented in Table 1 and Figure 1.

<div align="center"> 
  
**Table1: Theater plays crowdfunding outcomes**

![image](https://user-images.githubusercontent.com/103223944/162588544-eb7ab059-c22a-40d2-9239-7be3534b0105.png)

![image](https://user-images.githubusercontent.com/103223944/162588571-e074a291-8cb9-4042-b966-93fe0725c2cb.png)

**Figure 1: Theater plays crowdfunding outcomes** 

<div align="left"> 
  
### Analysis of Outcomes Based on Goals
In this analysis, we classified the projects based on the size of the funding goal and tried to discover if there is any correlation between the chance of the success or failure of the project and the amount of funding “goal”.  The results are presented in Table 2 and Figure 2. 

<div align="center"> 

**Table 2: The outcome of the crowdfunding projects based on the funding goal**
  
![image](https://user-images.githubusercontent.com/103223944/162588931-948f7dfa-06fe-4b05-8fab-6db439313a75.png)

![image](https://user-images.githubusercontent.com/103223944/162588964-7e416c90-ed81-4e8b-9644-5144a685bc85.png)

**Figure 2: The outcome of the crowdfunding projects based on the funding goal**
  
<div align="left"> 
  
### Challenges and Difficulties Encountered
The second analysis uses the Excel “countifs” function to present the number of successful, failed and canceled “theater plays” based on the funding goal amount. The challenge was to use the combination of “contifs” function and “filtering” option as instructed in the Deliverable 2 of module 1. It turned out that the “countifs” function ignores the filtered data. Therefore, multiple criteria were needed to be defined within the “countifs” function to achieve the goal of the analysis. 
## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?

As presented in Figure 1, the difference between the number of successful and the failed projects is the highest around May and Jun indicating a higher chance of success during this period of the year.  While the average percentage of the successful projects is higher for these two months (~ 66%), the average rate of failed projects is about 30% which is smaller than the average percent of the failed projects throughout the year (~ 37%). The higher percentage of the successful projects (~ 66%) combined with the lower percentage of the failed projects (~ 30%) during this period (May and Jun) compared to the rest of the year indicates that this is the best time of the year to launch the project. Interestingly, the average percentage of the canceled projects is about 2.5% during this period of the year compared to the average of 3% for the whole year.  
  
- What can you conclude about the Outcomes based on Goals?

As presented in Figure 2, there is no linear relationship between the funding goal amount and the chance of success. Clearly, smaller projects with funding goals < $5,000 have a high chance of success (>60%), but also projects with funding between $35,000 and $45,000 also have a relatively high chance of success (average of ~60%). However, it should be noted that the number of projects significantly reduces as the funding goal amount increases. Therefore, one needs to be cautious to generalize the observations. Additionally, the projects with funding goals greater than $45,000 have a very high chance of failure. 
  
- What are some limitations of this dataset?

One of the limitations of the dataset is that it’s biased towards projects with the smaller funding goal amounts and therefore, it is hard to generalize trends for mid-size and large projects.
    
- What are some other possible tables and/or graphs that we could create?
  
For the first analysis, we could have generated the percentage plots for the successful and failed projects. Also, the percent difference between the successful and failed projects would have been helpful.  
