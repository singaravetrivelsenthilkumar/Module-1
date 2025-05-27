## Experiment No: 1d – Conditional Statements- Write a python program to compute whether a given year is leap year or not
## AIM  
To write a Python program to check whether a given year is a leap year or not.
## ALGORITHM  
1. Start the program.

2.Prompt the user to input a year.

3.Check if the year is divisible by 4 but not by 100, or divisible by 400.

4.Display whether the year is a leap year or not.
## PROGRAM
```python
# Reg.No-212222220048
# Name- SINGARAVETRIVEL S
# Write your code here
a=int(input())
if(a%100==0):
    if(a%400==0):
        print("Given year {} is a leap year".format(a))
    else:
        print("Given year {} is not a leap year".format(a))
else:
    if(a%4==0):
        print("Given year {} is a leap year".format(a))
    else:
        print("Given year {} is not a leap year".format(a))
```

## OUTPUT
![Screenshot 2025-04-28 134229](https://github.com/user-attachments/assets/c3f404a0-819d-4a08-9dee-3bf719389456)

## RESULT
The program successfully checks and displays whether the given year is a leap year.
