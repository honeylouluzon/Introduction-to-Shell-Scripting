# Introduction to Linux Commands and Shell Scripting

This repository contains a Jupyter Notebook (`linux.ipynb`) that demonstrates various Linux commands and their usage. Below is a preview of the notebook's content:

## Notebook Preview

1. **Update System Packages**
   - Command: `sudo apt update`
   - Description: Updates the list of available packages and their versions.

2. **Search Manual Pages**
   - Command: `man -k .`
   - Description: Searches the manual pages for all available commands.

3. **View Manual for `ls` Command**
   - Command: `man ls`
   - Description: Displays the manual for the `ls` command.

4. **List Files in Directory**
   - Command: `ls`
   - Description: Lists all files in the current directory.

5. **Install `tldr` Command**
   - Command: `npm install -g tldr`
   - Description: Installs the `tldr` command for simplified manual pages.

6. **View `tldr` for `ls` Command**
   - Command: `tldr ls`
   - Description: Displays a simplified manual for the `ls` command.

7. **Display Current User**
   - Command: `whoami`
   - Description: Displays the username of the current user.

8. **Display System Name**
   - Command: `uname`
   - Description: Displays the system's name.

9. **Display System Information**
   - Command: `uname -a`
   - Description: Displays detailed system information.

10. **Display User ID**
    - Command: `id`
    - Description: Displays the user ID and group ID of the current user.

11. **Display User Numeric ID**
    - Command: `id -u`
    - Description: Displays the numeric user ID of the current user.

12. **Display User Name from Numeric ID**
    - Command: `id -u -n`
    - Description: Displays the username corresponding to the numeric user ID.

13. **Display Disk Usage**
    - Command: `df`
    - Description: Displays disk space usage.

14. **Display Disk Usage (Human-Readable)**
    - Command: `df -h`
    - Description: Displays disk space usage in a human-readable format.

15. **List Running Processes**
    - Command: `ps`
    - Description: Lists currently running processes.

16. **List All Processes**
    - Command: `ps -e`
    - Description: Lists all processes running on the system.

17. **Print Environment Path**
    - Command: `echo $PATH | tr ':' '\n'`
    - Description: Prints each directory in the PATH environment variable on a new line.

18. **Print a Message**
    - Command: `echo "Hello World!"`
    - Description: Prints the message "Hello World!" to the terminal.

19. **Print Formatted Text**
    - Command: `echo -e "Printing\nThis 2nd line."`
    - Description: Prints formatted text with a newline.

20. **Display Current Date**
    - Command: `date`
    - Description: Displays the current date and time.

21. **Display Custom Date Formats**
    - Commands:
      - `date "+%Y"`
      - `date "+%D"`
      - `date "+The current time is %T"`
    - Description: Displays the year, date, and a custom time format.

22. **List Files in Parent Directory**
    - Command: `ls ../..`
    - Description: Lists files in the parent directory two levels up.

23. **List Files in Home Directory**
    - Command: `ls ~`
    - Description: Lists files in the home directory.

24. **Print Current Directory**
    - Command: `pwd`
    - Description: Prints the current working directory.

25. **Change Directory to Home and Print**
    - Commands:
      - `cd ~`
      - `pwd`
    - Description: Changes to the home directory and prints the current directory.

26. **Navigate to Workspace Directory**
    - Commands:
      - `cd ../../workspace/Introduction-to-Shell-Scripting`
      - `pwd`
      - `ls`
    - Description: Navigates to the workspace directory, prints the current directory, and lists its contents.

27. **List Files in Parent Directory**
    - Command: `ls ..`
    - Description: Lists files in the parent directory.

28. **List Files in Current Directory**
    - Commands:
      - `ls .`
      - `pwd .`
    - Description: Lists files in the current directory and prints its path.

29. **Create and Remove a Sample Directory**
    - Commands:
      - `mkdir sample`
      - `ls`
      - `touch sample.md`
      - `ls`
      - `rm sample.md`
      - `rm -r sample`
      - `ls`
    - Description: Demonstrates creating, listing, and removing a directory and file.

30. **View Shell Script Content**
    - Command: `cat linux.sh`
    - Description: Displays the content of the `linux.sh` file.

31. **View Manual for Bash**
    - Command: `man bash`
    - Description: Displays the manual for the Bash shell.

## Access the Notebook

[View the Notebook](linux.ipynb)
