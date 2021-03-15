# Cisc3140
The file Lab1 is a word document file on the experience of the group discussion and what my group discussed in the break out rooms on Zoom. We discussed a game called Mareeo Shooting with Them.
The file Lab3 is about writing what skills we are qualified for and no qualified for and how do we go about learning them.


Lab 5: For lab 5, I choses to do task 1. I used the csv file: hurricanes.csv for task 1. This file contains data of the hurricanes that have occurred from 2005 to 2015. It includes the average number of hurricanes, how many hurricanes happened per month of each year. The question I asked was: What were the hurricane statistics for the month of May? For the command line solution, I outputted my commands and the results to another file called: Session.log. To display the contents of the csv file, I used the ‘cat’ command. It displayed it, but not exactly as what the csv file showed when you download it to the computer. To find the statistics for May, I used the grep command to display the row that contained “May”. The log is shown below, but I will be uploading the Session.log file below this file in my github repository. 

Terminal log: 
Script started on Mon Mar 15 13:39:23 2021
[1m[7m%[27m[1m[0m                                                                               
 
]7;file://Hashims-MBP.home/Users/hashimn4

[0m[27m[24m[Jhashimn4@Hashims-MBP ~ % [K[?2004hccd desktop[?2004l

[1m[7m%[27m[1m[0m                                                                               
 
]7;file://Hashims-MBP.home/Users/hashimn4/desktop

[0m[27m[24m[Jhashimn4@Hashims-MBP desktop % [K[?2004hccat  c  ccd dow   c  ccd[?2004l

[1m[7m%[27m[1m[0m                                                                               
 
]7;file://Hashims-MBP.home/Users/hashimn4

[0m[27m[24m[Jhashimn4@Hashims-MBP ~ % [K[?2004hccd downloads[?2004l

[1m[7m%[27m[1m[0m                                                                               
 
]7;file://Hashims-MBP.home/Users/hashimn4/downloads

[0m[27m[24m[Jhashimn4@Hashims-MBP downloads % [K[?2004hccat hurricanes.csv[?2004l

"Month", "Average", "2005", "2006", "2007", "2008", "2009", "2010", "2011", "2012", "2013", "2014", "2015"
"May",  0.1,  0,  0, 1, 1, 0, 0, 0, 2, 0,  0,  0  
"Jun",  0.5,  2,  1, 1, 0, 0, 1, 1, 2, 2,  0,  1
"Jul",  0.7,  5,  1, 1, 2, 0, 1, 3, 0, 2,  2,  1
"Aug",  2.3,  6,  3, 2, 4, 4, 4, 7, 8, 2,  2,  3
"Sep",  3.5,  6,  4, 7, 4, 2, 8, 5, 2, 5,  2,  5
"Oct",  2.0,  8,  0, 1, 3, 2, 5, 1, 5, 2,  3,  0
"Nov",  0.5,  3,  0, 0, 1, 1, 0, 1, 0, 1,  0,  1
"Dec",  0.0,  1,  0, 1, 0, 0, 0, 0, 0, 0,  0,  1

[1m[7m%[27m[1m[0m                                                                               
 
]7;file://Hashims-MBP.home/Users/hashimn4/downloads

[0m[27m[24m[Jhashimn4@Hashims-MBP downloads % [K[?2004hggrep ""M"a"y"[1C hurricanes.csv[?2004l

"May",  0.1,  0,  0, 1, 1, 0, 0, 0, 2, 0,  0,  0  
[1m[7m%[27m[1m[0m                                                                               
 
]7;file://Hashims-MBP.home/Users/hashimn4/downloads

[0m[27m[24m[Jhashimn4@Hashims-MBP downloads % [K[?2004h
![image](https://user-images.githubusercontent.com/61445847/111200548-44c1b200-8598-11eb-85b7-58953b7d796a.png)
