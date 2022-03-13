# Election_Analysis
## Overview of Election Audit
I recently helped Seth and Tom submit election audit results to the election commission and they asked for more information to better analyze the voting data. They asked for the following additional data:
 - Voter turnout for each county
 - Percentage of votes from each county out of the total count
 - County with the highest turnout

I was able to collect and analyze the data using the following resources.

### Resources
Data source: [election_results.csv](https://raw.githubusercontent.com/AndyPicton/Election_Analysis/main/Resources/election_results.csv)

Software: Python 3.10.2 and Visual Studio Code 1.65.0

## Election Audit Results
### Counties
Jefferson, Denver, and Arapahoe

### Candidates
Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane

### Results
- Total votes: 369,711
- Jefferson County received 38,855 votes which is 10.5% of the total votes cast
- Denver County received 306,055 votes which is 82.8% of the total votes cast
- Arapahoe County received 24,801 votes which is 6.7% of the total votes cast

**The largest County turnout was Denver**

- Charles Casper Stockham received 85,213 votes which is 23.0% of the total votes cast
- Diana DeGette received 272,892 votes which is 73.8% of the total votes cast
- Raymon Anthony Doane received 11,606 votes which is 3.1% oif the total votes cast

**The winner of the election is Diana DeGette**
- Winning Vote Count: 272,892
- Winning Percentage: 73.8%

![image](https://user-images.githubusercontent.com/99369565/158076858-b34da261-8739-4e0b-b857-f253993b8dc3.png)


## Election Audit Summary
As seen in the [PyPoll_Challenge.py](https://github.com/AndyPicton/Election_Analysis/blob/58dbf4c8c538d5688c36ecd6f7dc4a56b2408db3/PyPoll_Challenge.py), this script can be run very quickly to analyze many lines of data. The code used can be modified anyway needed to analyze your data, it does not have to be rewritten. The data can be anything really and in an order, to make it as easy as possible for the code it would be best to leave it in the same format but that is still not required. 

### To modify the script:
1. The first change to the script would be to change the file_to_load path so that the new data can be read.
![image](https://user-images.githubusercontent.com/99369565/158078677-83fd8718-6c0a-4e26-ab52-3e905286e49a.png)
 - All you need to do is change 
  - ("Resources", "election_results.csv")
  - ("analysis", "election_analysis.txt")
 - To:
  - ("New folder name", "new_election_results.csv")
  - ("New analysis", "New_election_analysis.txt")

2. The second change that would be useful is to change the list and dictionary names to be consistant with the data.
![image](https://user-images.githubusercontent.com/99369565/158078808-3c998ea2-ed8a-42cb-bac8-c4c952bf9eba.png)
 - Change county_list[] to what you feel matches the data best

