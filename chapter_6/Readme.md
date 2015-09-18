In chapter_6 directory with created subdirectories I used command: ls –lR
Got list with full path to each directory with list of directories and files in each directory, including modification date and time (–l). Information given recursively to each new subdirectory (-R).

What's in the tmp directory? 
Tmp is a temporary directory for temporary folders and files
Can you show me what files are in that directory?
Cd tmp
Ls
stuff
What files are in your home directory?
Cd
Ls
#.bash_profile#  Library          RubymineProjects ~$_rsa.pub.pub
Applications     Movies           id_rsa           ~$id_rsa.pub
Desktop          Music            id_rsa.pub
Documents        Pictures         myapp
Downloads        Public           workspace
What's in slash temp?
	When do ls tmp in chapter_6 directory I get list of files and directories under tmp directory.
When do ls /tmp I am getting list of file of tmp directory in my “home directory”

This is what I have there:
KSOutOfProcessFetcher.501.I5ci1K_TwCwqo1sKvc0siaBbJTw=
com.apple.launchd.53d8aW3bNF
com.apple.launchd.thxzCb9iwI
mysql.sock
textmate-501.sock

to list my home directoryI used command: ls ~

Result:
#.bash_profile#  Library          RubymineProjects ~$_rsa.pub.pub
Applications     Movies           id_rsa           ~$id_rsa.pub
Desktop          Music            id_rsa.pub
Documents        Pictures         myapp
Downloads        Public           workspace

