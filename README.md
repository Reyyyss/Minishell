# Minishell

🐚 Minishell


Minishell is a simple Unix shell built in C as part of the 42
The goal of the project is to recreate the basic behavior of Bash, giving you a deeper understanding of how a real shell works under the hood — from parsing input to managing processes and file descriptors.

🚀 Features


Command parsing with quotes and special characters

Pipes (|) and redirections (>, <, >>, <<)

Environment variable expansion ($VAR)

Signal handling (Ctrl+C, Ctrl+D, Ctrl+\)


Built-in commands:
echo

cd

pwd

export

unset

env

exit

Executes external programs via execve

Proper error handling and exit codes


⚙️ How It Works


Minishell works by:

Reading a command line input from the user.

Parsing it and check syntax errors.

Handling built-ins internally or launching external binaries.

Managing pipes, redirections, and environment variables.

Waiting for child processes and returning the correct exit status.
