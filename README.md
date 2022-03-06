

# Kickstarting with Excel



## Purpose of Analysis

The purpose of Kickstarter analysis is to breakbown large number of data into meaningful charts and pivot tables from which we can easily see the desired information. 

### Background 
  The main sheet contains information about the various file video and television shows. It contained of when it was launched, the countries it was launched in, the goal as well a the outcomes in terms of funds that is how successful it was.

## Analysis based on launch date

In order to perform the analysis, I took help of pivot tables, charts as well as various excel functions. There are couple of analysis which were done. Below is the screenshot attached of the pivot table.

### Theatre outcomes by launch date 
 There were many parent categories however I filtered only to see the theatre outcomes by launch date. With the help of pivot table, we can see how many shows were 
i.	cancelled - 37
ii.	Failed - 493
iii.	Successful - 839



### Result 
 Under the "theatre" category, successful campaigns were highest all over a year with "May" month backing first position. Also in the month of October there were no shows cancelled.
       
      
### Challenges 

i.	Filter years to months - Data was provided with year when it was launched. In order to see the data for every month, year had to be put into 4 Quanters as this concept was new for me so I had to play out a little in order to convert years to months. Below is the screenshot attached for the same.

![Figure 1](https://github.com/aashvie21/kickstarter-analysis/blob/main/Images/del1.png)
 


## Analysis based on Goals

In order to perform the outcome based  on goals I tool the help of countifs funtion which was based on goals that were in the dollar value.

·	Goal outcome by price range - The range is from less than 1000 to 50000 or more. In between this price range analysis was done on the following.
i.	Successful
ii.	Failed
iii.	Cancelled
iv.	Total projects


### Result 
With the help of percentage function, we can see that number of successful shows were within the range of $1000 and less. Also, there were no successful shows with the price range of $45000-$49999. A major revelation is there were no cancelled shows within the provided range.


### 	Challenges 

i.	The  challenge I faced was in Countifs function. Under number of cancelled projects as I was getting 0 and I thought I am doing some mistake in the formula. Below is the screenshot attached.
 
Just to confirm I manually went to see if there was any successful campaigns and seems like there were no successful campaigns in the range "less than 1000".
![Fifure 2](https://github.com/aashvie21/kickstarter-analysis/blob/main/Images/del2.png)












































