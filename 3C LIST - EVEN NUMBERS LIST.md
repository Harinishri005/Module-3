# Exp.No:3c
## LIST - Write a python program to swap the value in the list with the next value if next value is divisible by 5.

### AIM  
To write a python program to swap the value in the list with the next value if next value is divisible by 5.



### ALGORITHM

1.Start the program.

2.Define a list with integer elements.

3.Initialize a counter i = 0.

4.Loop through the list using while i < len(list) - 1:

5.Check if list[i + 1] is divisible by 5 using list[i + 1] % 5 == 0.

6.If true:Swap list[i] and list[i + 1].

7.Increment i by 2 to skip the next index.

8.Else:Increment i by 1.

9.Return or print the modified list.

10.End the program.


### PROGRAM
### REG NO:212223090008
### NAME:Harinishri S
```
L=eval(input())
x=0
l=len(L)
while x<l-1:
    if L[x]%5==0:
        temp=L[x]
        L[x]=L[x+1]
        L[x+1]=temp
        x=x+2
    else:
        x+=1
print(L)
```     

### OUTPUT

![screenshot3b](https://github.com/user-attachments/assets/b23f7c27-d1cd-4595-92ba-8aaafc413e35)

### RESULT
The program successfully swaps elements with the next one when the next value is divisible by 5.
