*THIS IS THE README FILE FOR THE 0x02-shell_redirections PROJECT*

This project consists of several tasks as follows

TASK 0 - Hello World [0-hello_world]
       	 Write a script that prints “Hello, World”, followed by a new line to the standard output.

TASK 1 - Confused smiley [1-confused_smiley]
       	 Write a script that displays a confused smiley "(Ôo)'.
TASK 2 - Let's display a file [2-hellofile]
       	 Display the content of the /etc/passwd file.
TASK 3 - What about 2? [3-twofiles]
       	 Display the content of /etc/passwd and /etc/hosts
TASK 4 - Last lines of a file [4-lastlines]
       	 Display the last 10 lines of /etc/passwd
TASK 5 - I'd prefer the first ones actually [5-firstlines]
       	 Display the first 10 lines of /etc/passwd
TASK 6 - Line #2 [6-third_line]
       	 Write a script that displays the third line of the file iacta.
	 The file iacta will be in the working directory
	     You’re not allowed to use sed
TASK 7 - It is a good file that cuts iron without making a noise [7-file]
       	 Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) 
	 containing the text Best School ending by a new line.
TASK 8 - Save current state of directory [8-cwd_state]
       	 Write a script that writes into the file ls_cwd_content the result of the command ls -la. 
	 If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content 
	 does not exist, create it.
TASK 9 - Duplicate last line [9-duplicate_last_line]
       	 Write a script that duplicates the last line of the file iacta
	 The file iacta will be in the working directory
TASK 10 - No ore javascript [10-no_more_js]
     	  Write a script that deletes all the regular files (not the directories) with a .js extension 
	  that are present in the current directory and all its subfolders.
TASK 11 - Don't just count your directories, make your directories count [11-directories]
     	  Write a script that counts the number of directories and sub-directories in the current directory.
	  * The current and parent directories should not be taken into account
	  * Hidden directories should be counted
TASK 12 - What's new [12-newest_files]
     	  Create a script that displays the 10 newest files in the current directory.
	  Requirements:
		* One file per line
		* Sorted from the newest to the oldest
TASK 13 - Being unique is better than being perfect [13-unique]
     	  Create a script that takes a list of words as input and prints only words that appear exactly once.
	  	 Input format: One line, one word
		 Output format: One line, one word
		 Words should be sorted
TASK 14 - It must be in that file [14-findthatword]
     	  Display lines containing the pattern “root” from the file /etc/passwd
TASK 15 - Count that word [15-countthatword]
     	  Display the number of lines that contain the pattern “bin” in the file /etc/passwd
TASK 16 - What's next? [16-whatsnext]
     	  Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
TASK 17 - I hate bins [17-hidethisword]
     	  Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
TASK 18 - Letters only please [18-letteronly]
     	  Display all lines of the file /etc/ssh/sshd_config starting with a letter.
	  include capital letters as well
TASK 19 - A to Z [19-AZ]
     	  Replace all characters A and c from input to Z and e respectively.
TASK 20 - Without C, you would live in hiago [20-hiago]
     	  Create a script that removes all letters c and C from input.
TASK 21 - esreveR [21-reverse]
     	  Write a script that reverse its input.
TASK 22 - DJ Cut Killer [22-users_and_homes]
     	  Write a script that displays all users and their home directories, sorted by users.
	  Based on the the /etc/passwd file 

*ADVANCE TASKS*
==============================
TASK 23 - Empty casks make the moset noise [100-empty_casks]
     	  Write a command that finds all empty files and directories in the current directory and all sub-directories.
	  	Only the names of the files and directories should be displayed (not the entire path)
		Hidden files should be listed
		One file name per line
		The listing should end with a new line
		You are not allowed to use basename, grep, egrep, fgrep or rgrep
TASK 24 - A gif is worth ten thousand words [101-gifs]
     	  Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories.
	  	Hidden files should be listed
		Only regular files (not directories) should be listed
		The names of the files should be displayed without their extensions
		The files should be sorted by byte values, but case-insensitive 
		(file aaa should be listed before file bbb, file .b should be listed before file a, and file 
		Rona should be listed after file jay)
		One file name per line
		The listing should end with a new line
		You are not allowed to use basename, grep, egrep, fgrep or rgrep
TASK 25 - Acrostic [102-acrostic]
     	  An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval. Read more.

	  Create a script that decodes acrostics that use the first letter of each line.
       	  The ‘decoded’ message has to end with a new line
	  You are not allowed to use grep, egrep, fgrep or rgrep
TASK 26 - The biggest fan [103-the_biggest_fan]
Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
      	       Order by number of requests, most active host or IP at the top
	       You are not allowed to use grep, egrep, fgrep or rgrep