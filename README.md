#Module-3-Challenge

## Overview of Election Audit  
The purpose of this audit was to determine the number of votes and percentage of the total number of votes in each of the 3 counties and for the 3 candidates of a congressional election in Colordo. 

## Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

  - **How many votes were cast in this congressional election?**
    There was a total of 369,711 votes cast in this congressional election
  - **Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.**
 
 | County    | Total Number of Votes | Percentage of Total Vote |
 |-----------|-----------------------|--------------------------|
 | Denver    | 306,055               | 82.8%                    |
 | Jefferson | 38,855                | 10.5%                    |
 | Arapahoe  | 24,801                | 6.7%                     |
          
  - **Which county had the largest number of votes?**
    Denver county had the largest turn out with 306,055 votes.
    
  - **Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.**

| Candidate               | Total Number of Votes | Percentage of Total Vote |
|-------------------------|-----------------------|--------------------------|
| Diana DeGette           | 272,892               | 73.8%                    |
| Charles Casper Stockham | 85,213                | 23.0%                    |
| Raymon Anthony Doane    | 11,606                | 3.1%                     |

  - **Which candidate won the election, what was their vote count, and what was their percentage of the total votes?**
    Diana DeGette won the election with 272,892 votes (73.8% of the total vote).
 
  
## Election-Audit Summary: 
In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

This script can be used to load in any election csv, assuming it is in the exact same format at the original election_results.csv (ie 3 columns of data: ballot ID, county, candidate). This script could be applied to a state-wide election dataset that includes more counties and candidates. Given input data about zipcode or city the script could be modified for analysis of the voting trends in a city or zipcode. The script could also be modified to show a graphical representation of the election outcomes via pie or bar graphs. 
