# Do More

Used ```man``` command to go through command we have learned (man mkdir, man cd, etc)

# "English" questions

> 1. What option to ls tells it to output file size in human readable form?

I would run 
  
```man ls```

to find a command I need to display a file size.

In manual I find command 

```ls --lh```

The output shows me a list with description of files including the size of files in bytes, kilobytes, megabytes, etc.

> 2. Is there a case insensitive option to grep?

mFirst I would run

```man grep```
 
to find a right option which makes command not case sensitive. The option is ``` -i```

```grep -i "Text" <file.name>```

> 3. What does the -r and -f options to rm do exactly?

I would run ```man rm``` to see for the options

The -r option is equivalent -R option and attempts to remove the file hierarchy rooted in each file argument.

The -f options attempt to remove files with any type of permission without confirmation.


> 4. What does the ifconfig command do?

```ifconfig``` command is a system utility for network interface configurations.
