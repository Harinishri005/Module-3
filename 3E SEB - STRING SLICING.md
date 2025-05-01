## Exp.No:3e
## SEB - Write a Python program to find sequences of lowercase letters joined with a underscore.

### AIM  
To  write a Python program to find sequences of lowercase letters joined with a underscore.

### ALGORITHM

1.Start the program.

2.Import the re module for regular expressions.

3.Define an input string that contains words or sequences.

4.Define the regular expression pattern:
r'\b[a-z]+_[a-z]+\b'

5.[a-z]+ matches one or more lowercase letters.

6._ matches the underscore character.

7.The second [a-z]+ again matches one or more lowercase letters.

8.\b ensures the match is a complete word.

9.Use re.findall() to extract all matches from the string.

10.Print the matched sequences.

11.End the program.


### PROGRAM
### REG NO:212223090008
### NAME:Harinishri S
```
import re
s=input()
if re.search(r'[a-z]+_+[a-z]',s):
    print("Found a match!")
else:
    print("Not matched!")
```


### OUTPUT

![screeenshotreg](https://github.com/user-attachments/assets/2ea21d95-1919-4173-b77b-685213ae9dad)



### RESULT

The program successfully finds and returns all sequences that consist of lowercase letters joined with a single underscore, ignoring uppercase letters and other patterns.


