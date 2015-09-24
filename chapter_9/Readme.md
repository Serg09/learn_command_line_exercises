
# Do More
**Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.**

> In chapter_9 directory I have create new **tmp** directory.

> **cd** to the **tmp** directory

> and make a new file "test.txt" using command **touch**

> changed one level up **cd ..**

> run command **rmdir** to remove **tmp** directory and got error **rmdir: tmp: Directory not empty**

> I can't delete this directory because I have no proper permission to delete this file with directory.

# English quastions

**Can you touch blah.txt?**
> I chapter_9 directory I run command **touch blah.txt**. Now if I  **ls** command to check if file is created and get output: **Readme.md, blah.txt, tmp**

**Let's create foo.txt.**

> To create **foo.txt** file I run command touch:

      touch foo.txt
      
**What happens if you touch an existing file?**

> If I touch an existing file I will update time and date stamps of the file
