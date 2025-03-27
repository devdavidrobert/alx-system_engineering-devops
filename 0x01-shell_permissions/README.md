# 0x01. Shell Permissions

## Overview
This directory contains tasks and shell scripts focused on understanding and managing file permissions in a Linux environment, as part of the ALX System Engineering & DevOps curriculum. It introduces key concepts of user management, file ownership, and permission settings, which are essential for system administration and security.

## Objectives
- Learn to view and interpret file permissions using `ls -l`.
- Modify file permissions using `chmod` (both symbolic and numeric methods).
- Change file ownership with `chown` and group ownership with `chgrp`.
- Understand special permissions like `setuid`, `setgid`, and the sticky bit.
- Create scripts to automate permission-related tasks.

## Contents
This directory likely includes scripts such as:
- **`0-iam_betty`**: Switches the current user to `betty` using `su`.
- **`1-who_am_i`**: Prints the effective username of the current user using `whoami`.
- **`2-groups`**: Prints all groups the current user is part of using `groups`.
- **`3-new_owner`**: Changes the owner of a file to another user using `chown`.
- **`4-empty`**: Creates an empty file using `touch`.
- **`5-execute`**: Adds execute permission to a file for the owner using `chmod u+x`.
- **`6-multiple_permissions`**: Sets specific permissions (e.g., `rwxr-x-w-`) on a file using `chmod`.
- **`7-everybody`**: Adds execute permission for all users on a file using `chmod a+x`.
- **`8-James_Bond`**: Sets permissions to `007` (no permissions for owner/group, full permissions for others) using `chmod 007`.
- **`9-John_Doe`**: Sets permissions to `753` (rwxr-x-wx) on a file using `chmod 753`.
- **`10-mirror_permissions`**: Mirrors the permissions of one file to another using `chmod --reference`.
- **`11-directories_permissions`**: Adds execute permissions to all subdirectories using `chmod -R a+X`.
- **`12-directory_permissions`**: Creates a directory with specific permissions (e.g., `751`) using `mkdir -m 751`.
- **`13-change_group`**: Changes the group ownership of a file using `chgrp`.

## Usage
To run any script:
1. Navigate to the directory:
   ```bash
   cd 0x01-shell_permissions
