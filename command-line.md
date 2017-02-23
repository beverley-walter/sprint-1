# Sprint One

## Without using jargon, how would you describe the command line to a lay person (e.g. your mum)?
Its the domain of uber geeks! The command line - also referred to as terminal, shell or prompt - is a way of accessing the folder/directory structure (and files within the folders/ \directories) of your computer. Which enables certain tasks to be completed using text commands, rather than menus and mouse direction.

## List 10 terminal commands and in plain English (i.e. with minimal technical jargon) describe what they do.
Command prompts - specifically for Ubuntu (should work on most distributions)
1.      cp: Copies a file. E.g. cp file bev, this command makes an extra copy of the file selected. The first file still exists, with its original name
2.      mv: Moves a file to another location (and can rename). E.g. mv file bev will name the file, bev, mv bev ~/Desktop will move the file to my desktop, but not rename it.
3.      mkdir: This command allows you to create a directory. E.g mkdir music, creates a music directory.
4.      chmod: Changes the permissions of the files. Permissions for user, group, and world, can be set to read, write or execute. E.g. everyone can read a file but only the user can    write to it, it would read rwxr--r--. To change the permission you use either a + or – in front of a specific permission, e.g. chmod g+x bev
5.      chown: Changes the ownership of files and folders – for different users.
6.      free: Will display the amount of free and used memory in the system, using megabyes. E.g. free-m
7.      top: Displays information on your Linux system, running processes, and system resources, including CPU, RAM and the total number of tasks being run. (To exit top, press Q).
8.      ps: Allows you to see all processes running on the machine.
9.      grep: The grep command allows you to search for a particular pattern e.g. a word or bit of text, like bev, it will then list the titles in a file which have matching lines. E.g. grep bev file. Matching the pattern ‘bev’ in the file ‘file’. (Can be used with ls… as in, ls |grep bev).
10.   sed: Or Stream EDitor, will allow you to search for a pattern or text, and change it. So it will file occurances of ‘cat’ and can change them to ‘chicken’, in a file named pets E.g. sed/cat/chicken/g pets
11.   ping: Tell you how long it takes for the connection to reach the server. (added the 11th as its the only one I knew before doing anything.)
