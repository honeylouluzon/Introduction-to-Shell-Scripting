# Introduction to Linux Commands and Shell Scripting

This repository contains a Jupyter Notebook (`linux.ipynb`) that demonstrates various Linux commands and their usage. Below is a preview of the notebook's content:

## Notebook Preview

1. **Update System Packages**
   - Command: `sudo apt update`
   - Description: Updates the list of available packages and their versions.
   - Location: Cell 1

2. **Search Manual Pages**
   - Command: `man -k .`
   - Description: Searches the manual pages for all available commands.
   - Location: Cell 2

3. **View Manual for `ls` Command**
   - Command: `man ls`
   - Description: Displays the manual for the `ls` command.
   - Location: Cell 3

4. **List Files in Directory**
   - Command: `ls`
   - Description: Lists all files in the current directory.
   - Location: Cell 4

5. **Install `tldr` Command**
   - Command: `npm install -g tldr`
   - Description: Installs the `tldr` command for simplified manual pages.
   - Location: Cell 5

6. **View `tldr` for `ls` Command**
   - Command: `tldr ls`
   - Description: Displays a simplified manual for the `ls` command.
   - Location: Cell 6

7. **Display Current User**
   - Command: `whoami`
   - Description: Displays the username of the current user.
   - Location: Cell 7

8. **Display System Name**
   - Command: `uname`
   - Description: Displays the system's name.
   - Location: Cell 8

9. **Display System Information**
   - Command: `uname -a`
   - Description: Displays detailed system information.
   - Location: Cell 9

10. **Display User ID**
    - Command: `id`
    - Description: Displays the user ID and group ID of the current user.
    - Location: Cell 10

11. **Display User Numeric ID**
    - Command: `id -u`
    - Description: Displays the numeric user ID of the current user.
    - Location: Cell 11

12. **Display User Name from Numeric ID**
    - Command: `id -u -n`
    - Description: Displays the username corresponding to the numeric user ID.
    - Location: Cell 12

13. **Display Disk Usage**
    - Command: `df`
    - Description: Displays disk space usage.
    - Location: Cell 13

14. **Display Disk Usage (Human-Readable)**
    - Command: `df -h`
    - Description: Displays disk space usage in a human-readable format.
    - Location: Cell 14

15. **List Running Processes**
    - Command: `ps`
    - Description: Lists currently running processes.
    - Location: Cell 15

16. **List All Processes**
    - Command: `ps -e`
    - Description: Lists all processes running on the system.
    - Location: Cell 16

17. **Print Environment Path**
    - Command: `echo $PATH | tr ':' '\n'`
    - Description: Prints each directory in the PATH environment variable on a new line.
    - Location: Cell 17

18. **Print a Message**
    - Command: `echo "Hello World!"`
    - Description: Prints the message "Hello World!" to the terminal.
    - Location: Cell 18

19. **Print Formatted Text**
    - Command: `echo -e "Printing\nThis 2nd line."`
    - Description: Prints formatted text with a newline.
    - Location: Cell 19

20. **Display Current Date**
    - Command: `date`
    - Description: Displays the current date and time.
    - Location: Cell 20

21. **Display Custom Date Formats**
    - Commands:
      - `date "+%Y"`
      - `date "+%D"`
      - `date "+The current time is %T"`
    - Description: Displays the year, date, and a custom time format.
    - Location: Cell 21

22. **List Files in Parent Directory**
    - Command: `ls ../..`
    - Description: Lists files in the parent directory two levels up.
    - Location: Cell 22

23. **List Files in Home Directory**
    - Command: `ls ~`
    - Description: Lists files in the home directory.
    - Location: Cell 23

24. **Print Current Directory**
    - Command: `pwd`
    - Description: Prints the current working directory.
    - Location: Cell 24

25. **Change Directory to Home and Print**
    - Commands:
      - `cd ~`
      - `pwd`
    - Description: Changes to the home directory and prints the current directory.
    - Location: Cell 25

26. **Navigate to Workspace Directory**
    - Commands:
      - `cd ../../workspace/Introduction-to-Shell-Scripting`
      - `pwd`
      - `ls`
    - Description: Navigates to the workspace directory, prints the current directory, and lists its contents.
    - Location: Cell 26

27. **List Files in Parent Directory**
    - Command: `ls ..`
    - Description: Lists files in the parent directory.
    - Location: Cell 27

28. **List Files in Current Directory**
    - Commands:
      - `ls .`
      - `pwd .`
    - Description: Lists files in the current directory and prints its path.
    - Location: Cell 28

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
    - Location: Cell 29

30. **View Shell Script Content**
    - Command: `cat linux.sh`
    - Description: Displays the content of the `linux.sh` file.
    - Location: Cell 30

31. **View Manual for Bash**
    - Command: `man bash`
    - Description: Displays the manual for the Bash shell.
    - Location: Cell 31

32. **Edit Shell Script**
    - Commands:
      - `nano -w linux.sh`
      - `vim linux.sh`
    - Description: Opens the `linux.sh` file in text editors for editing.
    - Location: Cell 32

33. **Change File Permissions**
    - Commands:
      - `chmod +x linux.sh`
      - `chmod u-x linux.sh`
      - `chmod go-wx linux.sh`
      - `chmod g+w linux.sh`
    - Description: Demonstrates changing file permissions for the `linux.sh` file.
    - Location: Cell 33

34. **List Files with Specific Patterns**
    - Commands:
      - `ls /bin/b*`
      - `ls /bin/*r | head -n 20`
    - Description: Lists files in `/bin` matching specific patterns.
    - Location: Cell 34

35. **Display File Metadata**
    - Command: `ls -l linux.sh`
    - Description: Displays detailed metadata for the `linux.sh` file.
    - Location: Cell 35

36. **View File Modification Date**
    - Command: `date -r linux.sh`
    - Description: Displays the last modification date of the `linux.sh` file.
    - Location: Cell 36

37. **Search Files**
    - Command: `find /etc -name '*.txt'`
    - Description: Searches for `.txt` files in the `/etc` directory.
    - Location: Cell 37

38. **View README File Content**
    - Commands:
      - `more README.md`
      - `head README.md`
      - `tail README.md`
    - Description: Displays the content of the `README.md` file.
    - Location: Cell 38

39. **Count Words, Lines, and Characters in README**
    - Commands:
      - `wc README.md`
      - `wc -l README.md`
      - `wc -w README.md`
      - `wc -c README.md`
    - Description: Counts the number of words, lines, and characters in the `README.md` file.
    - Location: Cell 39

40. **Sort and Filter README Content**
    - Commands:
      - `sort README.md | head -n 10`
      - `sort -r README.md | head -n 10`
      - `uniq README.md | head -n 10`
    - Description: Sorts and filters the content of the `README.md` file.
    - Location: Cell 40

41. **Search README for Specific Text**
    - Commands:
      - `grep ch README.md | head -n 10`
      - `grep -i ch README.md | head -n 10`
    - Description: Searches for specific text in the `README.md` file.
    - Location: Cell 41

42. **Cut and Paste File Content**
    - Commands:
      - `cut -c 2-9 README.md | head -n 10`
      - `cut -d ' ' -f2 README.md | head -n 10`
      - `paste first.txt last.txt`
      - `paste -d "," first.txt last.txt`
    - Description: Demonstrates cutting and pasting file content.
    - Location: Cell 42

43. **Remove Temporary Directory**
    - Command: `rm -r copy`
    - Description: Removes the `copy` directory.
    - Location: Cell 43

44. **Display Hostname Information**
    - Commands:
      - `hostname`
      - `hostname -s`
      - `hostname -i`
    - Description: Displays the hostname, short hostname, and IP address of the system.
    - Location: Cell 44

45. **Display Network Configuration**
    - Commands:
      - `ifconfig`
      - `ifconfig eth0`
    - Description: Displays network configuration details for all interfaces or a specific interface (e.g., eth0).
    - Location: Cell 45

46. **Ping a Website**
    - Command: `ping -c 5 www.google.com`
    - Description: Sends 5 ICMP echo requests to www.google.com to check connectivity.
    - Location: Cell 46

47. **Fetch a Webpage Using curl**
    - Command: `curl www.google.com`
    - Description: Fetches the HTML content of www.google.com.
    - Location: Cell 47

48. **Save Webpage Content to a File**
    - Commands:
      - `curl www.google.com -o google.txt`
      - `head -n 10 google.txt`
    - Description: Saves the HTML content of www.google.com to a file named google.txt and displays the first 10 lines.
    - Location: Cell 48

49. **Download a File Using wget**
    - Command: `wget https://www.w3.org/TR/PNG/iso_8859-1.txt`
    - Description: Downloads the file iso_8859-1.txt from the specified URL.
    - Location: Cell 49

50. **Download a File Using curl**
    - Command: `curl -O https://www.w3.org/TR/PNG/iso_8859-1.txt`
    - Description: Downloads the file iso_8859-1.txt from the specified URL using curl.
    - Location: Cell 50

51. **View File Content**
    - Command: `head -n 10 iso_8859-1.txt`
    - Description: Displays the first 10 lines of the file iso_8859-1.txt.
    - Location: Cell 51

52. **Install iproute2 Package**
    - Command: `sudo apt install iproute2`
    - Description: Installs the iproute2 package for advanced network configuration.
    - Location: Cell 52

53. **Display IP Address Information**
    - Command: `ip a`
    - Description: Displays IP address information for all network interfaces.
    - Location: Cell 53

54. **Display IP Address for Specific Interface**
    - Command: `ip addr show eth0`
    - Description: Displays IP address information for the eth0 interface.
    - Location: Cell 54

55. **Create a Tar Archive**
    - Command: `tar -cf introToShell.tar ../../workspaces/Introduction-to-Shell-Scripting`
    - Description: Creates a tar archive of the Introduction-to-Shell-Scripting directory.
    - Location: Cell 55

56. **Create a Compressed Tar Archive**
    - Command: `tar -czf introToShell.tar.gz ../../workspaces/Introduction-to-Shell-Scripting`
    - Description: Creates a compressed tar archive of the Introduction-to-Shell-Scripting directory.
    - Location: Cell 56

57. **List Contents of a Tar Archive**
    - Command: `tar -tf introToShell.tar | head -n 20`
    - Description: Lists the first 20 files in the tar archive.
    - Location: Cell 57

58. **Extract a Tar Archive**
    - Command: `tar -xf introToShell.tar workspaces`
    - Description: Extracts the tar archive into the workspaces directory.
    - Location: Cell 58

59. **Extract a Compressed Tar Archive**
    - Command: `tar -xzf introToShell.tar.gz workspaces`
    - Description: Extracts the compressed tar archive into the workspaces directory.
    - Location: Cell 59

60. **Create a Zip Archive**
    - Command: `zip -r introToShell.zip ../../workspaces/Introduction-to-Shell-Scripting/`
    - Description: Creates a zip archive of the Introduction-to-Shell-Scripting directory.
    - Location: Cell 60

61. **Extract a Zip Archive**
    - Commands:
      - `unzip introToShell.zip`
      - `ls -R`
    - Description: Extracts the zip archive and lists the contents recursively.
    - Location: Cell 61

62. **Clean Up Extracted Files and Archives**
    - Commands:
      - `rm -r workspaces`
      - `rm introToShell.zip`
      - `rm introToShell.tar`
      - `rm introToShell.tar.gz`
    - Description: Removes extracted files and archives to clean up the workspace.
    - Location: Cell 62

## Access the Notebook

[View the Notebook](linux.ipynb)
