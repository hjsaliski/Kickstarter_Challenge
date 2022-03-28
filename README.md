# Kickstarter_Challenge
Module 1 Challenge

  1) Overview of Analysis:
    For this project we made interpretations of this sheet of data for fundraising goals for different plays and helped answer specific questions based on our findings. Specifically, we looked at two modes, theater outcomes based on the date it was launched and theater outcomes based on their financial goals for each play. For the theater outcomes by launch date we created a pivot tables and organized data by whether or not it was Successful, failed, or canceled for each month of the year. We then created a line graph to better analyze the numbers of plays that were either successful, failed or canceled within each of these months. For the theater outcomes based on goals we organized data by number of successful, failed or canceled plays and their percentage compared to total projects in each categroy respectfully. The number of successful, failed or canceled plays were categorized by the financial goals of each play within certain ranges of funds needed for each play. For clarification, we used excel to count how many plays were either successful, failed or canceled that had a specific financial goal between a certain range of funds. 
  2) Analysis and Challenge:
  
     Analysis of outcomes by launch date:
     For this analysis we formatted a pivot table to include outcome of plays based on the month of year they were launched.  What we have discovered from our analysis of the theater outcomes by launch date is that we can see there is an uprise in plays 
     in the spring and summer months and a downfall of plays in the fall and winter months. From Apr-Jul the success rate for each month 
     averages around 62-65%. We can see that the Dec had the worst success rate at only 49%. We showed this in our graph too by marking   the success rate and measuring how it begins to decline as the summer months end and the winter months begin. We can also see that the number of failed plays where in the summer months, number of failed plays begin to be fairly consistent while number of successful plays begin to get higher. Canceled plays throughout the year stay fairly consistent except in October where there were no canceled plays. 
     
     Analysis of outcomes based on goals:
      For this analysis we made a table comparing the number of plays that were either successful, failed, or canceled within a certain goal range. We then measured the percentage of each of these outcomes from the total amount of plays in each goal range. We did this by using a COUNTIFS function and using this code to filter each category for specific outcomes and play type. We set the goal ranges for each outcome and play type in quantities of $5000. We then created a line graph to see any relationships in goal range and outcome. We can see that as funding for the plays and the goals increase, the rate of success actually begins to drop and the rate of failure begins to grow. We can see that plays with goals under $5000 have a 73% chance of being successful and anything over 50k has an 88% chance of failure or 13% chance of success. 
     
     Challanges and difficulties encountered:
     Most of my challenges in the outcome based on launch date came from needing to know how to create the pivot table for the correct analysis. There are so many combinations 
    
  3) Results:
      Two conclusions I can make about the Outcomes on Launch date is that during the summer months there were significantly more plays held in general. From April to August we saw most plays being held with a slight drop when fall and winter began. We can also see that in the spring time it seems as though there are more successful plays compared to the total number of plays for each month. 
      
     For the outcomes based on goals we can see that the most successful plays were mostly in the smaller goal bracket, anything under $5000 had at least a 73% success rate. We can also make the judgement that as the goals of each play increase the chance of success begins to go down and the chance of failure begins to go up. we can see where in-between 35k and 45k there is a spike in the opposite direction but with such little sample space we cant make the conclusion that this range is totally successful. 
     
     Some limitations of this dataset may include a lack of ample sample space for each outcome goals we were looking for. Especially in the outcome based on goals we mght have a better analysis if there were more of an equal amount of plays in each goal range. This way we wouldnt be making concusions on whether or not 40000$ goals were actually successful based on 1 or 2 plays. Another limitation could be the time frame in which the data was comprised. Widening the scope of data can improve more accurate results when calculating average and percentage of plays success over a broader timeline. The Limitations on this dataset can be measured by what kind of data we are given and what we are trying to do with that data. So we are limited to a number of fields for example the name of the play how much money it raised and whether or not it was successful in the timeframe it was conducted. But if we had more data like _How_ the money was raised or what city the play was conducted then we would have other criteria to judge the data on.  
     
      We could add another aspect to the outcomes by date chart having total number of plays with each section of successful, failed or canceled plays because as it may seem as though successful plays are dropping as the year progresses so is the total number of plays. Another Table we could have made could have been more specific in the outcome of goals tab. we could have made a smaller range and had more specific findings.
