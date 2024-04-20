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
#a program to mark the maximum of marks using the list method sort.
#DEVELOPED BY: KISHORE NARAYANAN S R
#REGISTER NUMBER: 212223110023
def max_marks(array):
    array.sort()
    return array[-1]


```

ii)	# To find the maximum marks using the list method max().
```
#a program to find the maximum marks using the list method max().
#DEVELOPED BY: KISHORE NARAYANAN S R
#REGISTER NUMBER: 212223110023

def max_marks(array):
    return max(array)


```

iii) # To find the maximum marks without using builtin functions.
```
#a program to find the maximum marks without using builtin functions.
#DEVELOPED BY: KISHORE NARAYANAN S R
#REGISTER NUMBER: 212223110023

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1
```



## Output:
i)	# To find the maximum of marks using the list method sort.

![Screenshot 2024-04-20 183953](https://github.com/KISHORENARAYANANSR/FindMaximum/assets/148202102/6cc99ed3-ce49-4ea3-8b1c-994ed93de831)


ii)	# To find the maximum marks using the list method max().

![Screenshot 2024-04-20 184005](https://github.com/KISHORENARAYANANSR/FindMaximum/assets/148202102/c031c8aa-850a-4cce-a011-a2a64cc45e7d)


iii) # To find the maximum marks without using builtin functions.

![Screenshot 2024-04-20 184016](https://github.com/KISHORENARAYANANSR/FindMaximum/assets/148202102/c0d16673-5740-4cd3-9a64-7bc074505375)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
