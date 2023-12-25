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
Developed by: RUCHITRA THIYAGARAJ
RegisterNumber: 23000100
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
Developed by: RUCHITRA THIYAGARAJ
RegisterNumber: 23000100
'''
def max_marks(marks):
    marks.sort()
    res=marks[-1]
    return res

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: RUCHITRA THIYAGARAJ
RegisterNumber: 23000100
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if(i>max):
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/RuchitraThiyagaraj/FindMaximum/assets/154776996/af33f0c5-61a7-45bc-87b9-f9d565fb2c7f)
</br>
![image](https://github.com/RuchitraThiyagaraj/FindMaximum/assets/154776996/89db2400-11a0-4014-9699-26470c60c294)
</br>
![image](https://github.com/RuchitraThiyagaraj/FindMaximum/assets/154776996/16c5ee20-93e5-4375-9245-5a115b5f00b1)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
