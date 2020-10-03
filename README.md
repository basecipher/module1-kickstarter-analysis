# Kickstarting with Excel

## Overview of Project

Using Excel to filter statistical data and uncover trends to assist client with meeting their objective

### Purpose
To help client determine proper budget goal for her campaign.

## Analysis and Challenges
* Raw Kickstarter data was imported into an Excel spreadsheet.
* Broad Categories were broken down into small subcategories to help us focus on the clients need, which in this case was musical plays in Great Britain.
* Charts were made to visualize the parent category outcomes then broken down to subcategories.
* Data was streamlined using VLOOKUP to create a table showing goal and pledged amounts in relation to their respective average donation and backers.  This can be observed under "Edinburgh Research" tab.
* The below table was used to create a series of useful pivot tables (i.e "Subcategory Statistics" tab).

![iIQR Goal](https://github.com/basecipher/module1-kickstarter-analysis/blob/master/IQR%20Goal.png)

* Statistics formulas were used to determine the interquartile range of the Kickstarter's both goal and pledge data.  A box plot graph was designed with these results as shown below.

![Box Plots](https://github.com/basecipher/module1-kickstarter-analysis/blob/master/Box%20Plots%20-%20git.png)

### Analysis of Outcomes Based on Launch Date
Most successful outcomes are in March while most failed are in October.  Top 3 consecutive months to launch align with summertime (May-July).

![Theater Outcomes vs Launch](https://github.com/basecipher/module1-kickstarter-analysis/blob/master/resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals
Goals with price range between $3500 and $3999 showed the least probability of failure in relation to highest probability of success.

![Outcomes vs Goals](https://github.com/basecipher/module1-kickstarter-analysis/blob/master/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
It was challenging to master VLOOKUP function and understanding the differences between standard deviation and the interquartile range (IRQ).  After understanding them I realized how much they have in common.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Kickstarters have a greater chance of success during the summer and greatest chance of failure in fall and winter.

- What can you conclude about the Outcomes based on Goals?
Setting budget goal between $3,500 and $4,000 renders the highest probability of success.

- What are some limitations of this dataset?
* Dataset came from only one single source.
* We didn't see comparison of size of production and how that affected its success and failure in this dataset.

- What are some other possible tables and/or graphs that we could create?
* A graph could be made showing relationship of goal with the number of backers.
* We could also formulate a table with successful production in relation to whether they were staff picked or not (column M in main Kickstarter worksheet).
