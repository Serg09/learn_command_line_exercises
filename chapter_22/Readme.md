Do More
---

### Take and list out all the environment variables you've found and then go look up what they are online.

Here is a list and short explanation to some environment variables I found online.

* SHELL: This describes the shell that will be interpreting any commands you type in. 
Usually it si a bash by default.

* TERM_PROGRAM: This specifies the type of terminal is used when running the shell. 
Different can be used for different operating requirements. 

* USER: The current logged in user.

* PWD: The current working directory.

* OLDPWD: The previous working directory. 
This is kept by the shell in case if needed to switch back to previous directory.

* LS_COLORS: This defines color codes that are used to optionally add colored output to the ls command. 

* PATH: A list of directories that the system will check when looking for commands. 
When a user types in a command, the system will check directories in this order for the executable.

* HOME: The current user's home directory.

* HISTFILESIZE: Number of lines of command history stored to a file.

* HISTSIZE: Number of lines of command history allowed in memory.

* HOSTNAME: The network name of the computer at this time.

* SHELLOPTS: Shell options that can be set with the set option.

* SHLVL The number of nested shells. 1 is a login shell. 'w' stands for window, 't' for tab, and 'p' for panel. 


### Can you set the debug environment variable to true?

I would run command:

```export debug=true```

I then run command ```env``` to check if debug is set to true.

### Can you remove the debug environment variable?

I would run command:

```unset debug```

I then run command ```env``` to check if debug is set to false.

### Add your environment variables, and what they do to your Readme.md.

Did some additional research for the environment variables, and here is more useful variables.

* COLORFGBG This is a feature which tells the application what colors the default foreground and background correspond to.

* MAIL: The path to the current user's mailbox.

* BASHOPTS:Ooptions that were used when bash was executed.

* BASH_VERSION: The version of executed bash in human readable form.

* BASH_VERSINFO: The version of bash in machine readable form.

* COLUMNS: The number of columns that are used to draw output on the screen.

* DIRSTACK: The stack of directories that are available with the pushd and popd commands.

* PS1: The primary command prompt definition. This is used to define what your prompt looks like when you start a shell session.

* UID: The UID of the current user.
