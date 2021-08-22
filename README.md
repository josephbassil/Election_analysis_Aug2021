# Election_analysis_Aug2021

#Overview:
We are given election data in a csv file(Resources), showing the ballot's id, name if the candidate and the correspondent county, and we are asked to write code( using Python and VS code) to analyze this csv file and determine:
1. Total number of votes
2. list of candidates
3. how many votes did each candidate get
4. percentage of votes each candidate get
5. winning candidate
6. County votes and percentages
7. winning county (county with most votes)

#Election analysis results:
total votes=369,711
##list of counties: 
Jefferson, Denver, Arapahoe
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)

##list of candidates: 
Charles Casper stockham, Diana DeGette, Raymon Anthony Doane.
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)


#Summary:
According to the numbers extracted from our resources:
we are able to identify the winner in this election and extract the winning votes and percentages
Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%
winning county: Denver

##This script can be used for all future election audits,
Double checking on the file_to_load and file_to_save paths, csv headers is necessary to be able to run this code for other elections.
