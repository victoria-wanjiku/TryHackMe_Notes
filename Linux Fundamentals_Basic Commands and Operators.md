## 📌 Overview

Today I learned the basics of Linux commands and operators while working through TryHackMe labs. These commands are essential for navigating the system, managing files, and performing efficient command-line operations, especially in cybersecurity tasks.

---

## 💻 Basic Linux Commands

### 1. `whoami`
- Displays the current logged-in user.
- Useful for checking privileges.

### 2. `pwd (Print Working Directory)`
Shows the current directory path.

### 3. `ls`
Lists files and directories in the current location.

### 4. `cd`
Used to navigate between directories.

### 5. `cat`
Displays the contents of a file.

### 6. `echo`
Prints text to the terminal or writes into a file.

### 7. `grep`
Searches for specific text within files.
Very useful in log analysis.
grep  "keyword" file.txt

### 8. `find`
Used to locate files and directories.
find  -name file.txt

---
## 🔗 Linux Operators
### 1. &
Runs a command in the background.
command &
### 2. &&
Runs the next command only if the previous one succeeds.
command1 && command2
### 3. > (Overwrite)
Redirects output to a file (replaces existing content).
echo "Hello" > file.txt
### 4. >> (Append)
Adds output to the end of a file without deleting existing content.
echo "Hello" >> file.txt

### 🔐 Key Takeaways
Linux commands are essential for system navigation and file management.
grep and find are powerful tools for searching and reconnaissance.
Operators help chain commands and manage output efficiently.

### 🚀 Conclusion

This session helped me build a strong foundation in Linux command-line usage. I am now more comfortable navigating the terminal and using commands to interact with the system, which is crucial for my journey in cybersecurity and penetration testing.

![Linux Output](../Images/linux_basics.png)
