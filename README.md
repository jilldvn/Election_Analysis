# Election_Analysis
## Overview of Election Audit

The purpose of this analysis is to ensure and the counts of voters are accurate and layout with final result summary using reliable python script without manual counting to reduce potential human errors. 

## Election Audit Results

Based on the audit results run python script:
### Total Votes: 369,711

### County Votes:
#### -Jefferson: 10.5% (38,855)
#### -Denver: 82.8% (306,055)
#### -Arapahoe: 6.7% (24,801)

### Largest County Turnout:
#### -Largest County: Denver
#### -Largest County Voter Count: 306,055

### Candiate Vote Counts:
#### -Charles Casper Stockham: 23.0% (85,213)
#### -Diana DeGette: 73.8% (272,892)
#### -Raymon Anthony Doane: 3.1% (11,606)

### Winning Candidate and Vote Count: 
#### -Winner: Diana DeGette
#### -Winning Vote Count: 272,892
#### -Winning Percentage: 73.8%

## Election Audit Summary
For future use, the same script could be applied to any other election datase by simply replacing the csv file path, either absolute or relative path, as <file_to_load = os.path.join("resources parent folder", "other election file.csv")>.

Meanwhile changing the output location to print in new text file or csv, such as <file_to_save = os.path.join("analysis parent folder", "other election_analysis.txt").>

In addition, it is possible to add a few more expression to analyze other descirptive data as needed, for example, if other descriptive data needed, getting "largest county voters percentage" to add expression of <largest_county_percentage = float(largest_count) / float(total_votes) * 100>

Conclusively speaking, it is a flexible, reliable and sufficent way to run the election result in any occasion without causing tremandous amount of human power wiht error proofing benefit. 
