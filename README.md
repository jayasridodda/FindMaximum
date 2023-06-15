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
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Jayasri Dodda
RegisterNumber: 212222240028
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]

```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: JAYASRI DODDA
RegisterNumber: 212222240028
'''
def max_marks(marks):
    maxi=max(marks)
    return maxi

```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: JAYASRI DODDA
RegisterNumber: 212222240028
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max = i
    return max
```

## Output:
i)	# To find the maximum of marks using the list method sort.
![Screenshot (41)](https://github.com/jayasridodda/FindMaximum/assets/123259278/5709e110-2560-4315-88d8-85d88cfa1fa6)
ii)	# To find the maximum marks using the list method max().
![Screenshot (42)](https://github.com/jayasridodda/FindMaximum/assets/123259278/ece85640-6d9f-4852-be2a-e627b5fbf100)
iii) # To find the maximum marks without using builtin functions.
![Screenshot (43)](https://github.com/jayasridodda/FindMaximum/assets/123259278/7f0b9e3b-c62b-4e92-96f6-5a300ddec373)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
