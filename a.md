# Bash commands
---------------------------------------------------------------------------------------------------------------------------------------------------------
## ls
### ls -a: 
It shows us the files and directories within the current directory, including hidden files and directories.
### ls -l:
It shows all the information: user, group, permissions, size, date and time of creation.
### ls -lh:
It shows the same information as ls -l but with the size units in KB, MB, etc.
### ls- h:
Print file sizes in a human-friendly way.
### ls - A:
List all files except the "." and the ".."
### ls * :
List all subdirectories.
### ls * .txt:
List only text files with wildcard.
### ls .* :
View hidden files.
## cp
### cp -i:
interactive - ask before overwrite
### cp -R:
recursive copy (including hidden files)
### cp -R/direction/destination: 
Copy the absolute direction where we are.
###  cp -i*.txt: 
Copy in the previous directory all the text files.
###  cp file1  file2: 
Copy the first file to another file.
## rm
### rm -R:
Delete directory contents recursively.
### rmdir:
Delete empty directories. This option allows us to delete a directory without specifying -r / -R / –recursive, as long as the directory is empty.
### rm * :
Use a wildcard (* ) and regular expansions to match multiple files. For example, to remove all .pdf files in the current directory, use the following command
## locate
## locate [filename]:
It is used to find files by their filename. 
## mv
### mv [OPTION]:
It is used to move files and directories.
### mv -f:
Force move by overwriting destination file without prompt.
## whoami [OPTION]
### whoami [OPTION]:
Prints the user name currently logged on to the computer on the screen.
### id:
To find out user and group names and numeric ID’s.
### stat:
It shows much more detail than what ls does. It is a command-line utility that displays detailed information about given files or file systems.
## Permission.
There are 3 basic attributes for simple files: read, write, and execute.

* Read permission (read):
**r** means writing and comes from Read
* Write permission (write):
**w** means read and comes from Write
* Execute permission (execute):
**x** means execution and comes from eXecute
### chmod +x filename: 
Give permission to the execution of the program.
### chmod -x filename: 
Quit permission to the execution of the program.
### chmod +w filename: 
Give permission to write of the program.
### chmod -w filename: 
Quit permission to write of the program.
### chmod +r filename: 
Give permission to read of the program.
### chmod -r filename: 
Quit permission to read of the program.
Also we have:
### chmod 0numbersofheinsruction filename: 
Change the permission to the execution of the program.        

* --- 0
* --x 1
* -w- 2
* -wx 3
* r-- 4
* r-x 5
* rw- 6
* rwx 7
## Find.
### find filename:
It used to search for files.
### find . filename:
To search the folder you are currently in.
### find . -atime +1:
To find all the files within your home folder accessed more than (day specified).
# Fin exercise:
---------------------------------------------------------------------------------------------------------------------------------------------------------
## 1. find . -type f -name "* .[OPTION]":
**$ find . -type f -name "*.py"**

./DRY_1.py        

./DRY_2.py       

./Error1.py        

./Errores.py        

./Exer_26.py       

./NUMPYS/Exe_1.py       
[...]


