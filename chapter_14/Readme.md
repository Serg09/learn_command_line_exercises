##### *Before doing this rexercises, first I created files blah.txt and development.log in my chapter_12 directory, and foo directory with three files in /tmp directory*

### Can you remove blah.txt?
> To remove **blah.txt** file I would run command:

      rm blah.txt

> Output: there is no more **blah.txt** file in the directory

### Let's get rid of our development log file.
> To get rid of **development.log** file I would run command:

      rm development.log
      
> Output: only Readme.rm file left in the directory. Develpment.rm file was removed.


### Can you remove everything in the slash temp slash foo directory?
> To remove all files in **/tmp/foo/** directory I would run command:

      rm /tmp/foo/*
      
> To check if all files were removed i run command:

      ls /tmp/foo/
      
> Output: there is no more file. Directory is empty

## rm -rf command
> teh **rm -rf** command is dangerous because it can remove all content including file and subdirectories. And because it uses force, write-protected files will be deleted too.

