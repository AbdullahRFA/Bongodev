Here are some basic macOS Terminal commands that can help you with day-to-day tasks:

1. Navigating Directories

	•	pwd (Print Working Directory): Shows the current directory you’re in.

pwd


	•	ls (List): Lists files and directories in the current directory.

ls

	•	To show hidden files:

ls -a


	•	To display more details (permissions, size, date):

ls -l


	•	cd (Change Directory): Navigate between directories.

cd <directory-path>

	•	To go back to the previous directory:

cd ..


	•	To go to the home directory:

cd ~



2. File Management

	•	touch: Create a new empty file.

touch filename.txt


	•	mkdir: Create a new directory (folder).

mkdir my_directory


	•	cp: Copy a file or directory.

cp source_file destination_file

	•	To copy a directory, use the -r option:

cp -r source_directory destination_directory


	•	mv: Move or rename a file or directory.
	•	To move:

mv source_file destination_directory/


	•	To rename:

mv old_filename new_filename


	•	rm: Remove (delete) a file.

rm filename.txt

	•	To remove a directory and its contents, use the -r option:

rm -r directory_name



3. File Viewing and Editing

	•	cat: View the contents of a file.

cat filename.txt


	•	nano: Edit a file directly in the terminal using the nano text editor.

nano filename.txt


	•	open: Open a file or directory in its default app (Finder, text editor, etc.).

open filename.txt



4. File Permissions

	•	chmod: Change the permissions of a file or directory.
	•	Example to make a file executable:

chmod +x script.sh



5. Network Commands

	•	ping: Check the connection to a website or IP address.

ping google.com

	•	Press Ctrl + C to stop.

	•	ifconfig: View network interface configuration.

ifconfig


	•	curl: Make HTTP requests to a URL.

curl https://example.com



6. System Information and Monitoring

	•	top: View real-time system resource usage (like Task Manager).

top

	•	Press q to exit.

	•	df: Show disk space usage.

df -h


	•	du: Show the size of files and directories.

du -sh <file_or_directory>


	•	whoami: Display the current logged-in user.

whoami



7. Search and Find

	•	find: Find files and directories by name.

find . -name "filename.txt"


	•	grep: Search for specific text within files.

grep "search_term" filename.txt



8. Miscellaneous

	•	clear: Clear the terminal screen.

clear


	•	history: Show the list of previously used commands.

history


	•	exit: Close the terminal session.

exit



These commands should help you navigate and manage your files more efficiently on macOS! Let me know if you need more specific commands or help with something else.
