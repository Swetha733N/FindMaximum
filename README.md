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

	 To find the maximum of marks using the list method sort.
   
```
Program to mark the maximum of marks using the list method sort
Developed by: SWETHA N
RegisterNumber: 212222110050
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large
```

	To find the maximum marks using the list method max().
  
```
Program to find the maximum marks using the list method max().
Developed by: SWETHA N
RegisterNumber: 212222110050
def max_marks(marks):
    # write your code here
    large=max(marks)
    return large
```

  To find the maximum marks without using builtin functions.
  
```
Program to the maximum marks without using builtin functions.
Developed by: SWETHA N
RegisterNumber: 212222110050
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```

## Output:
 To find the maximum of marks using the list method sort.
![image](https://github.com/Swetha733N/FindMaximum/assets/122199934/bc4cd0d4-6c40-4813-9946-77a89d1c6c97)




	To find the maximum marks using the list method max().
![image](https://github.com/Swetha733N/FindMaximum/assets/122199934/9355b201-a436-4da0-aaf2-ef48323347a9)


 To find the maximum marks without using builtin functions.
![image](https://github.com/Swetha733N/FindMaximum/assets/122199934/f801558f-0eb4-47f0-a6f7-1d5c59433033)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
