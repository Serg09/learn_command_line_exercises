# English quastions

**What the pushd and popd commands do?**
> **pushd** command saves current directory in memory and moves to the other directories, and when needed to return to saved directory, use command **popd** to return to saved directory.

# Do More

> As I already create the tmp directory tree I will use this directories for the exercise.


    pushd tmp/stuff/things/frank/joe/alex/john/
    
> Output: ~/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank/joe/alex/john ~/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_8

    pwd
    
> Output: /Users/viola_lv/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank/joe/alex/john

    popd
    
> Output: ~/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_8

    pwd
    
> Output: /Users/viola_lv/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_8

    pushd tmp/stuff/things/frank
    
> Output: ~/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank ~/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_8

    pwd
    
> Output: /Users/viola_lv/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_8/tmp/stuff/things/frank

    popd
    
> Output: ~/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_8

    pwd

> Output: /Users/viola_lv/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_8
