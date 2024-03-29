# BASH Cheat Sheet

### **`ls`**

* Usage: `ls [flags] [directory name...]`
* What it does: Lists all files and directories in the directory
* Useful flags:
  * `-a`: Lists ALL files
---
### **`pwd`**

* Usage:
* What it does:
* Useful flags:
---             
### **`cd`**

* Usage: `cd [directory name]`
* What it does: Changes location
* Tips and Tricks: 
  * `cd -` go back one
  * `cd ..`  go up one level
  * `cd ~` go home        
---
### **`mkdir`**

* Usage: `mkdir [flag] [directory name...]`
* What it does: Makes a directory or directories
* Useful flags:
  * `-p`: Makes parent directories given a path
---
### **`touch`**

* Usage: `touch [file name...]`
* What it does: Makes a file or files
---
### **`cp`**

* Usage: `cp [file name...] location`
* What it does: Copies a file
* Useful flags:
  * `-r`: Copies a directory
---
### **`rm`**

* Usage: `rm [flag] [file name... or directory name...]`
* What it does: Removes files or directories
* Useful flags: 
  * `-rf`: Removes directories
---
### **`mv`**

* Usage: `mv [file...] location`
* What it does:
* Useful flags:
  * `mv ../filename` move a file from the level above
  * `mv .` move to the current dir
  * `mv file1.md file2.md location` move multiple files
  * `mv file [new file name]` rename file
---
### **`git commands`**

* `git config --global user.name`
* `git config --global user.email`
* `git init` creates a .git file
* `git status`
* `git add`
* `git commit -m "[message]"`
* `git push -u origin master`
  