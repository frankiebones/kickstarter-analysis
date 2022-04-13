# Kickstarting with Excel

## Overview of Project   

### Purpose
To provide Louise with insight as to how other Kickstarter theater campaigns performed based on when they were launched as well as the percentage of plays that were either successful or failed based on their goal amount. This may help Louise make a better educated decision regarding their next Kickstarter campaign in the hopes that they do not fall just $400 short of their goal once again.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The dataset was filtered to include only Theater campaigns then grouped by month for each of the outcomes. 
![Outcomes_Based_on_Launch_Date](https://user-images.githubusercontent.com/15967377/163271349-08c610d6-9525-4c27-811e-6fd0c704fe77.png)

### Analysis of Outcomes Based on Goals
The dataset was divided into tiers based on the goal amount and summarizes the percentage of successful, failed and canceled Plays campaigns in a line graph.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/15967377/162595253-77d442a1-67dd-45f5-a02a-9f3ad10b5e8c.png)

### Challenges and Difficulties Encountered
Luckily for Louise, I didn't have trouble grouping the data to provide visualization. 
I did however, spend quite some time trying to determine how to fill down the tier goal system in the Outcomes Based on Goals sheet rather than manually creating that whole list. Best I could come up with was to build it out over 3 columns with "to" being the middle column then concatenating all after filling down the values. Would love to know if there is a better way for more tedious table referencing like that. Almost seems that the starting and ending tiers of the goal bins could have each been their own column and the COUNTIFS could have referenced the tier amounts so it would be more dynamic if the tiers were to change.
I also encountered some slight frustration and dissatisfaction with the color of the lines on my original Theater_Outcomes_vs_Launch graph and have since updated it but am unsure how to commit those changes to github.

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. May through June are the best months to launch a theater campaign.
2. December was close to even regarding success vs failure.

- What can you conclude about the Outcomes based on Goals?  
The majority of plays have a goal of under $5000 which also makes them more likely to be successfully funded.

- What are some limitations of this dataset?  
It does not account for currency conversion. While there are only a few campaigns from Hong Kong or Norway, there are over 20 from Sweden when combined are likely to disrupt some statistics if not accounted for.

- What are some other possible tables and/or graphs that we could create?  
I was curious to see if there were particular categories that were most likely to exceed their goal and it turns out Louise is in a good place if they attempt to launch another play campaign as 607 plays surpassed their goal amount. 
![Exceeded_Goal](https://github.com/frankiebones/kickstarter-analysis/blob/main/exceeded_goal.png?raw=true)


