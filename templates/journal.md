# Thomas's Technical Journal

## Week Two (1/30 to 2/6)

This week, I spent part of my time reviewing Git and the command line and reading about the history FOSS and design principles.  I was already familiar with the command line, so spent the time working on upgrading my laptop's drive to an SSD.  Time was also spent on a work project invol

*Hour 1: Spent the time figuring out how to clone an harddrive in Linux.  Found out about "rsync" which seems very useful
*Hour 2: Cloning a harddrive in Linux seemed overly complicated, so I did a clean install and began setting up software needed (laptop is for class)
*Hour 3: Read *Decoding Liberation*
*Hour 4: Started reading *The Design of Design*
*Hour 5: Reviewed Git using the DHRI Git tutorial, looked into VS Code as a editor to use
 

## Week Three (2/7 to 2/13)

This week I started learning how to use python.  I've done a tutorial before, but didn't remember much of it

*Hour 1: Installed Anaconda, set up a lesson folder, and started *Learn Python3 the Hard Way*, started with excersice 0 and looked at the different types of text editors online 
*Hour 2: Did excercises 1-6, played around with the Study Drills too, didn't run into any problems
*Hour 3: Did excercises 7-11, added played around with input() with some older excercises
*Hour 4: Did excercises 12 & 13, played around with inputs and modules a bit


## Week Four (2/14 to 2/20)

This week I continued *Learn Python3 the Hard Way*

*Hour 1: Did excercise 14, started playing *Zork* got 15 points and killed by the troll in the basement. Did actually think about how the commands and prompts were structed to make the game work.
*Hour 2: Did excercise 15, including "Study Drills," ran into some problems figuring out how to get the script to work with input() and including close().  Realized I could change an older script I had to convert excel to XML, but then realized this was written in python 2 and decided  to save that project for later. Did excercise 16.
*Hour 3: Did excercise 17, spent most of the time figuring out how to get the code down to one line. 
*Hour 4/5: Did excercises 18-21, stopped before doing ex21 study drills.

## Week 5 (2/21 to 2/27)

More python

*Hours 1&2: I took the python2 script I had to convert Excel sheet into indivudual XML files so it would work in python3.  At first it worked, but then noticed a lot of fields were missing.  After running it a few times I realized I was missing the code to write those specific fields. Got that working, but the "Date" field kept not showing up.  After a whole lot more poking around, I realized Python wasn't reading the Date column, because the column was listing the dates as dates, not as plain text. This led to some reformatting in Excel and now the files are exported correctly. The remaining issue is a "Traceback ....." error because the script reads past the last row and is hitting blank "Filename" cells or reading a column too far.  Will investigate more later.
*Hour 3: Set up Jekyll.  Installed it the basic way first and nothing worked, then I found the better and more detailed instructions and got it all up and running
*Hour 4/5ish: Worked on Python3 The Hard Way, did ex22 which has you write down and list every command so far.  I found this very useful since I realized I forgot a bunch of things.
*Hour 5ish?: Worked on a topic modeling project using Mallet, but this time instead of using RStudio to melt and reform the data, I used pandas in python to create the final excel doc. Started looking into using Python to model n-grams.


## Week 6 (2/28 to 3/6)

Spent time reading about free software and opensource software, looked into what the GNU-GLP license says

Coding practice:
*Hour 1-3: Returned to *Learn Python 3*, started excercise 23, eyes glazed over at Unicode, read through the whole thing slowly, sort of understood it.  Example 24 went fine.  Hit a lot of trouble with example 25, in the part of working directly in python (rather than a python file).  Besides typos I hit a "UnboundLocalError" saying that the variable is being referenced before being assigned, even though that part of code is where the variable is being assigned.  After a long time poking around, I realized I was missing a chunk of code. 

## Week 7 (3/7 to 3/13)

Didn't have a whole lot of time this week to do home work
Hour 1-2: Played around with using text analysis with Mallet on the command line

## Week 8 (3/14 to 3/20)

Didn't have a huge amount of time to practice python, but spent many hours trying to troubleshoot a repository at work

*Hour 1: Did ex26 in *Learn Python*, edited to justly say there cannot be too many cats.
*Hour 2: Started memorizing the logic tables and looking at the Boolean  expressions
*Hour 3: Worked on ex31 but didn't go super into the study drills. Got stumped on ex32 on how to append assign a range directly to a list, not entirely sure it's possible

## Weeks 9-12 

My playing around with python was spread out all over the place and I had to spend more time on my other class, a work projects, and dealing with a corrupt hard drive on another laptop, but did work my way through more *Learn Python*.
I spent a lot of time on ex36 where you remake the game that was introduced earlier. It was fun and I played around with While statements and trying to carry some "If Trues" to other rooms, with the idea that the player can pick up an item in one room, turning "item = FALSE" to "item = TRUE" and then have that be referenced later in another room.  I made a potion that if true, would automatically heal you after a "death" incident, letting you keep playing.  Now I'm at ex38 which involves lists and thinking on how this can be used better for an inventory.
I also worked on the Rob's Network Analysis project, looking into how the csv library/module works and statements we can use in it.  This led to a rabbit hole of getting Gephi to work on my laptop and setting up the JRE 8.

### Weeks 13-14

 Been working on Robs Network Analysis project. My goal is to take the name, workshop pairs and then end up with a final csv that pairs each name together based on workshops atteneded together.  The idea is that you then have a long name,name csv that links people who atteneded a single workshop together.  It took me a long time to figure out how to approach the problem, but maybe 8-10 hours of searching and reading stackoverflow made me realize I need to import the csv as a dictionary and arrange the data likst workshop [name1, name2, etc.]. I've gotten up to that step and have been able to output the dictionary so each key(workshop) is on it's own line.  Now I'm trying to figure how to pair up the values in each dictionary and create the last csv.