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

 Developed by:V.Sai Sruthi
 Register Number:212223100061


i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    max_marks=max(marks)
    return max_marks
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    max=marks[0]
    for i in marks[1:]:
        if i>max:
            max=i
    return max       
```


## Output:

![image](https://github.com/sruthiviswanadham/FindMaximum/assets/151760421/59f2c4d6-37af-41d0-be02-08f347b1a996)
![image](https://github.com/sruthiviswanadham/FindMaximum/assets/151760421/3b4ea4d0-033f-4d99-bf6a-5435f1c79d65)
![image](https://github.com/sruthiviswanadham/FindMaximum/assets/151760421/e6c22fb4-9a64-443c-a0fb-b4dd743da62d)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
