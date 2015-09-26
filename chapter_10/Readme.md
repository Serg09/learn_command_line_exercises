# Can you copy the foo.txt file to slash temp?  (Create foo.txt first...)
> First Iwould create the file foo.txt

      touch foo.txt
      
>  Now I can copy foo.txt into tmp directory using command:

      cp foo.txt tmp/

> Now I have foo.txt file both chapter_10 and tmp directory

# Can you copy .bash_profile in your home directory to the current directory?
> I would use **ls** command to see what in my home directory:

      ls /Users/viola_vs
      
> In my home directory I have file **#.bash_profile#** 
> Now when I know exactly that file in my home directory and I know exact name of the file I can copy file using command:

      cp \#.bash_profile# workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_10/#.bash_profile#

> Now I have **#.bash_profile#** file in my **chapter_10** directory too.

# What is ROBOCOPY
> Robocopy is a robust file and folder copy. It copy a file only if source and destination are different in time stamps or in file sizes.

> The syntax of robocopy is different too:

      robocopy <source directory> <destination directory> [<file>[ ...]] [<options>]

# Do More
### Use the cp -r command to copy more directories with files in them.
### Copy a file to your home directory or desktop.
> To copy all subdirectories and file included in the copying directory I would use Option **-r**

> Then I would ru command that includes copy option with source and destination:

      cp -r chapter_10 /Users/viola_lv/
      
> In the end of the source directory I put a **/** to make sure that directory is really exist. Otherwise I would get an error

### Find these files in your graphical user interface and open them in a text editor.
> Open Finder, click on Home directory in Favorites and there I can see chpter_10 which I copied using option **-r**
> click on the folder and double click the files files to open it in Text editor. 
