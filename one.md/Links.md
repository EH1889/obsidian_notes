In [[Linux]] to create a link between files use the ln command.
a -s is used for a soft link or a symbolic link. The hard link points to the inode and thus a copy is made. There is no longer an originonal version at this point.
 -d is for directory, you cannot hardlink directories

to find by link

find file/ -type l 
