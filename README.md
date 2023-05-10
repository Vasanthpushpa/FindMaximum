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

i)	# To find the maximum of marks using the list method sort.
```Python
Developed by: VASANTH P
RegisterNumber: 212222240113
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
Developed by: VASANTH P
RegisterNumber: 212222240113
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
Developed by: VASANTH P
RegisterNumber: 212222240113
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max=i
    return max

```
## Sample Input and Output
![image](https://github.com/Vasanthpushpa/FindMaximum/assets/119291100/96760f3e-a04a-41e6-90d0-f67b07272304)
![image](https://github.com/Vasanthpushpa/FindMaximum/assets/119291100/4a9e8a89-4f8a-4d72-87a6-77bbb2c49c8d)

## Output:
![image](https://github.com/Vasanthpushpa/FindMaximum/assets/119291100/40d9f641-5ba2-49ed-a392-d2a3dee5e8a2)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
