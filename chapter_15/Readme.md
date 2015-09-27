### Can you put "This class is fun" into bar.txt?
> To add text into a **bar.txt** file I would run command:

      echo "This class is fun" > bar.txt
      
> this command will create a **bar.txt** file and add a string into a file

### Can you put "Oh so much fun" into foo.txt?
> I would run command that will create a file if it not exist and add a string into a file:

      echo "Oh so much fun" > foo.txt
      
>> The | (pipe) takes command on the left and 'pipes' or merge into the right command.

>> The < will use input from the file on the right and sent it to the program or file on the left.

>> The > will use output from the file on the left and writs it to the file on the right.

>> The >> takes command on the left and appends it on the right.
