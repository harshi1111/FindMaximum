# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:
```
Developed by : HARSHITHA V
Register No : 212223230074 
```
i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max

```



## Output:
i) ![2024-09-23 09 46 25](https://github.com/user-attachments/assets/7f6a5005-e9d0-4ddb-8e58-c46f8a4e9118)
ii) ![image](https://github.com/user-attachments/assets/f010bd95-3ad0-42a4-9e4e-f91ae3bf28ec)
iii) ![image](https://github.com/user-attachments/assets/9e413e98-911b-472a-a76e-1fc6f8653fdf)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
