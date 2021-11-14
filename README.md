# Election_Analysis

## Overview of Election Audit

### Purpose

The purpose of this election audit on top of providing the election commission of the candidates election results, we will also provide the voter turnout for each county, percentage of votes from each county out of the total count, and county with the highest turnout.

## Election-Audit Results

- How many votes were cast in this congressional election?

 ![total_votes](https://user-images.githubusercontent.com/92401000/141698875-790aa80d-eda1-4605-878d-536b985c1933.PNG)

 The total number of votes casted in this congressional election was 369,711.
 
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

![county_votes](https://user-images.githubusercontent.com/92401000/141699077-aa584adf-321b-49f9-a7f9-c6be1c96ea45.PNG)

The total number of votes for Jefferson county was 38,855 which was 10.5% of total votes. The total number of votes for Denver county was 306,055 which was 82.8% of total votes. The total number of votes for Arapahoe county was 24,801 which was 6.7% of total votes. 
 
- Which county had the largest number of votes?

![largest_county](https://user-images.githubusercontent.com/92401000/141699102-f1056003-4277-41e5-bdb0-552eb539e347.PNG)

Denver county had the largest numbers of votes: 306,055 representing 82.8% of all total votes.
 
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

![candidate_votes](https://user-images.githubusercontent.com/92401000/141699126-5ef512e5-c1fd-4e30-9a85-cbff2142a65b.PNG)

Charles Casper Stockham received 85,213 votes representing 23.0% of all total votes. Diana DeGette received 272,892 votes representing 73.8% of all total votes. And Raymon Anthony Doane received 11,606 votes representing 3.1% of all total votes.
 
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

![winning_candidate](https://user-images.githubusercontent.com/92401000/141699151-7ac9ddc8-b511-4d71-968b-f8b9b21a19a9.PNG)

Diana DeGette won the election with 272,892 votes, representing 73.8% of the total votes.

## Election-Audit Summary

This PyPoll_Challenge script can be used for any election to determine the candidate and county results with small modifications. 
  1. If you want to use this script for another election, use a csv file and rename it to "election_results.csv" and place it in the "Resources" folder and remove the other csv file. Then ensure the format has three columns with data of "Ballot ID, County, Candidate" respectively in column A, B, C in csv file. This ensures no code changes will be needed to the script. 
  
  2. The other option is if you place the election data in "Resources" folder, you will need to replace the "election_results.csv" string in "file_to_load = os.path.join" line with the name of that file. Then the index number for the candidate name and county name inside the "for row in reader:" code will need to change to match the location of those two data inside the csv file. 
