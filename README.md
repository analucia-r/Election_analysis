# Election_analysis
Module 3
## Overview of Election Audit: 
In this audit we were able to work with the total number of votes casted from three different counties. With a complete list of candidates we analyzed the total number of votes each candidate recieved and the percentage for each candidate. Also, We determined the winner of the election based on popular vote. Finally, using python we progrmmatically counted up the total votes casted in this election. 
## Election-Audit Results: 
![election_results txt](https://user-images.githubusercontent.com/92067596/156948737-d92294df-b4f7-4936-a575-1d9c44a23ae0.png)
- Total votes casted in congressional election: 369,711
- Jefferson recieved 10.5% out of the total votes 
- Denver recieved 82.8% of the total votes 
- Araphone recieved 6.7% out of the total votes
- Denver had the largest turn out in number of votes with a 306,055 count
- Candidate Charles Casper Stockhamd recieved 23.0% out of the total votes 
- Candidate Diana DeGette recieved 73.8% of the total votes 
- Candidate Raymon Anthony Doane recieved 3.1% of the total votes
- Diana DeGette with 73.8% out of the total of votes won the election with 272,892 number of votes
## Election-Audit Summary: 
The script used was to retrieve the largest number of votes per county. Which was useful and we were able to retrieve also, how much votes per candidate.
For future use the script can be modified for not just county elections but for state or national elections too. Of course at a much larger scale there would have to be more to account such as who is voting for example age range. And we can see who is popular among the youth or elderly. 

## We can also incorporate which party each candidate belongs to and that would be adding and extra column in the excel data sheet and adding a line of code (dictionary). 
- party_name_list = []
- party_name options = {}
- party_name = row[3]
- party_name_list.append(party_name)
- party_count[party_name]
