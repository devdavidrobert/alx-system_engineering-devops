# 0x02. Shell Redirection

## Overview
This directory contains tasks and shell scripts focused on shell I/O redirection and piping, as part of the ALX System Engineering & DevOps curriculum. It teaches how to manipulate input and output streams in the shell, a critical skill for automating tasks and processing data in Linux.

## Objectives
- Learn to redirect standard input, output, and error using `>`, `>>`, `<`, and `2>`.
- Understand piping (`|`) to chain commands.
- Use commands like `tee`, `head`, `tail`, `wc`, and `sort` with redirection.
- Write scripts that manipulate input and output streams.

## Contents
This directory likely includes scripts such as:
- **`0-hello_world`**: Prints "Hello, World" to stdout using `echo`.
- **`1-confused_smiley`**: Prints a confused smiley `"(Ôo)'` using `echo` with proper quoting.
- **`2-hellofile`**: Displays the content of `/etc/passwd` using `cat`.
- **`3-twofiles`**: Displays the content of two files, like `/etc/passwd` and `/etc/hosts`, using `cat`.
- **`4-lastlines`**: Displays the last 10 lines of a file using `tail -n 10`.
- **`5-firstlines`**: Displays the first 10 lines of a file using `head -n 10`.
- **`6-third_line`**: Displays the third line of a file using `head -n 3 | tail -n 1`.
- **`7-file`**: Creates a file with a specific name containing text, using `echo` and redirection.
- **`8-cwd_state`**: Writes the output of `ls -la` to a file using `ls -la > file`.
- **`9-duplicate_last_line`**: Duplicates the last line of a file using `tail -n 1 >> file`.
- **`10-no_more_js`**: Deletes all `.js` files in the current directory using `find . -type f -name "*.js" -delete`.
- **`11-directories`**: Counts the number of directories using `find . -type d | wc -l`.
- **`12-newest_files`**: Lists the 10 newest files in the current directory using `ls -lt | head -n 10`.
- **`13-unique`**: Prints unique words from a file using `sort | uniq`.

## Usage
To run any script:
1. Navigate to the directory:
   ```bash
   cd 0x02-shell_redirection
   ```
2. Ensure the script has execute permissions:
   ```bash
   chmod +x script_name
   ```
3. Execute it:
   ```bash
   ./script_name
   ```

## Notes
- Scripts assume a Linux environment (e.g., Ubuntu).
- Some scripts may create or modify files in the current directory as part of redirection tasks. For example, `8-cwd_state` will create a file in the current directory.
- Be mindful of overwriting files when using `>` (use `>>` to append instead). For instance, `>` will overwrite a file, while `>>` will append to it.
- Some scripts may require a test file to exist. For example, for `4-lastlines` or `6-third_line`, you can create a sample file:
  ```bash
  echo -e "line1\nline2\nline3\nline4" > testfile
  ```

## Author
David Robert - ALX Africa Software Engineering Student
```

---

### `0x03-shell_variable_expansion/README.md`
- **Pasting**: Open a text editor or your GitHub repository, navigate to the appropriate directory (e.g., `0x01-shell_permissions`), create a new `README.md` file, and paste the content (`Ctrl+V` or `Cmd+V`).
- **Saving**: Save each file as `README.md` in its respective directory.

These READMEs are designed to be comprehensive and user-friendly, providing clear documentation for each directory in the context of the ALX curriculum. Let me know if you need further adjustments!
