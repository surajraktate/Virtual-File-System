# Virtual-File-System


#Technology: C
Description:

The Virtual File system provides all the functionality to the user which is same
as the UNIX based fle system.

It provides all necessary commands and system calls implementations of fle
system through customised shell.

In this project we implement all necessary data structures of File Subsystem as
Inode, Incore Inode Table, File Table, User File Descriptor Table etc.

By using this project we can emulate UNIX fle system on any windows
platform

Commands

  ls      : To list out all files
	clear   : To clear console
	open    : To open the file
	close   : To close the file
	closeall: To close all opened files
	read    : To read the contents from file
  write   : To write contents into file
	exit    : To terminate file system
	stat    : To display information of file using name
	fstat   : To display information of file using file descriptor
	truncate: To remove all data from file
	rm      : To delete the file
