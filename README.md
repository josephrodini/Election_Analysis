# Election_Analysis

## Project Overview
A Colorado Board of Elections employee, Tom, needed help completing an election audit of a recent local congressional election. The tasks to be completed included:

1. Calculating the total number of votes cast.
2. Getting a complete list of candidates who received votes.
3. Calculating the total number of votes each candidate received.
4. Calculating the percentage of votes each candidate won.
5. Determining the winner of the election based on popular vote.
6. Getting the percentage of votes cast in each county.
7. Determining the county with the most votes cast.

## Resources
Resources for this project included:
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.38.1

## Summary
The analysis of the election, [as seen in the election analysis text file we generated](https://github.com/josephrodini/Election_Analysis/blob/main/Resources/election_analysis.png), show that:
1. There were 369,711 votes cast.
2. The candidates receiving votes were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
3. and 4. The voting results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
  - Diana DeGette received 73.8% of the vote and 272,892 votes.
  - Raymon Anthony Doane  received 3.1% of the vote and 11,606 votes.
5. The winner of the election was Diana DeGette, who received 73.8% of the vote and 272,892 votes.
6. The three counties voting in the election include:
  - Jefferson County, which cast 38,855 votes, or 10.5%.
  - Denver County, which cast 306,055 votes, or 82.8%.
  - Arapahoe County, which cast 24,801 votes, or 6.7%.
7. The county casting the most votes was Denver County.

## Challenge Overview
The election data was tabulated into a comma-separated values file which proved to be easy to analyze as it was well-formatted and had no missing or error-riddled data, such as mispelled county or candidate names. 

## Challenge Summary
Tom can rest easy knowing that, thanks to Python and Visual Studio Code, we know who won the election and by what margin.

In addition, it is recommended that Tom use this script to audit more elections. So long as the election data is compiled into a .csv file, this script can be repurposed. For example, the script can analyze any additional columns of data so long as the row[] line of code is changed to match the column to be analyzed. This means we could analyze ballots with any number of races on them. This script could also be repurposed to handle proposition votes. Instead of tabulating candidate names in a candidate name list, we'd create a list (say, prop_options) that would have the options "approve" and "reject," as well as a proposition dictionary (like prop_votes) to hold the vote totals. This way we could cover both types of measures ballots usually contain.
