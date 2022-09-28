# Election_Analysis

## Project Overview
The purpose of this project was to take our initial project that we created to find the winner of the US Congressional Precint Election and expand upon it. The project focused on finding the voter turnout in each county, the percentage of votes in each county, compared to the total votes in the election, and finding which county had the largest voter turnout.

## Summary
# The analysis of the election shows that:
There were 369,7111 votes cast in this Congressional precint election

<img width="95" alt="image" src="https://user-images.githubusercontent.com/110848660/192868681-456d89b2-1894-4137-9dc6-95655e39fd65.png">

### The counties involved in this election were:
  - Jefferson County
  - Denver County
  - Arapahoe County
  
### The county results were:
  - Jefferson County placed 10.5% of the votes with a total of 38,855 votes
  - Denver County placed 82.8% of the votes with a total of 272,892 votes
  - Arapahoe County placed 6.7% of the votes with a total of 24,801 votes

<img width="101" alt="image" src="https://user-images.githubusercontent.com/110848660/192869023-8394c662-9e5c-4343-9909-67a73ccb1c68.png">

  
### The county with the largest turnout was:
  - Denver county with 82.8% of the votes with a total of 272,892 votes

<img width="110" alt="image" src="https://user-images.githubusercontent.com/110848660/192869182-ea8a3aaf-8dfa-4664-8791-c0686c2618d4.png">

### The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
 
### The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes
  - Diana DeGette received 73.8% of the vote and 272,892 votes
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes

<img width="138" alt="image" src="https://user-images.githubusercontent.com/110848660/192869296-5f5f7050-8f21-40e7-b6c5-05dedf52982a.png">


### The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 votes

<img width="110" alt="image" src="https://user-images.githubusercontent.com/110848660/192869610-36edcb7a-ed78-49e1-aed8-47137d0824a0.png">

## Election Audit Summary:
One of the benefits of this project is that we can use the same code and slightly modify it to be able to use it in other elections. One way to do this is by modifying the input file for the election results with the code below. We can either overwrite the existing file to pull in a different data set or use a different file altogether and change the path to bring in a new .csv file

<img width="256" alt="image" src="https://user-images.githubusercontent.com/110848660/192864191-b92cf623-482e-4eda-9d8d-7c78bf3f5f79.png">

We could also modify the code to give us the voter breakdown in each of the counties that were involved in the election. We looked at the candidate breakdown of all the counties combined, but we can modify the code to get even more information. We can add in additional code to show us how each of the three candidates did in each county separately. That would be beneficial information to see trends in different areas and could even be passed along to campaign managers to see what areas they may want to campaign harder in for a future election. We would do this by running a loop through each county in our .csv file, collecting the vote count for each candidate in that county, and then displaying the election results for that particular county. Then we would need to set up the loop to move to the next county in the .csv file and continue that process until it has looped through all the counties and captured all the results.
