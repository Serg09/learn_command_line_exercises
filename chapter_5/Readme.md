# Do More

* _cd to the joe directory with one command._
cd temp/stuff/things/frank/joe/

* _cd back to temp with one command, but not further above that._
cd ../../../../

* _Find out how to cd to your "home directory" with one command._
cd
pwd /Users/viola_lv/

*	_cd to your Documents directory, then find it with your GUI file browser (Finder, Windows Explorer, etc.)._
cd Documents (used tab to make it faster): 
Finder – Documents (in Favorites)

*	_cd to your Downloads directory, then find it with your file browser._
cd ..     cd Downloads
Finder – Downloads (in Favorites)

*	_Find another directory with your file browser, then cd to it._
Finder – Desktop: cd ..      cd Desktop/

*	_Remember when you put quotes around a directory with spaces in it? You can do that with any command. For example, if you have a directory I Have Fun, then you can do: cd "I Have Fun"_
Got it


# English quastions

**1) Can you cd into the temp directory?**
> Before I would change directory, I would run **pwd** to see were I am now: 
> Output is /Users/viola_lv/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5/, I can **cd** into the tmp directory. Additionaly I can check if there is a tmp directory in chapter_5 directory by running command **ls**

**2) Why don't we go into the temp directory?**
> Lets go. I run command:

      cd tmp/
      
>then:

       pwd
       
> output is /Users/viola_lv/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5/tmp
      
**3) Can you go to the slash temp directory?**
> Yes, I can. I run command:

            cd /tmp
            
> then run:

            pwd
            
> to see working directory.
> The working directory is /tmp and this is tmp directory for the all system and not the one that was created in chapter_5

**4) Can you go to the slash temp slash log directory?**
> No, I can not because there is no such directory **log** exist under the system tmp directory

 
##### <font color="white"> What does the .. argument to cd do?
> The **cd** with dash+double dots will move up one directory.
