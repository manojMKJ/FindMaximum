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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Balamurugan p
RegisterNumber: 22008625
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return larg
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:Balamurugan p 
RegisterNumber: 22008625
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Balamurugan :P
RegisterNumber: 22008625
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
             max=i
    return max



```
## Output:
![B1](https://github.com/manojMKJ/FindMaximum/assets/120717614/e3e8d09b-ecfd-4dab-99c0-59571163a290)
![B2](https://github.com/manojMKJ/FindMaximum/assets/120717614/22046420-c02f-4a06-9ea3-d60edbffe436)
![B3](https://github.com/manojMKJ/FindMaximum/assets/120717614/f763b43c-57b8-4332-8b16-fbba5cce0cb4)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
