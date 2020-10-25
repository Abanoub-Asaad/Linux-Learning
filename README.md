## Linux Commands 🧑‍💻

Command | Description
------- | -----------
shutdown now | To shut down the pc
reboot | To restart the pc
clear | To clear all previous commands and results that were in terminal
exit | To close the open trminal
passwd | To change the password of the current user
pwd | "print working directory"
ls | “list” to list all files that in the current directory
ls -l | To list all files that in the current directory with more details
ls -a | To list all files that in the current directory and the other hidden ones
ls -la | To list all files that in the current directory and the other hidden ones with more details
cd < path > | “change directory” to change the current directory
cd | To go to the home page
cd ~ | To go to the home page
cd .. | To go back one directory
sudo -i | To be a super user
mkdir < folder name > | “make directory” to make a new folder in the current directory
rmdir < folder name > | “remove directory” to remove a specific folder that in the current directory
touch < file name > | To make a new file in the current directory
rm < file name > | “remove” to remove a specific file that in the current directory
cp < file name > < new file name > | “copy” to make a copy of a specific file
mv < file name > < destination directory > | “move” to move a specific file to another directory
mv < file name > < another file name > | To rename a specific file
grep < string > < file name > | “global regular expression print” to search for a specific word in a specific file
diff < file name > < another file name > | “difference” to compare the contents of file1 and file2 and show the differences between them
echo < string > | To print a string
echo $< variable name > | To print the value of a specific variable
info < command > | To print some information about a specific command
gzip < file name > | To compress a specific file to zip format
gunzip < file name .gz > | To extract a zip file
tar cvf < new compressed file name .tar > < file to compress > <> <> | To compress some files
tar xvf < compressed file .tar > | To extract a compressed file


## Not always used commands 🧐

Command | Description
-- | --
sudo grep psk= /etc/NetworkManager/system-connections/* | To get the password of the connected wifi
sudo service network-manager restart | If you closed or killed the network by mistake you can restart it by this way
sudo apt-get --purge remove < package name > | To uninstall a specific program
sha1sum < file name > | To get the hash code "SHA-1 number" of a specific file


## Tricks `In terminal` ✸🧙‍✹

Trick | Description
-- | --
Tab | It's used for autocompletion `commands or arguments`
Ctrl + a | To move to the beginning of the line 
Ctrl + e | To move to the end of the line 
command_1; command_2; command_3 | To run multiple commands in one single command
command_1 && command_2 | To run multiple commands in one single command only if the previous command was successful
Ctrl+r search_term | It's a `reverse search` and used for easily search for a command in the history using a search term
Ctrl + q | If you probably clicked on `ctrl+s` for saving and you're in the terminal, you'll have a frozen terminal. so by this way you can use the terminal again
⬆️ `Up key` | To get to the previous command


## File Permissions `In terminal` ⚙️🔒

u  -> user 	   <br>
g  -> group 	   <br>
o  -> other people <br>

`chmod 754 <file name>` <br>

7, 5, 4 represent the individual permissions for (in this order) user, group, other <br>

4  ->  stands for "read"    <br>
2  ->  stands for "write"   <br>
1  ->  stands for "execute" <br>
4  ->  stands for "no permissions".


