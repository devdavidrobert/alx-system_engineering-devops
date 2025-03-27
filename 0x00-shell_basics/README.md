# 0x00. Shell Basics

## Overview
This directory contains tasks and shell scripts created to practice fundamental shell commands and scripting techniques as part of the ALX System Engineering & DevOps curriculum. It serves as an introduction to working with the Linux shell, focusing on basic navigation, file manipulation, and automation through scripting.

## Objectives
- Learn to navigate the filesystem using commands like `cd`, `ls`, `pwd`, etc.
- Understand file and directory manipulation with commands like `cp`, `mv`, `rm`, and `mkdir`.
- Write basic Bash scripts to automate simple tasks.
- Use environment variables and basic I/O redirection.

## Contents
Below is a summary of the scripts in this directory:
- **`0-current_working_directory`**: Prints the absolute path of the current working directory using `pwd`.
- **`1-listit`**: Lists the contents of the current directory using `ls`.
- **`2-bring_me_home`**: Changes the working directory to the user’s home directory using `cd ~`.
- **`3-listfiles`**: Displays directory contents in long format using `ls -l`.
- **`4-listmorefiles`**: Lists all files (including hidden ones) in long format using `ls -la`.
- **`5-listfilesdigitonly`**: Lists files with numeric user and group IDs in long format using `ls -lan`.
- **`6-firstdirectory`**: Creates a directory named `my_first_directory` in `/tmp/` using `mkdir`.
- **`7-movethatfile`**: Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory` using `mv`.
- **`8-firstdelete`**: Deletes the file `betty` from `/tmp/my_first_directory` using `rm`.
- **`9-firstdirdeletion`**: Deletes the directory `my_first_directory` from `/tmp/` using `rmdir`.
- **`10-back`**: Changes the working directory to the previous one using `cd -`.
- **`11-lists`**: Lists all files and directories (including hidden ones) in the current directory, parent directory, and `/boot` directory using `ls -la`.
- **`12-file_type`**: Prints the type of the file `/tmp/iamafile` using `file`.
- **`13-symbolic_link`**: Creates a symbolic link to `/bin/ls` named `__ls__` using `ln -s`.
- **`14-copy_html`**: Copies all `.html` files from the current directory to the parent directory, only if they don’t exist or are newer, using `cp -u`.

## Usage
To run any script:
1. Ensure it has execute permissions:
   ```bash
   chmod +x script_name
