# Unix Commands Used in Data Engineering.
This repository contains all the basic Unix commands, their explanation and Usage that are used in the field of data engineering. 

## Introduction
### What is Unix ? 
- Unix is an Operating System which is a set of programs that acts as a link between the computer hardware and the user. 
- Unix was developed in 1969 by a group of AT&T employees namely Ken Thompson, Dennis Ritchie, Douglas McIlroy and Joe Ossanna at Bell Labs. 
- Various Unix varients include Solaris Unix, HP Unix, BSD etc. Linux is also a flavor of Unix. 
- Unix is a **multiuser system**, which means that several people can use a unix system at the same time. 
- Unix has a **multitasking environment** which means that a user can run multiple programs at the same time. 

### Unix Architecture
1. **Kernel** : 
	- Kernel aka Operating System are a set of computer programs that allocate the system resources and coordinate the details of the computer's internal programs. 
	- It is the heart of the operating system. 
	- It interacts with the hardware and most of the tasks like memory management, task scheduling and file management. 

2. **Shell** : 
	-  The Shell is basically a program through which the user communicates with the kernel. It is a command line interpreter that translated commands entered by the user and converts them into a language that is understood by the kernel. 
	- It is the utility that processes the user's requests.
	- When a command it typed by the users, the shell interprets the command and calls the appropriate program. 
	- C Shell, Bourne Shell and Korn Shell are exampled of famous shell programs used in various Unix variants. 

3. **Command and Utilities** : 
	- Command are strings when typed into the shell, run a specific program. 
	- There are over 250 plus commands and many more provided through third party software. 
	- Examples : **cp**, **mv**, **cat**, **grep** etc. 

4. **Files and Directories** : 
	- All data in Unix are organized into files. 
	- The files are then organized into directories. 
	- These directories are further organized into a tree-like structure called the **filesystem**.
	
## Basic Commands
1. **ls** : 
	Lists all the available files and sub-directories in a given directory. 
	Syntax : 
	> `ls -option`

	Options : 
	- ***a*** : All files and sub-directories are listed, including the hidden ones. 
	- ***l*** : List files and directories along with their various permissions. 
	- ***al*** : Combination of ***a*** and ***l***. 

	Usage : 
	> `ls -al`

2. **mkdir** : 
	Used to create a directory. 
	Usage : 
	> `mkdir sample_directory`

3. **cd** : 
	Used to change directory. 
	Usage : 
	> `cd sample_directory` <br />
	`cd` or `cd ~` changes to home directory.<br /> 
	`cd ..` changes to parent directory. 

4. **pwd** : 
Short for Path to Working Directory. Prints out the path of the current directory with respect to the home directory. 
Usage : 
> `pwd`

5.  **cp** : 
	Short for copy. It copies a file or directory into another. It copies the contents of a file or directory into another file or directory respectively.  
	Usage : 
	> `cp file_or_directory_1 file_or_directory_2`

	Copies contents of file_or_directory_1 to file_or_directory_2.
