# Do More
* **Make 20 more directories and remove them all.**

> First, I created 20 directories using command **mkdir**

>> mkdir Dir_1, mkdir Dir_2, mkdir Dir_3, mkdir Dir_4, mkdir Dir_5, mkdir Dir_6,  

>> mkdir Dir_7, mkdir Dir_8, mkdir Dir_9, mkdir Dir_10, mkdir Dir_11, mkdir Dir_12, 

>> mkdir Dir_13, mkdir Dir_14, mkdir Dir_15, mkdir Dir_16, mkdir Dir_17, 
 
>> mkdir Dir_18, mkdir Dir_19, mkdir Dir_20,

> Then I used command **rmdir** to remove each file

>> rmdir Dir_1, rmdir Dir_2, rmdir Dir_3, rmdir Dir_4, rmdir Dir_5, rmdir Dir_6,  

>> rmdir Dir_7, rmdir Dir_8, rmdir Dir_9, rmdir Dir_10, rmdir Dir_11, rmdir Dir_12, 

>> rmdir Dir_13, rmdir Dir_14, rmdir Dir_15, rmdir Dir_16, rmdir Dir_17, 
 
>> rmdir Dir_18, rmdir Dir_19, rmdir Dir_20,


* **Make a single path of directories that is 10 deep and remove them one at a time just like I did above.**
> For this exercise I have created single path of directories that is 10 dip 

      mkdir -p First/Second/Third/Fourth/Fifth/Sixth/Seventh/Eighth/Ninth/Tenth

> Than **cd** to the lowest directory

      cd First/Second/Third/Fourth/Fifth/Sixth/Seventh/Eighth/Ninth/Tenth
      
> change directory **cd ..** to the previous one
      
> and start removing directories one by one

##### Step of removing the directories#####

      cd First/Second/Third/Fourth/Fifth/Sixth/Seventh/Eighth/Ninth/Tenth
      
      cd ..
      
      rmdir Tenth
      
      cd ..
      
      rmdir Ninth
      
      cd ..

      rmdir Eighth
      
      cd ..
      
      ls
      
         Seventh
      
      rmdir Seventh

      cd ..
      
      rmdir Sixth
      
      cd ..
      
      rmdir Fifth
      
      cd ..
      
      rmdir Fourth
      
      cd ..
      
      ls
      
            Third
            
      rmdir Third
      
      cd ..
      
      rmdir Second
      
      cd ..
      
      rmdir First
      
* **If you try to remove a directory with contents you will get an error. I'll show you how to remove these in later exercises.**

> No one created and removed directories has no content and I had no problems to remove directories.

# English quastions

**1) Can you remove the tmp directory?**
> I can remove **tmp** directory starting the lowest directory first. But my **tmp** directory has subdirectories and command **rmdir tmp** would not be executed.

**Let's remove the tmp directory.**
> To remove tmp directory I use command:

      rmdir tmp
      
> The output is:

      mdir: tmp/: Directory not empty
      
> To remove I should start the lowest directory or use argument **-p** to remove all directory.
