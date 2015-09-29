# Do More

* _cd to the joe directory with one command._

> cd temp/stuff/things/frank/joe/

* _cd back to temp with one command, but not further above that._

> cd ../../../../

* _Find out how to cd to your "home directory" with one command._

> cd ~viola_lv/

*	_cd to your Documents directory, then find it with your GUI file browser (Finder, Windows Explorer, etc.)._

> cd ~/Documents/ (used tab to make it faster): 

> open Finder – click on Documents (in Favorites)

*	_cd to your Downloads directory, then find it with your file browser._

> cd ~/Downloads/

> open Finder – click on Downloads (in Favorites)

*	_Find another directory with your file browser, then cd to it._

> open Finder – in Favorites click on Desktop:

> cd ~/Desktop/



# English quastions

**1) Can you cd into the temp directory?**
> Before I would change directory, I would run **pwd** to see were I am now: 

> The output is /Users/viola_lv/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5/, 

> Then I would create tmp directory using command:

      mkdir tmp/
      
> Now I can **cd** into the tmp directory. 

      cd tmp/
      

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
> To go to log directory I would create log directory

      mkdir /tmp/log/

> Now I would change **cd** to the /tmp/log directory:

      cd /tmp/log
      
## "How to cd to your home directory": cd or cd ~
> To change to my home directory I would run:

      cd ~viola_lv/

 
##### <font color="blue"> What does the .. argument to cd do?
> The **cd** with dash+double dots will move up one directory.
