# Describe what **ls -lR** does?
> The command:

      ls -l  
      
> shows directory or file with it size and modified date and time, file or directory name and owner of file (who own permission for file or directory).

> Command:

      ls -R 
      
> List all tree with all subfolders.

> The command 

      ls -lR
      
> list the file names with it size and modification date, and file or directory name and owner of file (who own permission for file or directory) for the each directory in the tree.

> The command **ls -lR** could have very long list, especially if there is a lot of directories and file in each directory


# English quastions

**1) What's in the tmp directory?**
> To see what in the tmp directory I would run command:

      ls
      
> The output is: *stuff*

**2) Can you show me what files are in that directory?**
> To show what files are in the tmp directory I would run:

      ls (or ls -l for the full information about files)
      
> The output shows me one file per line and in my tmp directory it shows 0 files.


**3) What files are in your home directory?**
> I would run command

            ls /Users/viola_vs
            
> To see all files including hidden files I would run:

            ls -a /Users/viola_vs
            
> Or
>
> To see files in my home directory, first I would **cd** into the home directory _/Users/viola_lv_
> Then run command:

            ls
            
> The output shows three files in the home directory _#.bash_profile#, ~$id_rsa.pub, ~$_rsa.pub.pub_
> To list all files including hidden files I would rin:

            ls -a
            
> In the output list I got #.bash_profile#, .CFUserTextEncoding, .DS_Store, .bash_history, .bash_profile, .bash_profile copy.txt
.bash_profile.swp, .bashrc, .gemrc, .gitconfig, .gitignore_global, .irb-history, .mkshrc, .netrc, .profile, .viminfo,
.zlogin, .zshrc, ~$_rsa.pub.pub, ~$id_rsa.pub


**4) What's in slash temp?**
> /tmp is a system temporary directory

> To see all files including hidden files in this directory I would run:

            ls -a /tmp
            
> The output is:

.s.PGSQL.5432
.s.PGSQL.5432.lock
KSOutOfProcessFetcher.501.HVXI9pQwBk_bgiVJaTNhiQNhqxc=
com.apple.launchd.0c5CyNEkyL
com.apple.launchd.gG5J79pn1C
mysql.sock
