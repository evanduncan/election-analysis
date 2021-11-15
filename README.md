# election-analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary
The analysis of the election shows that:
- There were 369,711 votes cast in the election
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Stockham received 23% of the vote and 85,213 votes.
  - DeGette received 73.8% of the vote and 272,892 votes.
  - Doane received 3.1% of the vote and 11,606 votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 votes
- The counties that voted in this election and their corresponding vote totals were:
  - Denver County with 306,055 votes or 82.8%
  - Jefferson County with 38,855 votes or 10.5%
  - Arapahoe County with 24,801 votes or 6.7%


This script could be used on a number of elections to determine the outcome, given only a few simple changes depending on the data provided. It is a simple, generalized script that looks at raw voting data and determines the candidate names, the  total number of votes cast, each candidate's vote total and percentage of votes cast, the counties polled, and the count and proportion of the vote represented by each county. The main alteration to the code that would need to be made is to reassign the indices that determine the county and candidate names according to the relevant data sheet. Another change that would need to be made is to alter the file paths in the code according to the machine you are working on.
