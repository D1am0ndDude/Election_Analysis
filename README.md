# Election_Analysis
# Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election. Our job is to generate a vote count report to certify this U.S. congressional race.

## Resources
* Data Source:election_results.csv
* Software:Python 3.7.8, Visual Studio Code, 1.38.1
* 
## Election-Audit Results:
The Analysis of the election show that:
* There were 369,711 votes cast in the election.
* County Votes:![County_Votes](https://user-images.githubusercontent.com/46943357/189550825-a5bb32dd-2f8a-4808-be0e-e6a23a54e611.PNG)
  * Jefferson: 10.5% (38,855)
  * Denver: 82.8% (306,055)
  * Arapahoe: 6.7% (24,801)
  
* The Largest County Votes:
  * Largest County Turnout: Denver: 82.8% (306,055) 
  
* The candidates were:
  * Charles Casper Stockham
  * Diana DeGette
  * Raymon Anthony
* The candidate results were
  * Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  * Diana DeGette received 73.8% of the vote and 72,892 number of votes.
  * Raymon Anthony received 3.1% of the vote and 11,606 number of votes.
* The winner of the election was:
  * Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Election-Audit Summary:
What this script can do for you? Simple! Counting each vote by hand is slow, and can be inaccurate if miss counted. That can completely throw things off. With this script, and it's pin-point accuracy, every vote from each county will be summed up. Afterwards, the script takes the total votes, then caculates the percentage of the highest county voted, then makes it visually clear who won. 

How can you apply this script to any Election? First, you're going to have to change the file names and locations. When you have a spreadsheet with all the votes on it, edit the file, and folder name to what is appropriate. Second, if the Candidate and County names are in different rows, that too will need to be adjusted. ![EditNames](https://user-images.githubusercontent.com/46943357/189550778-9de99821-4e42-49f6-93c0-15a848b2b95b.PNG)
