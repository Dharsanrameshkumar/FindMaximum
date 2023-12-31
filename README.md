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

Program to mark the maximum of marks using the list method sort
Developed by:dharsan 
RegisterNumber:212223100003

def max_marks(marks):
    list_1=sorted(marks)
    maxi=list_1[-1]
    return maxi
    

```

ii)	# To find the maximum marks using the list method max().
```

Program to find the maximum marks using the list method max().
Developed by: dharsan
RegisterNumber:212223100003

def max_marks(marks):
    list_1=max(marks)
    return list_1
    

```

iii) # To find the maximum marks without using builtin functions.
```

Program to the maximum marks without using builtin functions.
Developed by:dharsan
RegisterNumber:212223100003 

def max_marks(marks):
    maxi=marks[0]
    for mark in marks[1:]:
       if mark>maxi:
           maxi=mark
    return maxi
    

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![Alt text](<Screenshot (43).png>)
![Alt text](<Screenshot (44).png>)

## Output:
![Alt text](<Screenshot (71).png>)
![Alt text](<Screenshot (72).png>)
![Alt text](<Screenshot (73).png>)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.