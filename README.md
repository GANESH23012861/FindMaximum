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
Developed by: selvaganesh r.
RegisterNumber: 23012861
'''
def max_marks(marks):
    a=marks.sort()
    d=marks[-1]
    return d




```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: selvaganesh
RegisterNumber: 23012861
'''
def max_marks(marks):
    a=marks.sort()
    d=max(marks)
    return d


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: selvaganesh.
RegisterNumber: 23012861
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
        
        


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
## output 1 :
![Screenshot 2023-12-21 185623](https://github.com/GANESH23012861/FindMaximum/assets/147139861/2a3b06f8-cb4c-475d-9442-d2d0f4097904)

## output 2 :
![Screenshot 2023-12-21 185941](https://github.com/GANESH23012861/FindMaximum/assets/147139861/f7c2d2a9-1195-43a6-9934-cd4a557a7b8d)

## output 3 :
![Screenshot 2023-12-21 185958](https://github.com/GANESH23012861/FindMaximum/assets/147139861/7d241d2e-d628-4e62-b151-c8d343759d93)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
