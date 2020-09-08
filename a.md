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
