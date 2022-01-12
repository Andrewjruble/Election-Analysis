# Election-Analysis
## Overview of Election Audit 
An employee from the Colorado Board of Elections requested an audit of a recent local election. The tasks for the analysis were: 

- The total number of votes cast
- A complete list of candidates who received votes
- The percentage and total number of votes each candidate won
- The winner of election based on popular votes
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout


Explain the purpose of this election audit analysis.

## Election-Audit Results
 Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

 1. How many votes were cast in this congressional election?
    - **369,111 votes**
 2. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
    - **Jefferson: 10.5% (38,855)**
    - **Denver: 82.8% (306,055)**
    - **Arapahoe: 6.7%% (24,801)**
 3. Which county had the largest number of votes?
    - **Denver**
 4. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    - **Charles Casper Stockham 23.0% (85,213)**
    - **Diana DeGette: 73.8% (272,892)**
    - **Raymon Anthony Doane: 3.1% (11,606)**
 
 5. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
    - Winner: **Diana DeGette**
    - Winning Vote Count: **272,892** 
    - Winning Percentage: **73.8%** 

![Screenshotofresults](https://github.com/Andrewjruble/Election-Analysis/blob/main/Resources/Elections_Results.PNG)

## Election-Audit Summary
In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

This audit for the Colorado Board of Elections can be modified to work on other election results.  Below are two examples:
The orginal results came in a CSV with 3 variables, one column for variable. If future results came with an additional column of data, it could be extracted. For example, nexts years data contains the political party of the candidate in the 4th row. 

Add in about percent of political party per party




Much like the winning candidate along with their vote totals and percentage were found, winning political party, votes and percentage of votes could be determined. Winning candidate, winning count, and winning percentage were all initially defined as variables: 

INSERT IMAGE

Winning party, winning party count and winning party percentage could be added or replaced similarily. 






