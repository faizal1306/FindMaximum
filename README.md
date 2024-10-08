## DATE: 
## Ex NO 6: Find the maximum of a list of numbers
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


#Developed by : AMALJOSH MAADHAV J
#Roll num: 212223230012
def max_marks(a):
    a.sort()
    return a[9]


```

ii)	# To find the maximum marks using the list method max().
```


#Developed by : AMALJOSH MAADHAV J
#Roll num: 212223230012
def max_marks(a):
    return max(a)


```

iii) # To find the maximum marks without using builtin functions.
```


#Developed by : AMALJOSH MAADHAV J
#Roll num: 212223230012
def max_marks(a):
    max =a[0]
    for i in a:
        if(i>max):
            max=i
    return max


```



## Output:
### i)
![image](https://github.com/user-attachments/assets/c8a8e648-8324-4f9a-81be-34225f8941ac)

### ii)
![image](https://github.com/user-attachments/assets/a727143d-a7da-47ff-b7e0-eee2959d9ce7)

### iii)
![image](https://github.com/user-attachments/assets/24b73731-53b0-4cde-991d-ce28fd466034)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
