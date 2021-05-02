# Election_Analysis

## Overview of Election Audit

A Colorado Board of Elections employee requested an election audit of a recent local congressional election.  A .csv file was provided of each vote cast, the candidate selected, and the county where the vote was cast.  The data file was analyzed leveraging Python 3.9 and Visual Studio Code script editor with the objective that the code could be reused for other elections.

The audit includes:

  1. The total number of votes cast.
  2. The total number of votes cast in each county.
  3. A list of candidates who received votes.
  4. The total number and percentage of votes each candidate won.
  5. The winner of the election based on popular vote.

## Election Audit Results

The election audit analysis shows:

- There were 369,711 votes cast in the election.

- The breakdown of votes cast by county:
    - Jefferson County accounted for 10.5% of votes with 38,855 votes cast
    - Denver County accounted for 82.8% of the votes with 306,055 votes cast
    - Arapahoe County accounted for 6.7% of the votes with 24,801 votes cast

- The county with the most votes was Denver County
    
- The candidate results were:
    - Charles Casper Stockham received 23% of the vote with 85,213 votes
    - Diana DeGette received 73.8% of the vote with 272,892 votes
    - Raymon Anthony Doane received 3.1% of the vote with 11,606 votes
   
- The winner of the election was:
    - Diana DeGette who received 73.8% of the vote with 272,892 votes

These results are summarized in a readable text file (shown below) with the election audit script.

![image_name](https://github.com/Christopheremorgan/Election_Analysis/blob/main/election_results_screenshot.png)

## Election Audit Summary
This script can easily be leveraged for future elections and to provide audit results for other types of elections with minimal modifications. For example, counties could be adjusted for other region types including cities, districts, precincts or states.  

The existing script will adjust to any number of candidates without any code changes.  The winner logic can be adjusted to account for winning percentages for primary elections with winning percentage thresholds and run-off rules.  The winning percentage can be initialized at the threshold % and the winner candidate variable could be initialized to "No winner. Run off required" in the event the primary threshold condition is not met.
