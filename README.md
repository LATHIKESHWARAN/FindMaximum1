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
Developed by: LATHIKESHWARAN J
RegisterNumber: 212222230072
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max


```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: LATHIKESHWARAN J
RegisterNumber: 212222230072
'''
def max_marks(marks):
    max_val=max(marks)
    return max_val


```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: LATHIKESHWARAN J
RegisterNumber: 212222230072
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i >max:
            max=i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-11-28 183415](https://github.com/LATHIKESHWARAN/FindMaximum/assets/119393556/e1a41350-f084-41a2-b526-0c9b360bde74)

![Screenshot 2023-11-28 183740](https://github.com/LATHIKESHWARAN/FindMaximum/assets/119393556/e294d46f-781e-422b-b25e-8716d2014138)

![Screenshot 2023-11-28 183806](https://github.com/LATHIKESHWARAN/FindMaximum/assets/119393556/9aad4f20-eb83-4493-a515-47cb3234900b)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
