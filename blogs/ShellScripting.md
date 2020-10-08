<h1 align="center">Shell Scripting</h1>

![img](img/ShellScripting_Pranjal.jpeg)

### Introduction to Shell scripting

The process of writing the scripts so as to automate the tasks is called **Shell Scripting**. Scripts are executed as they have been written in the terminal itself. It is a very powerful and fun method for automating your tasks.
It can be said that it is the process of establishing connection to the system by writing scripts.

### Getting Started

Now, let's get started towards a very fun journey of shell scripting.

Make a new file and name it as **hello.sh**. You can name your file anything you want but the extension must be **.sh** for the script to be executed.
Write the following program in your file and save it. 
**Our very first program**
```
#!/bin/sh

echo "Your name: "
read name
echo "Hey, $name"
```
Here, **echo** is used for displaying the message on the command line. The **read** command is used to take and store the input given by the user. And, the **$name** is used for printing the value given by the user.
**#!/bin/sh** must always be specified on the first for the system to know that this script must be executed in system shell.

For running the script, go to your command line and execute the following command -- **./hello.sh**. The following output will be generated - 
```
$ ./hello.sh
Your name: 
Pranjal
Hey, Pranjal
```

There are more commands that can be executed like **date** command. 
``` $ date ```

Output --
```
Wed  7 Oct 20:50:31 IST 2020
```

**pwd** - It returns the current directory in which you are currently in.

### Variables

There are three main types of variables −

- **Local Variables** − It is a variable that is present only within the current instance of the shell.

- **Environment Variables** − It is available to any child process of the shell. Some programs need environment variables in order to function correctly.

- **Shell Variables** − It is a special variable that is set by the shell and is required by the shell in order to function correctly. Some of these variables are environment variables whereas others are local variables.

**Variable name** -- It can contain only letters (a to z or A to Z), numbers ( 0 to 9) or the underscore character.
By convention, the names of the variables will be in UPPERCASE. Also, you cannot use **!, *, -** in your variable name as they have other meaning in shell scripting.

For example, **Valid Variable names**
- _NAME
- VAR_1
- VAR_2

**Invlaid Variable names**
- VAR1-VAR2
- -VAR
- VAR_1!

**Declaring Variable** -- The common format for declaring the variable is ```variable_name = variable_value```.
For example, ```NAME = "StatusNeo"

We can also make a variable Read-only by **readonly** command. 
For example, 
```
#!/bin/sh

NAME="StatusNeo"
readonly NAME
```

### Special Variables

Listed below are some special variables and their usage.

| Variable | Description |
| :-- | :-- |
| $0 | It returns the filename of the current script |
| $n | Here n is any integer that corresponds to the argument number used in the script. |
| $# | It returns the total number of arguments in the script. |
| $$ | It returns the process ID of the current shell |
| $! | It returns the process number of the last command used. |
| $? | It returns the exit status of the last command executed. |



