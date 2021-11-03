# Kickstarting with Excel

## Overview of Project
Kickstarter analysis using data from 2007 to 2019 in relation to their launch dates and their funding goals.  

### Purpose
To help Louise learn about the success and failures of other fundrasers in relation to their launch dates and their funding goals. 

## Analysis and Challenges
The analysis done was to use kickstarter data from 2009 t0 2017 across many dicisplins.  Some challenges were deciding which sub categories were relevant comps and what time frames were to be used.  These were overcome by just considering the theatre category and to use all the data across all time.

### Analysis of Outcomes Based on Launch Date
To first study the outcomes by launch date the total data was collected and put into one excel sheet.  Then we could use a pivot table to disect the data.  The data was first filtered by the theatre category and then put into collumns decided the outcome of the kickstarter.  The rows represent the month of the year so we could consider what times of  year would be best to kick off the kickstarter.  It was then plotted.  Screen shot below.

![image](https://user-images.githubusercontent.com/92898919/140232889-792ae137-ae5c-44d7-936e-57ccd1acf65b.png)

https://github.com/clare2261/kickstarter-analysis/blob/main/Resources/Theatre_Outcomes_vs_Launch.png?raw=true

### Analysis of Outcomes Based on Goals
The second alaysis done was based on the goal amount in dollars.  So the dollar amounts were binned into 12 bins.  For only considering plays as the subcategory we counted for each success, failed, and canceled projects.  The percentages of each were then calculated off the collected data.  The screen shot below shows the percentages by bin.  

![image](https://user-images.githubusercontent.com/92898919/140232853-b68367a9-ac40-4c6b-926f-c710484a8230.png)
https://github.com/clare2261/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true

### Challenges and Difficulties Encountered
Some challenges were to decide on filtering and which data would be relevent to Louise.  Another challenge was to have the confidence that the countifs were working correctly and there were in fact no canceled plays on the second analysis.  This was confirmed by filter the sheets and double checking.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
There was more success during the middle of the year than at the begining or the end of the year.  This trend corresponded witht he most kickstarters starting off in May.

- What can you conclude about the Outcomes based on Goals?
There were no canceled kickstarters in plays across any goal bin.  The most successful kickstarters were less than 1000$ goals.

- What are some limitations of this dataset?
The limitations of the data were that it only included years 2009 to 2017 and it only included data from kickstater.  There are likely other fundraising oppertunities that are not in the scope of this analysis.

- What are some other possible tables and/or graphs that we could create?
Looking at percent successful across different countries may give Louise some insight into if by switching location she would increase her liklihood of fulfillment.  Or if the trend of success has changed over the timing from 2009 to 2017.
