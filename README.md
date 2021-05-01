# Election_Analysis

## Overview of Election Audit

A Colorado Board of Elections employee requested an election audit of a recent local congressional election.  A .csv file was provided with votes cast for each candidate and included which county the vote came from.  The data file was analyzed leveraging Python in the Visual Studio Code script editor.

The audit includes:

  1. The total number of votes cast.
  2. The total number of votes cast in each county.
  3. A list of candidates who received votes.
  4. The total number and percentage of votes each candidate won.
  5. The winner of the election based on popular vote.

## Election Audit Results

The analysis of the election show that:

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

These results are summarized in a text file (shown below) created as a readable output of the election audit script.
[insert png link of the script here]

## Election Audit Summary
This script can easily be leveraged for future elections and to provide audit results for other types of elections with minimal modifications. For example, counties could be adjusted for other region types including cities, districts, and states.  

The existing script will adjust to any number of candidates and the winner logic can be adjusted to also account for winning percentages for primary elections with thresholds and run-off rules.  The winning percentage can be initialized at the primary threshold %.
