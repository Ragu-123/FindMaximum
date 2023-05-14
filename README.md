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
Developed by:RAGUNATH R 
RegisterNumber:212222240081
'''

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by:RAGUNATH R 
RegisterNumber:212222240081 
'''
def max_marks(marks):
    # write your code here
   max1=max(marks)
   return  max1


```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by:RAGUNATH R 
RegisterNumber:212222240081
'''
def max_marks(list1):
    # write your code here
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1=i
    return max1


```

## Output:
i) # To find the maximum of marks using the list method sorts.
![image](https://github.com/Ragu-123/FindMaximum/assets/113915622/d2d9c4c6-dbc6-429e-8261-a57ec073c87a)
ii) # To find the maximum marks using the list method max().
![image](https://github.com/Ragu-123/FindMaximum/assets/113915622/39ab9817-2ffa-4f11-b0d7-fdf37d497baf)
iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/Ragu-123/FindMaximum/assets/113915622/551d0d22-2da8-4599-85a4-fbbc98119036)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
