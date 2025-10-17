# CS Meeting: Windows

# CMD Line Workshop
**Basic Commands (Directory Navigation)** <br>
- ">" means the end of a path, for example C:\>cd users\foldername
- defaulted to home directory
- To change the directory (place where the cmd prompt is looking at), cd:[args]
- cd stands for change directory
- to go back a level: cd ... to go back two or more cd/ ... to go back to root directory cd\
- To change drive :A:
- To clear screen: cls
- TAB to search through options (for example you want to find a directory)
- to exit cmd, exit
<br><br>

**Create and View Directory Content** <br>
- To view contents of directory ... dir ... add file name to find something in particular
- If you're looking for a specific file type but you don't know the name, use an asterick ... it means "anything, wildcard." *.txt for example
- To make a folder ... mkdir OR md
- Make multiple folders, just list serveral names after the command above
- make a file: type nul > name ... OR echo. > name (this command kinda sucks since it creates a zero byte file)
- ex type num > main.cpp
- contents of file: type name
<br><br>

**Deleting Stuff** <br>
- delete ... del
- remove a folder ... rmdir OR rd
- you can't remove a whole directory, it keeps you a bit safe
<br><br>

**Change Directory Contents** <br>
- move a file (not deleting anything but I'm putting it under this header anyway) ... move file_name
- copy a file .... copy
- rename a file ... move OR ren
<br><br>

**Extra commands** <br>
- open a program, just type the name
YOU CAN CHANGE THE COLORS!
- color 0F (example to the left. The numbers are hex digits. 0F is the regular color set.)
- help command: help rmdir (for example)
- Up and down arrow key navigates through command history
<br><br>

**More extra contents** <br>
- PATH variable = environmental variable, can be used to search through all directories store here
- see all file paths .. tree
- get names of all drive names ... wmic logicaldisk get name
- replace file with >
- append files with >>
- show all attributes ... attrib />
- add attribute ... attrib +h
- remove attribute ... attrib -h
<br><br>

**fun cool stuff?** <br>
- xcopy (a better copy command)
- set command (like let in javascript, creates variables) --> display with echo... echo %variablename%


## Final Thoughts
