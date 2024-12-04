## Introduction to Shell

In this section, we will take a look at linux shell in detail.

- This command line interface (CLI) will enable you to effectively work on linux laptop/server/virtual machine.

- While the graphical version may see more appealing to the users but can be limited in case of functionality. These is where the Linux command line commonly known as **Linux Shell** shines.

**What is a shell?**

- Linux shell is a program that allows text based interaction between the user and the operating system, this interaction is carried out by typing commands into the interface and receving the response in the same way.

- The Linux shell is a powerful tool with which you can navigate between different locations within the system, however when you login to the shell the very first directory you were take into is your home directory.

## The Home Directory

# Introduction to Shell

A user **michael**'s home directory is created under `/home/michael`, where `/home` is a system-created home directory that contains the home directories for almost all users in the Linux system.

The name of the home directory is, by default, identical to the name of the user. Hence, **michael's** home directory is `/home/michael`.

Remember, the home directory is unique for each user. Another user, called **allen**, will have a different home directory, which by default is created under `/home/allen`.

### Why Do We Need a Home Directory?
The home directory allows users to store their personal data in the form of files and directories.  
Each user in the system gets their own unique home directory with complete access to it (to be able to save, retrieve, and delete data).  
Think of it as a dedicated locker assigned to you in which you can store or retrieve items.  
Other users can't access your files and folders within your home directory (only you can).

**Note**: The representation of the home directory is represented as `~` (tilde symbol).

---

### Command Prompt
You can configure the command prompt to show whatever you want, such as the hostname, date, or time.  
It is currently configured to show the current working directory. The `~` symbol here represents the home directory.

---

### Command and Arguments
To interact with the Linux system using the shell, a user has to type in commands.  
When a command is run, it executes a program to achieve a specific task.

**For example**:  
The `echo` command is used to print a line of text on the screen.  
```bash
$ echo

An **argument** acts as an input to a command.
For example: To print a hello message, type echo hello command.

$ echo hello

There are several commands that can work without an argument too.
For example: Type in the command called uptime. This command is used to print information about how long a system has been running since the last reboot along with other information. This command doesn't need an argument.

$ uptime

A command can also have options that modify its behavior in some predetermined way. The option is sometimes referred to as a switch or a flag.

For example: To print the same word hello but without a trailing newline, use the echo command with the -n flag.

$ echo -n hello



