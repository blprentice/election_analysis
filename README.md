# Election_Analysis

## Project Overview

A Colorado Board of Elections employee has tasked me with completing an audit of a recent congressional election. The original scope is as follows:

#1. Calculate the total number of votes cast.
#2. Get a complete list of candidates who received votes.
#3. Calcualte the total number of votes each candidate received.
#4. Calcuate the percentage of votes each candidate won.
#5. Determine the winner of the election based on popular vote.

Additionally, the Board of Elections requested the following after my initial submission:

#6. Voter turnout for each county.
#7. Percentage of votes from each county out of the total count.
#8. County with the highest turnout.

## Resources

Data Source: election_results.csv
Software: Python 3.7.3, Visual Studio Code 1.73.1

## Election Audit Results

• Total votes cast: 369,711
• Vote breakdown by county
    ○ Jefferson County: 38,855 (10.5%)
    ○ Denver County: 306,055 (82.8%)
    ○ Arapahoe County: 24,801 (6.7%)
• The county with the largest number of votes was Denver County.
• Vote breakdown by candidate:
    ○ DeGette, Diana: 272,892 (73.8%)
    ○ Doane, Raymon Anthony: 11,606 (3.1%)
    ○ Stockham, Charles Casper: 85,213 (23.0%)
• The winner of the election was Diana DeGette with 272,892 votes (73.8% of total)

## Election Audit Summary

A major benefit of automating this election audit process is that the Python script can be used, with some adjustments, for any election in the state.
    #1. This script could provide the same information for different geographical entities, e.g. municipalities or voter precincts.
    #2. The script could be modified to provide the voter turnout as a percentage of registered voters in the county/municipality/precint if that data were available.
