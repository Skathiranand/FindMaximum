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
Developed by: S.kathiranand
RegisterNumber: 23013711
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by:Kathir anand S
RegisterNumber:23013711 
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by:Kathir anand S 
RegisterNumber:23013711 
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input 
### (i)
![Screenshot from 2023-12-20 16-12-57](https://github.com/Skathiranand/FindMaximum/assets/147141136/c3bca55b-5d65-4a1c-8f29-a034698b74c1)

### (ii)
![Screenshot from 2023-12-20 16-14-16](https://github.com/Skathiranand/FindMaximum/assets/147141136/98fdf4e6-204e-41c9-9680-7b1c2bf8dd48)

### (iii)
![Screenshot from 2023-12-20 16-14-31](https://github.com/Skathiranand/FindMaximum/assets/147141136/00cae9ca-7edd-408b-9d19-ce2f7d393aeb)

## Output:
### (i)
![Screenshot from 2023-12-20 16-16-44](https://github.com/Skathiranand/FindMaximum/assets/147141136/c1d49ba5-0eb8-47cf-bf53-54495961264e)

### (ii
![Screenshot from 2023-12-20 16-17-23](https://github.com/Skathiranand/FindMaximum/assets/147141136/23d2fc45-ffab-4065-9743-cb13362f4501)

### (iii)
![Screenshot from 2023-12-20 16-17-45](https://github.com/Skathiranand/FindMaximum/assets/147141136/253a9201-89cb-44e0-9675-89d1c0d923a0)

## Result:

Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
