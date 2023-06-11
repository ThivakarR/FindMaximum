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
Developed by: R.THIVAKAR
RegisterNumber: 212222240109
'''
def max_marks(marks):
    marks.sort()
    return(marks[-1])



```

ii)	# To find the maximum marks using the list method max().
```Python
Developed by: R.THIVAKAR
RegisterNumber: 212222240109
'''
def max_marks(marks):
    large=max(marks)
    return large;

```

iii) # To find the maximum marks without using builtin functions.
```Python
Developed by: R.THIVAKAR
RegisterNumber: 212222240109
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i> max:
            max = i
    return max

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-06-11 171050](https://github.com/ThivakarR/FindMaximum/assets/118707074/38ec57f5-6ecc-4f68-b7a4-e9a4af0e03e7)

![Screenshot 2023-06-11 171111](https://github.com/ThivakarR/FindMaximum/assets/118707074/7c368838-4c1b-4114-aafa-b2f7cfdbf81a)

![Screenshot 2023-06-11 171124](https://github.com/ThivakarR/FindMaximum/assets/118707074/08c759fd-4d9b-4ab2-8c21-e995a04bee50)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
