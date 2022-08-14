# Election Analysis

## Project Overview
The Colorado Board of Elections requested for a complete election audit of their local congressional election. With the raw data from the election, my team and I were able to use unique ballot IDs, names of candidates, and the counties these votes were cast in to provide a results summary of the outcome of the election with over 300,000+ data points.

## Tasks
1. Calculate the total number of votes.
2. Compile the list of counties where citzens voted.
3. Compile the list of candidates who recieved votes.
4. Calculate the total number and percentage of votes per county.
5. Determine the county with largest turnout.
6. Calculate the total number and percentage of vote per candidate.
7. Determine the winner of the election based on the popular vote.

## Resources
Data: election_results.csv
Software: Python 3.8.1, Visual Studio Code 1.45.1

## Results
1.Total Votes:
- 369,711
  
2.County Names:
- Jefferson
- Denver
- Arapahoe
  
3. Candidates Names:
- Charles Casper Stockham
- Diana DeGette
- Raymon Anthony Doane

4.Number and percentage of votes per county:
- Jefferson, 38,855 votes, 10.5% of total votes
- Denver, 306,055 votes, 82.8% of total votes
- Arapahoe, 24,801 votes, 6.7% of total votes

5.Largest County Turnout:
- Denver

6.Number and percentage of votes per candidate:
- Charles Casper Stockham, 85,213 votes, 23.0% of total votes
- Diana DeGette, 272,892 votes, 73.8% of total votes
- Raymon Anthony Doane, 11,606 votes, 3.1% of votes

7. Winner of congressional election:
- Diana DeGette

![Election Results](https://user-images.githubusercontent.com/102635884/184518583-dff0e6f0-5e66-441a-b150-e4a67998263d.PNG)


## Summary
This analysis can act as a guide for any election that the election commission holds in the future. As long as the data is within a CSV file and a similar dataset. Another modification to allow for ranking for election truneouts would be to create a new decison statement and a new lopp to caulate the totals, percentages and how it would rank for the highest values. This would allow for quicker understanding with such large datasets. For modicifcations on a larger scale outside of the county, the script can be edited to change the counties to states.
