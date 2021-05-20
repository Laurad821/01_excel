# 01_excel - Assignment

## Purpose & Table Findings

The purpose of the analysis on 'Theater outcomes based on launch date' was to determine during what time of year campaigns were most successful. The data showed for the months of May and June, theater sales were at their highest compared to the rest of the year. The purpose of 'Outcomes based on goals' was to determine the amount of plays that were successful, that failed, or that were canceled based on the goal dollar amount.
In the first analysis for 'Theater outcomes based on launch date', I created a pivot table from the Kickstarter worksheet using the years, months, outcomes and category columns. From the pivot table I inserted a line graph to see a clearer representation of the data. ![Picture1](https://user-images.githubusercontent.com/83786920/118834099-f8dd0300-b88f-11eb-817e-32dec9a34e95.png) Fortunately, I did not encounter a challenge on this part, but if the data from the Kickstarter worksheet did not have the correct formulas for the date conversion columns and the columns for parent category and subcategory were not inserted, then the pivot table would have extracted inconsistent information. The data must be consistent for the pivot table to work. There was a rather frustrating challenge I faced using the CountIFS function for the 'Outcomes based on goals' tab. I failed to manually type the criteria I needed to use for this formula following the criteria range. I thought that by filtering and selecting the column from the Kickstarter worksheet would pull the data into the formula without having to type "successful", "plays". Once I figured it out, it was simply chganging the outcomes and the goal amounts for the "failed" and "canceled" columns. A line graph was created to visualize the  outcomes based on goal amounts ![Outcomes_vs_goals](https://user-images.githubusercontent.com/83786920/118836489-e237ab80-b891-11eb-94d3-e684ea6b883f.png)

## What are two conclusions you can draw about the Theater Outcomes by Launch Date?

  Two conclusions that can be drawn about the Theater 'Outcomes by Launch Date' is the    first being that May and June are the best months to launch theater campaigns. May had a total of 111 successful campaigns and June with a total of 100 successful campaigns. The second conclusion is October was the only month with zero cancellations.

## What can you conclude about the Outcomes based on Goals?
  
  There were 534 total projects with a goal range of $1000 to $4999 that had 388 successful campaigns, whereas the second highest had a total of 186 total projects ranging less than $1000. Louise had fewer campaigns that were $5000+. Although, the other ranges were above $5000, there were more successful projects than canceled ones at a higher price, even though the project count was less than 100. To conclude, Louise should have kept her goals at lower rate between $500 to $10,000.
  
## What are some limitations of this dataset?
  
  The goal amounts were set too high and the question of why theater campaigns were most successful in May.
  
## What are some possible tables and/or graphs that we could create?
    
  N/a. The tables/graphs used were appropriate for understanding the data.
    
