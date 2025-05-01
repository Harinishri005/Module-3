# Exp.No:3a
## STRING - FIND AND REPLACE

### AIM  
To Write a python function "convert" to accept a string and converts the uppercase character into lowercase character, lowercase character into uppercase  character and also replace the special characters with "bb"


### ALGORITHM

1.Start

2.Define a function named convert that accepts one parameter: a string s.

3.Initialize an empty result string.

4.Loop through each character ch in the string

5.If ch is an uppercase letter → convert it to lowercase and add to result.

6.Else if ch is a lowercase letter → convert it to uppercase and add to result.

7.Else (i.e., special character or symbol) → append "bb" to the result.

8.After the loop ends, return the modified result string.

### PROGRAM
### REG NO:212223090008
### NAME:Harinishri S
```
def convert(s):
    r=""
    for x in s:
        if x.isupper():    
            r+=x.lower()
        elif x.islower():
            r+=x.upper()
        else:
            r+="bb"
    print(r)
s=input()
```
### OUTPUT
![Screenshotmod3](https://github.com/user-attachments/assets/de28af2f-d026-42e7-aab8-23336266d39e)

### RESULT
The function processes each character of the input string: letters are case-inverted, while special characters (like .) are replaced with "bb".






