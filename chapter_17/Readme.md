### Can you show me all the files in slash temp slash foo?
> To show all the files in /tmp/foo/ directory using **find** command, I would do:

      ind /tmp/foo/ -name "*.*" -print
      
> The output shows me all files in that directory: 

>>> /tmp/foo//file.txt

>>> /tmp/foo//log.log

>>> /tmp/foo//ruby.log

>>> /tmp/foo//text.txt

### What log files are in your log directory?
> To find all logs file in log directory I would run:

        find . -name "*.log" -print
        
> The output shows all log files in the directory:

>>> ./log/file_1.log

>>> ./log/file_2.log

>>> ./log/file_3.log

>>> ./log/file_4.log

### Run find in the class directory, pipe the output to pbcopy and create a gist with the content.  Paste the Gist URL as a comment on this story.
> To find all files in class directory I would **cd** to the class directory and run command:

      ind . -name "*.*" -print > pbcopy
      
> On the output I would get file **pbcopy** with a list of all founded files in the class directory

> then I would create a Gist link with the output content and add link as a comment in the Pivotal
