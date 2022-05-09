# Election Analysis 
(repository for Module3 - Python)

## 1.  Overview of Election Audit

Tom, a Colorado Board of elections employee, has requested an audit of the tabulated election results for the U.S. Congressional Precinct in Colorado.  The task requested requires the total number of votes and their percentages for each candidate and the winning candidate.  Additionally, a summary based on counties within the precinct was requested and a breakdown of votes per county for identification of the largest county turnout was incorporated into the tool.  It had also been requested that the task be coded in Python in order to develop a tool that can be applied to other elections such as; other congressional districts, Senatorial districts, and local elections.  

In order to develop this tool the election results data was provided in a Comma Separated Values (CSV) file called election_results.csv and is located in the Resource folder .  This data included all votes cast in the election; Mail-In_Ballot, Punch Cards, and Direct Recording Electronic (DRE counting machines) voting methods.  It contains 3 columns of information Ballot ID, County, and Candidate. 
	
	
[election_results.csv]https://github.com/AnaMMoreira/Election_Analysis/blob/main/Resources/election_results.csv
	
Seth, Tom's manager, would like him to become familiar with writing an running Python script using a command line, in order to make updates to GitHub repository. Using and understanding the Python script will allow Tom to perform future updates and election audits and analysis.  The Python code is found in the PyPoll_Challenge.py file and comments describing each data manipulation is carefully included so Tom or anyone looking at the code can easily follow and perhaps modify as needed.

[PyPoll_Challenge.py]https://github.com/AnaMMoreira/Election_Analysis/blob/main/PyPoll_Challenge.py

## 2.  Election-Audit Results

For this project, the command line was used to upload and access files to update GitHub repositories, and starting the Python interpreter to write and run Python scripts. Git Bash is a Microsoft Windows environment application that installs Bash and Git on a Windows operating system and was the terminal used.  After installing and setting up all the necessary tools the developed code was successfully run and yielded the following election results.  The code outputs the results to the command line as seen in the following screen capture.

![terminal output image]https://github.com/AnaMMoreira/Election_Analysis/blob/main/analysis/command_line_window.png

The results were also saved to a text file externally and can be seen within the Analysis folder

[Election Analysis Results]https://github.com/AnaMMoreira/Election_Analysis/blob/main/analysis/election_analysis.txt

* How many votes were cast in this congressional election?

	In the summary it can be observed that a total count of the votes yielded a Total Votes of 369,711.

* The breakdown of the number of votes and the percentage of total votes for each county in the precinct was as follows; 
 
 	Jefferson: 10.5% (38,855)\
  	Denver: 82.8% (306,055)\
  	Arapahoe: 6.7% (24,801)
 
* The largest county turnout was from Denver's contribution of 306,055 votes representing 82.8 % of the total votes.

* Each candidate vote breakdown can be summarized as follows

	Charles Casper Stockham: 23.0% (85,213)\
	Diana DeGette: 73.8% (272,892)\
	Raymon Anthony Doane: 3.1% (11,606)

* The winner of the election was Diana DeGette with 272,892 votes representing 73.8 % of the total votes.

## 3. Election Audit Results

 In summary the Python code developed for this project is able to audit, and analyze election data.  It is able to extract total vote count and subdivide and group votes by both counties and candidates in order to be able to reliably count and determine who won the elections, what the percentage of votes each candidate acquired, and which counties contributed the most by votes to the election.  A proposal to the election commission thus can be made to modify this script so it can be used for any election.

This code could be applied to other precincts as is, it will read in each county because it generates a list of counties and candidates and is able to accurately calculate the total votes and therefore each individual contributions.  

Improvements for other applications could include for example, for local elections within each county the code could be simplified to only give the summary for each candidate by simply commenting out the sections which extract, count and calculate votes based on the different counties.

Another example could be to further expand the code to subdivide the county votes grouped by candidates so that each candidate can see where they got the most votes.  This could be particularly useful for the Congressional and Senatorial elections which are conducted on the State level and are based on population totals.

