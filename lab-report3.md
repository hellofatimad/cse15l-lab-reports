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
   
   > ![Image](OutputCmd2.png)

    
   * Explanation:
   
      * This grep command finds the string "databases" from the file `journal.pbio.0020001.txt`. As a result, it prints out the line with the keyword "databases" and highlighting the word. This is particularly useful because I can easily identify where the keyword is located.


### 2. grep –c “string” filename

#### First Example

  `grep -c "divert" ./911report/chapter-1.txt`
  
  * Output:
  

  * Explanation:
  
    * This grep command finds the number of times the keyword "divert" pops up. I find this output particularly interesting because my above example highlighted four "divert" strings within the file, yet this grep command output is 3, instead of 4.


#### Second Example

  `grep -c "databases" ./plos/journal.pbio.0020001.txt`
  
  * Output:
  
  * Explanation:
  
    * This grep command finds the number of times the keyword "databases" popos up in the file. This is useful because I can determine how much the word pops up.


### 3. grep “string” -i filename

#### First Example

  `grep "Divert" -i ./911report/chapter-1.txt`
  
  * Output:
  
  * Explanation:
  
    * This grep command finds the keyword by ignoring the case sensitive aspect of grep. The output is all of the lines containing the keyword. 

#### Second Example 

  `grep "Databases" -i ./plos/journal.pbio.0020001.txt`
  
  * Output:
  
  * Explanation: 
  
    * This grep command outputs the line containing the keyword, while ignoring case sensivity. This is especially helpful because there may be some sentences starting with the keyword, and I would not be able to detect it using regular grep commands.


### 4. grep "string" -n filename

#### First Example

  `grep "divert" -n ./911report/chapter-1.txt`
  
  * Output:
  
  * Explanation:
  
    * This grep command outputs line and line numbers containing the keyword within the file. 

#### Second Example

  `grep "databases" -n ./plos/journal.pbio.0020001.txt`
  
  * Output:


  * Explanation:
  
    * This grep command outputs the line and line number containing the keyword. This is particularly useful if I want to locate the keyword. 
 
