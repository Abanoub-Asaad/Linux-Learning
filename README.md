# Sections

- [Linux Commands](https://github.com/Abanoub-Asaad/Linux-Learning#linux-commands-)
- [Important Commands](https://github.com/Abanoub-Asaad/Linux-Learning#Important-Commands-)
- [Tricks in Terminal](https://github.com/Abanoub-Asaad/Linux-Learning#tricks-in-terminal-)
- [Amzaing applications for Linux](https://github.com/Abanoub-Asaad/Linux-Learning#amzaing-applications-for-linux-) 
- [File Permissions In terminal](https://github.com/Abanoub-Asaad/Linux-Learning#file-permissions-in-terminal-%EF%B8%8F)

--------------------------------------

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
< program_name > & | To open a specific program
pkill < program_name > | To close a specific program
application_name -version | To know the version of a specific application

## Important Commands 🧐

Command | Description
-- | --
sudo grep psk= /etc/NetworkManager/system-connections/* | To get the password of the connected wifi
sudo service network-manager restart | If you closed or killed the network by mistake you can restart it by this way
sudo apt-get install < package name > | To install a specific program
sudo apt-get --purge remove < package name > | To uninstall a specific program
sha1sum < file name > | To get the hash code "SHA-1 number" of a specific file
sudo parted -l | To manage partitions with GNU Parted
sudo fdisk -l | To manipulate disk partition table 


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


## Amzaing applications for Linux 🎧💻

Application Name | Description | Installation Command
-- | -- | --
Rambox | is a workspace browser that allows you to manage as many applications as you want, all in one place | sudo snap install ramboxpro
Kodi | is a free media player that is designed to look great on your big screen TV but is just as home on a small screen | sudo apt install kodi
Stacer | is an open source system optimizer and application monitor that helps users to manage entire system with different aspects | sudo apt install stacer
Calibre | The one stop solution for all your e-book needs. Comprehensive e-book software | sudo apt-get install calibre
Kdenlive | A software for video editing | sudo apt install kdenlive
NitroShare | is designed to make transferring files from one device to another extremely simple | sudo apt-get install -y nitroshare
GIMP | is an image editor like photoshop | sudo apt-get install gimp
Mega | is a cloud storage and file hosting service | sudo apt-get install megatools 
Steam | is the ultimate destination for playing, discussing, and creating games | sudo apt-get install steam 


## File Permissions `In terminal` ⚙️🔒

u  -> user 	   <br>
g  -> group 	   <br>
o  -> other people <br>

`chmod 754 <file name>` <br>

7, 5, 4 represent the individual permissions for (in this order) user, group, other <br>

4  ->  stands for "read"    <br>
2  ->  stands for "write"   <br>
1  ->  stands for "execute" <br>
0  ->  stands for "no permissions".

## Others
- [How To Use SSH To Connect To A Remote Server In Linux Or Windows](https://phoenixnap.com/kb/ssh-to-connect-to-remote-server-linux-or-windows)
- [How to use rsync to copy files](https://linuxhint.com/rsync_copy_files/)


