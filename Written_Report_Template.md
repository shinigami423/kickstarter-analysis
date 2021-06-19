# Kickstarting with Excel

## Overview of Project

### Purpose
Help Louise determine the how campaigns fared differently by looking at the Kickstarter launch dates and funding goals.
Perform basic Excel functions to clean the data then create pivot tables and charts to visualize campaign outcomes.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
! [date] (Outcomes Based on Launch Date.png)
The pivot table labeled "Theater Outcomes by Launch Date" contains the counts of successful, failed, and canceled Kickstarters accross the months in year range of 2009-2017 under the "theater" category. It is created from the data found on the "Kickstarter" sheet. A line graph is created to show how successful the Kickstarters are when launched at a given time of the year.

### Analysis of Outcomes Based on Goals
! [goals] (Outcomes Based on Launch Date.png)
Contrasting the outcomes based on launch dates, a table is setup to determine if Kickstarters can be more successful based on a range of goals. A line graph is created to show the percentage of sucess/failed/canceled Kickstarters based on the range of goals.

### Challenges and Difficulties Encountered
I faced a small bump when I added the Date Created Conversions to the Axis (Categories), excel automatically added a Years2 and Quarters categories. I shuffled around the orders then found that all I had to do was to remove them completely to have the chart display by months only.

## Results

Basing off the Launch Date alone, I noticed the number of successful Kickstarters are considerably higher in the months of May and June. Lousie should consider starting her theater related Kickstarter between the months of May to June. She should also consider avoiding launch in the month of December as it looks to be a 50% gamble for Kickstarters to be successful.

From the outcomes Based on Goals graph, we recognize that percentages of success are much higher at lower goals. It would be best for Louise to set her funding goal to be less than $5,000 if able as the chances of success is almost 3 times higher. She could also take a chance at goals in between $35,000 and $45,000 if she needs a higher budget. I suggest this range for her to consider as the percetage of failed Kicksters between $5,000 and $35,000 are higher. And definitely avoid going higher than $45,000 as chances and slim to none.

Limitations of this dataset may include incomplete data as there is 1369 total Kickstarters under the theater category. It is difficult to say if there is enough data to accurately protray the outcomes. For example, I filtered the outcomes by launch date by indiviual years and found the increasing number of Kickstarters emerging as the years go by. So this whole data can easily be skewed as we include the following years (2018-2021)

We can create a table to consider outcomes based on Launch Date and Goals. I would create a box and whisker plot to find any outliers. For example, we can find and remove any outliers with certain trends or super high goals and create new tables and charts for more accurate and persuasive suggestions.
Another way to easily view the outcomes based on launch date is to use a stacked column chart. I simply find it more pleasing to look at as you can see how often the percentage of successful overshadows the failed, and vice versa.

