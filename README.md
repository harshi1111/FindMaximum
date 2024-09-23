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
Developed By : HARSHITHA V
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
i) ![image](https://github.com/user-attachments/assets/cbde4072-9b88-4b85-8ac8-2a424fce07e3)

ii) ![image](https://github.com/user-attachments/assets/7d931648-e820-4fde-a3bc-4eb64f24576e)

iii) ![image](https://github.com/user-attachments/assets/c732f4ba-5a20-4268-a633-39847793163c)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
