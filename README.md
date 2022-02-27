# Election_Analysis

## Project Overview
I have been given the task of completing the election audit of a local congressional election by a Colorado Board of Elections. The three candidates whose votes we tallied were, Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane. We analyzed the data for three counties in the state of Colorado;Arapahoe, Denver and Jefferson.

  *)The total number of votes was 369,711. 
  *)Jefferson had 38,855 voters or 10.5%
  *)Denver had 306,055 voters or 82.8%
  *)Arapahoe had 24,801 voters or 6.7% 
  *)Denver had the largest number of votes
  *)Stockham received 85,213 votes or 23.0%. 
  *)DeGette received 272,892 votes or 73.8% while
  *)Doane received 11,606 votes or 3.1%.
  
 The winner, by a considerable margin, was Diana Degette who receives 272,892 votes or 73.8%

## Resources
For our analysis we used a .csv (comma separated values) file provided by the election board. We also utilized Python 3.6.1 to analyze the code and Visual studio code 1.64.2 as the IDE or Integrated Development Environment. 

## Summary
The Election Analysis shows that there were 369,711 votes cast within the three counties. The candidates were Charles Casper Stockham, Diane DeGette, and Raymond Anthony Doane. 
The results of the election shows that Stockham received 23.0% of the vote and 85,213 votes in total. DeGette receives 73.8% of the votes and 272,892 votes in total; and Doane received 3.1% of the votes and 11,606 votes in total.

The winner of the election was Diana DeGette who received 73.8% of the vote.


## Election-Audit Summary

The code i've built here is simple but effective and easily recycled. When viewing the image below you will notice that our code does not search by Charles Cooper Stockham, Diane DeGette or Raymond Anthony Doane, but rather it searches by county_name and candidate_name. In fact all that would be necessary would be to change the section to load a file from a path and to double check any indexes in the csv file to make sure the order of columns is consistent. This means that this could could be repurposed to calculate say a sherriff election in texas or school board election in california with minimal changes. For example if we needed to repurpose this for a sherriff election all we would need to do is make sure that the csv file columns read in order of left to right: Ballot ID, County, Candidate which would keep the county index at 1 and the candidate index at 2 meaning the section of code below would stay the same; the for/if loop below using all unique county and candidate names to tally and calculate votes. 

![alt text](https://github.com/quorinne/Election-Analysis/blob/master/Resources/Screenshot%20(19).png?raw=true)




![alt text](https://github.com/quorinne/Election-Analysis/blob/master/Resources/Screenshot%20(13).png?raw=true)

## Challenge Overview

## Challenge Summary
