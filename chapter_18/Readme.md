# Show me the lines in foo.txt that have "ERROR" in them.

> First I would create a **foo.txt** file containing word arror in Upper case and lower case.

> then I would run command:

      grep -w "ERROR" foo.txt

> On the output I would get a line with word **ERROR** all in Upper case. To ignore the word case I would run command:

    grep -w -i "ERROR" foo.txt
    
> On the output I would get all **ERROR** with ignored word case

# Show me the lines in bar.txt that have "davinci" in them.

> I would create a **bar.txt** file wit **"davinci"** in it with different word case.

> Then would run command:

    grep -w "davinci" bar.txt
    
> To find all words **davinci** ignoring word case I would run:

    grep -w -i "davinci" bar.txt
    
# Can you print all the lines in text files that have your first and last name in them?

> To print the lines in *\.txt files with my name I would run 

      grep "Sergey Skumatov" *.txt
      
> The output would give me the result with file names.

      bar.txt:Sergey Skumatov
      foo.txt:Sergey Skumatov
      newfile.txt:Sergey Skumatov
      oldfile.txt:Sergey Skumatov

# -i option

> -i command force grep to ignore word cases.
