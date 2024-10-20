# Basic macOS Terminal Commands for Day-to-Day Usage

This README contains essential macOS Terminal commands that are helpful for daily tasks such as file management, navigation, network operations, and system monitoring.



 1. Navigating Directories

	pwd: Print the current directory path.

		pwd


	ls: List files and directories.

		ls

	Show hidden files:

		ls -a


	List files with detailed information (permissions, size, date):

		ls -l


	cd: Change directory.

		cd <directory-path>

	Move to the parent directory:

		cd ..


	Move to the home directory:

		cd ~



2. File Management

	touch: Create an empty file.

		touch filename.txt


	mkdir: Create a new directory.

		mkdir my_directory


	cp: Copy a file.

		cp source_file destination_file

	To copy a directory (recursively):

		cp -r source_directory destination_directory


mv: Move or rename a file or directory.
	Move:

	mv source_file destination_directory/
 Rename:

	mv old_filename new_filename
 rm: Remove a file.

	rm filename.txt
 To remove a directory and its contents (recursively):	
 
 	rm -r directory_name



3. File Viewing and Editing

	cat: View the contents of a file.

		cat filename.txt


	nano: Edit a file directly in the terminal.

		nano filename.txt


	open: Open a file or directory in its default application (e.g., Finder, text editor).

		open filename.txt



4. File Permissions

	•	chmod: Change file or directory permissions.
	•	Make a file executable:

		chmod +x script.sh



5. Network Commands

	ping: Check the connection to a website or IP address.

		ping google.com

	•	Press Ctrl + C to stop.

	•	ifconfig: View network interface configuration.

ifconfig
	curl: Make HTTP requests to a URL.

		curl https://example.com



6. System Information and Monitoring

	top: View real-time system resource usage (like Task Manager).

		top

	•	Press q to exit.

	df: Show disk space usage.

		df -h


	du: Show the size of files and directories.

		du -sh <file_or_directory>


	whoami: Show the current logged-in user.

		whoami



7. Search and Find

	find: Find files and directories by name.

		find . -name "filename.txt"


	grep: Search for specific text within files.

		grep "search_term" filename.txt



8. Miscellaneous

	clear: Clear the terminal screen.

		clear


	history: Show a list of previously used commands.

		history


	exit: Close the terminal session.

		exit



This format is ready to use in a README.md file for your GitHub repository! Let me know if you need anything else.


##To write to a file using Vim and save your changes, follow these steps:

##Steps to Write, Save, and Exit in Vim:

1.	Open the file with Vim:
To open an existing file or create a new one, use the following command in the terminal:

		vim filename.txt

2.	Enter Insert Mode:
When you open Vim, you’re in “normal mode,” which means you can move around but cannot insert text. To start editing the file, switch to insert mode by pressing:

		i

This will allow you to start typing and make changes to the file.

3.	Write Your Text:
Now, you can start writing or modifying text as needed.
4.	Save and Exit:
After you’re done writing, follow these steps to save and exit:
•	First, exit insert mode by pressing:

			Esc


•	Then, to save and quit, type the following and press Enter:

	:wq

•	:w means write (save the file).
•	:q means quit (exit Vim).
You can also use :x, which does the same as :wq.

Additional Options:

•	If you want to save the file without exiting, type:

	:w


•	If you want to quit without saving changes, type:

	:q!

The ! forces Vim to quit without saving.

Example Workflow:

1.	Open a file:

		vim myfile.txt


	2.	Press i to enter insert mode and write your content.
	3.	Once done, press Esc to exit insert mode.
	4.	Type :wq and press Enter to save and quit.

Let me know if you need more details!
