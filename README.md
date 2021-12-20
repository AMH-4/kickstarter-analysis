
![Parent Category Outcomes](https://user-images.githubusercontent.com/90002900/132962981-d66737af-cbe9-49d7-a6d9-0dda123f2730.png)



# **kickstarter-analysis**
*Performing analysis on Kickstarter data to uncover trends*


## Overview of Project:

#### *Purpose:*
The purpose of this challenge is to build upon the Excel skills learned throughout Module 1. Throughout Module 1 the goal was to help Louise plan her own successful campaign for her play *Fever*. For Louise, this challenge’s purpose was to understanding how different campaigns faired in relation to their launch dates and their fundraising goal while analyzing a dataset to discover hidden trends.

###Project Background
Louise, a playwright, was seeking to launch a crowdfunding campaign to for the launch of her play *Fever*. The campaign began  with estimated budget of over $10,000. Nervous about launching a crowdfunding campaign, Louise decided to enlist help.

In an effort to determine if there are specific factors that make a campaign successful, I organized, sorted ,and analyzed crowdfunding data. Throughout Module 1 the goal was to help Louise plan her own successful campaign. 

Louise took the analysis I performed throughout Module 1 and was able to execute here own successful crowdfunding campaign for her play *Fever*.

Louise’s play *Fever* came close to its fundraising goal in short amount of time. 
Upon completing her first crowdfunding campaign, Louise wanted to know how different campaigns faired in relation to their launch dates and their fundraising goal.
 

## Analysis and Challenges

#### *Analysis Overview:*
With the purpose of this analysis defined, two deliverables became necessary to perform. 
	* Visualize campaign outcomes based on launch date
	* Visualize the percentage of successful, failed, and canceled plays based on funding goals amount.
The following steps were taken to perform the above necessary deliverables:



#### *Challenges and Difficulties Encountered:*
Module 1, Kickstarting with Excel, began my data analytics journey. Although I had good Excel skills before this module, I encountered new obstacles and some familiar difficulties. This was the largest data set I have worked with in recent weeks, so navigating through the data was not always seamless. On two specific occasions, my formal was not correct. Although not difficult in nature, it was frustrating as the code began to blur together making it difficult for me to debug my formula. The first formula debugging was while creating the “Years” data in column U. This data was pulling data from column S “Date Created Conversion”. I failed to add the second “/60”. After re-reading the formula multiple times I finally was able to debug and enter the correct formula: “ =(((J2/60/60)/24)+DATE(1970,1,1)) “ inside the column S “Date Created Conversion”. Once this formula was correct column S and U worked properly. The second formula debugging occurred while working with the ‘Outcomes Based on Goals tab’. The COUNTIFS function used to create column B-D was simply to understand, however arranging the criteria and range correctly proved challenging. The challenges I encountered within this module revolved around navigating through a large data set and pinpointing formula failure through debugging. Altogether these challenges were likely relatively simple compared to the challenges to come.


## Results:

![Parent Category Outcomes](https://user-images.githubusercontent.com/90002900/132962981-d66737af-cbe9-49d7-a6d9-0dda123f2730.png)

Analysis and Challenges: Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered.
Results: Answer the following questions in complete and coherent sentences.
What are two conclusions you can draw about the Theater Outcomes by Launch Date?
What can you conclude about the Outcomes based on Goals?
What are some limitations of this dataset?
What are some other possible tables and/or graphs that we could create?
