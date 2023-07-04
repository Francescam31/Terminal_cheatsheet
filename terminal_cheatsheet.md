# Terminal Cheatsheet

### `pwd`
- print working directory

---
### Listing Files

### `ls`
- lists all files and folders in the current directory

### `-l (ls -l)`
- lists extra information on the files in the directory including modification date and file size

### `-a (ls -a)`
- lists hidden files 

---
### Changing Directory 

### `cd folder`
- change directory

### `cd`
- home directory

### `cd - `
- previous working directory

---
### Creating New files/directories

### `mkdir folder_name`
- Create new directory

### `touch file_name.(file extension)`
- creates a new file in the current directory 
- touch folder/file_name.() to create file in child directory

### `mv file new_filename` 
- Rename file

### `mv file_name folder`
- moves a file to to a different directory

---
### Opening files

### `open file.txt`
- opens the file in text editor
- opening a directory will open Finder

### `code file`
- opens VSCode

---
### Removing files/directories

### `rm`
- Removes directory (empty)

### `rm -r`
- Removes directory and contents

### `rm -f`
- 'Force' removes protected files

---
### Misc.

### CTRL + L
- Clears the screen

---
## Git

### `git init`
- initiates a git repository for the current directory
- check .git has been created by using the `ls -a` command

### `git status`
- provides an update on which files have been modified

### `git add (file or .)`
- commands git to track the file or everything in the directory

### `git commit -m "description"`
- Commits changes made to the tracked files 
- requires a description of the change made

### `git log`
- Shows the history of changes made in the repository 
- 'q' to exit

### `git remote add origin (link)`
- `git remote` links the local repository to Github
- `add` indicates creation of a new link
- `origin` is the conventional name for the primary remote

### `git push origin main`
- `git push` uploads from the local repository to Github

### `git pull origin main`
- downloads changes made by another user



