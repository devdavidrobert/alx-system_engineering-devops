| **Script** | **Description** |
| -------- | -------- |
| 0-alias | The code alias ls="rm *" creates an alias that redefines the ls command to execute rm *, which forcefully deletes all files in the current directory when the ls command is used. Caution is advised when using this alias, as it can result in unintended data loss. |
| 1-hello_you | The code echo "hello $USER" is a simple shell command used to display a greeting message. It dynamically inserts the currently logged-in user's name, obtained from the $USER environment variable, into the message. When executed, it prints a personalized greeting such as "hello username" to the terminal. |
| 2-path | The code export PATH=$PATH:/action is used to extend the system's PATH environment variable by adding the directory "/action." This allows the shell to search for and execute programs located in the "/action" directory without specifying the full path, simplifying the execution of commands. |
