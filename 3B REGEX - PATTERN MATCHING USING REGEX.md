# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.
3. Accept a string `str1` from the user.
5. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
6. Use the `re.match()` function to check if the string `str1` matches the pattern.  
7. If a match is found, print `"Found a match!"`.  
8. If no match is found, print `"Not matched!"`.  
9. Terminate the program.

---

### PROGRAM
### REG NO:212223090008
### NAME:Harinishri S

```
import re
def text_match(text):
    patterns='^ab*$'
    if re.search(patterns,  text):
        return 'Found a match!'
    else:
        return('Not matched!')
str=input()
print(text_match(str))
```

### OUTPUT

![screeenshotreg](https://github.com/user-attachments/assets/71f65fa4-dcfe-423c-bb72-9270792cc729)


### RESULT
The string matches if it starts with 'a' and is followed only by zero or more 'b' characters, with no other characters allowed.









