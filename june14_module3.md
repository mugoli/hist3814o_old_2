# Module 3

### Exercise 1

* I am having a lot of trouble with this exercise. I have been trying this for over two hours, and simply can not manage to get things right.
* When I look for the data in texas.txt, it already comes with tidles in front
* When I attempt to save the file, it saves as an html file, rather than a file where all the data is cleaned.
I have not been keeping track of each and every single step of the process, so I will attempt to chronicle this again.

DAY TWO

* My problem was that I had missed the step of exporting texas.txt as a file, opening it with a text editor on my desktop, deleting the unecessary lines, then reuploading the new texas.txt. I have no clue why I kept missing this step.
* I succesfully used the functions I RegX functions to add the ~, remove them, separate the columns, and clean up the dated entries. After much, much effort.

### Exercise 2
* I am realising that OpenRefine is basically a more accessible version of all of the exercises we have been doing in Module 2. Using the command line was a way of understanding the background workings of this tool. Similarily to learning a new language, learning words is more fun to do, but studying grammar and syntax are what allow you to manage to speak on your own, rather than relying on random words.
* I succesfully managed to download OpenRefine. 
* I then clustered the data and attempted to clean it
* At first, I seemed o only be able to get to 175 entries for the sender, although the workbook target was 160
* I found that using the "nearest neighbor" method with the "levenshtein" distance function, and playing with the Radius rather than the Block Chars allowed me to find the last bits of data clusters that I couldn't seem to find.
* In total, I have 148 senders, and 162 recipients.
* I saved the csv file, and also saved the two-column (source -> target) .csv file, which I then uploaded to my DH Box

Notes: I am noticing that a few lines here and there (not plenty) are missing dates. This may be due to a mistake I made during a previous exercise while manipulating the texas.txt file, or maybe it is just because there is no data for that entry.

