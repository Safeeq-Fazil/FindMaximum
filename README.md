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
Developed by: Safeeq Fazil.A
RegisterNumber: 212222240086
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Safeeq Fazil.A
RegisterNumber: 212222240086
'''
def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Safeeq Fazil.A
RegisterNumber: 212222240086
'''
def max_marks(list1):
    max= list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        


```


## Output:

## find the maximum of marks using the list method sort:
![exp 3a 1](https://github.com/Safeeq-Fazil/FindMaximum/assets/118680361/27b0e532-fb0e-4405-8658-b09aa70681a3)

## find the maximum marks using the list method max():
![3a 2](https://github.com/Safeeq-Fazil/FindMaximum/assets/118680361/e9de80be-a4f2-4e2b-a778-77a0335a1374)

## find the maximum marks without using builtin functions:
![3a 3](https://github.com/Safeeq-Fazil/FindMaximum/assets/118680361/7e498bc0-fe4d-47c2-a311-11a755e01daa)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
