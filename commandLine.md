## The command line 

Linux has a graphical user interface and it works pretty much like the GUI's on other systems that you are familiar with such as Windows and OSX.

***What is command line:*** <br>

A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

- opening terminal :

1. find the program Terminal under Applications -> Utilities.  <br>
<br>

2. click 'command + space' then start typing Terminal and it will soon show up.


## Basic Navigation :
- **pwd** :  Print Working Directory - ie. Where are we currently.<br>

- **ls** : List the contents of a directory. <br>

- **cd** :Change Directories - ie. move to another directory. <br>   

***Important conpcepts*** <br>

- Relative path:
A file or directory location relative to where we currently are in the file system. <br>

- Absolute path : 
A file or directory location in relation to the root of the file system. <br>


## More about Files :
- ***file***:
obtain information about what type of file a file or directory is.
<br>

- ***ls -a*** :
List the contents of a directory, including hidden files.


***Important conpcepts*** <br>
- Everything is a file under Linux
**Even directories**.<br>

- Linux is an extensionless system 
Files can have any extension they like or none at all.

- Linux is case sensitive <br>
Beware of silly typos.


## Manual pages :

- man : <br> 
Look up the manual page for a particular command.<br>

- man -k "search term" : <br>
  Do a keyword search for all manual pages containing the given search term.<br>

- "/term" :<br>
  Within a manual page, perform a search for 'term' <br>
- n : <br>
After performing a search within a manual page, select the next found item.

***The man pages are your friend.
Instead of trying to remember everything, instead remember you can easily look stuff up in the man pages.*** 


### File manipulation :

 - ***mkdir*** : 
Make Directory - ie. Create a directory.

- ***rmdir*** :
Remove Directory - ie. Delete a directory.

- ***touch*** :
Create a blank file.
- ***cp*** :
Copy - ie. Copy a file or directory.
- ***mv*** :
Move - ie. Move a file or directory (can also be used to rename).

- ***rm*** : 
Remove - ie. Delete a file. 

***important concepts*** :
- ***No undo*** :
 The Linux command line does not have an undo feature.<br>

***Command line options*** :
Most commands have many useful command line options. Make sure you skim the man page for new commands so you are familiar with what they can do and what is available.