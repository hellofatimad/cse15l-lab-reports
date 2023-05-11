# Lab Report 3

Four command-line options for `grep`

Citation: https://linuxhint.com/grep_command_linux/ and `man grep` options

File: https://github.com/ucsd-cse15l-s23/docsearch/tree/main

### 1. grep "string" filename -color command

Directories must be in technical!

#### First Example
  
  `grep "divert" ./911report/chapter-1.txt --color`

  * Output:
  
  > ![Image](OutputCmd1.png)

  * Explanation:
  
    * This grep command line finds the string "divert" from the file, `chapter-1.txt`. As a result, it prints out all lines, containing the keyword "divert". Adding the `--color` to the command line would highlight the keywords in which it would be found in the file.


#### Second Example
  
   `grep "databases" ./plos/journal.pbio.0020001.txt --color`
   
   * Output:
   
   > ![Image](OutputCmd1.png)

    
   * Explanation:
   
      * This grep command finds the string "databases" from the file `journal.pbio.0020001.txt`. As a result, it prints out the line with the keyword "databases" and highlighting the word. This is particularly useful because I can easily identify where the keyword is located.
      * 
