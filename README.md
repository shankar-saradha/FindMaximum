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
def max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark


```

ii)	# To find the maximum marks using the list method max().
```Pythondef max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![questrion 1](https://user-images.githubusercontent.com/93978702/152678991-d154b91f-f2da-49d6-9531-b0a67ef61d4e.png)
![quwst![question 3 ](https://user-images.githubusercontent.com/93978702/152678996-912bfa64-84e0-405a-9e92-429e5f41b2fe.png)
![quwstion 2](https://user-images.githubusercontent.com/93978702/152679004-865feab1-605a-4174-9190-de4edd676a6e.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
