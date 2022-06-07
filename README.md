# Kickstarter Campaign Analysis
This project is part of coursework for the [University of Texas: Data Science and Vizualization Bootcamp](https://techbootcamps.utexas.edu/data/) 

#### -- Project Status: [ Completed]

## Project Overview
The purpose of this project: the anlaysis of Kickstarter campaign success rates for plays, based on goals. In my analysis I hope to:

* Predict how to launch a successful Kickstarter campaign for a play

* Highlight meaningful trends using data

* Describe analysis methods used and challenges encountered with the data set.



### Methods Used

* Data Visualization
* Statistical analysis


### Technologies
* Excel 
 

## Project Analysis and Challenges

* Data: the dataset provided was an xlxs file of 4115 Kickstarter campaigns of varying types and goal amounts, respectively.

* Analysis: 
** Successful Kickstarter campaigns for plays have a mean goal of $5,049 and a median goal of
$3,000
** Successful Kickstarter campaigns for play funding have a mean Pleadge of $5,602 and a median pleadge of $3,3168
** There were 1267 total projects for plays in the sample data.
** Of the 1267 campaigns, 386 had a goal ranging from $1,000 - $4,999, with a success rate of 88.34%.
** An examination of goals vs outcomes indicate that campaigns for play fundraising within the $1k-5k range have a 88.34% liklihood of success.

![Outcomes vs Goals](https://github.com/DevTrav/kickstarter-research/blob/main/resources/Outcomes_vs_Goals.png)

* Challenges:
** Excel has limitations and will throw Errors when dividing by 0. This issue can be resolved by using another technology to examine the data or VBA to programatically remove the Error and provide a value (i.e. 0 or N/A ).

