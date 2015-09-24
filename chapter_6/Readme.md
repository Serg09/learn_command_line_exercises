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
> First, I would **cd** into the /tmp directory
> In tmp directory I would run command: 

            ls -la
            
> to list full information about all files including hidden files.
> The output for seven files looks like this:

            total 8
            drwxrwxrwt  7 root      wheel  238 Sep 23 23:54 .
            drwxr-xr-x@ 6 root      wheel  204 Apr 14 14:11 ..
            srwxrwxrwx  1 viola_lv  wheel    0 Sep 23 23:13 .s.PGSQL.5432
            -rw-------  1 viola_lv  wheel   49 Sep 23 23:13 .s.PGSQL.5432.lock
            drwx------  3 viola_lv  wheel  102 Sep 23 23:12 com.apple.launchd.hpCVZNC6Vh
            drwx------  3 viola_lv  wheel  102 Sep 23 23:12 com.apple.launchd.uJA8b4QxVE
            srwxrwxrwx  1 viola_lv  wheel    0 Sep 23 23:13 mysql.sock
