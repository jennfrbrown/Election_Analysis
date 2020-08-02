# Election_Analysis

## Overview of Election Audit
### Purpose
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calcualte the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7, Visual Studio Code 1.47.3

## Election-Audit Results:
The analysis of the election show that:
- There were 369,711 votes cast in the election.
### Counties
- The counties were:
  - Arapahoe
  - Denver
  - Jefferson
- The county results were:
  - Arapahoe county placed 6.7% of the vote and 24,801 votes.
  - Denver county placed 82.8% of the vote and 306,055 votes.
  - Jefferson county placed 10.5% of the vote and 38,855 votes.
- The county with the largest turnout was:
  - Denver
### Candidates
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
  - Diana DeGette received 73.8% of the vote and 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 votes.
### Summary of Results
<img src = https://github.com/jennfrbrown/Election_Analysis/blob/master/Images%20for%20ReadMe/Election%20Results.png>

 ## Election-Audit Summary:
This script while focusing on specific voter turnout and votes for individual counties can be modified to include additional analysis based on access to additional data.  For example, with additional data, this script could be modified to:
- Include voting method: 
    - There are three main ways of collecting votes - Mail-In Ballots, Punch Cards, or Direct Recording Electric.  By collecting this data and including it in the analysis to understand how many voters utilize each voting type, it would  help allocate staffing resources more effectively.
- Include Political Party:
   - To understand the trends beyond just voting for a specific candidate, if the candidate's political party was included, we could analyze how many voters voted by party lines.  If this data was taken over several years, it would provide historical information and insight into voting trends by party over the years.
- Expand to different election types:
  - If we wanted to increase the election from a state to federal level, you could amend the code to look data from the state level rather than the county level.
  
