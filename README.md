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

i)
```


#Developed by : MOHAMED FAIZAL M
#Roll num: 24000006
def max_marks(array):
    array.sort()
    return array[-1]


```

ii)
```


#Developed by : MOHAMED FAIZAL M
#Roll num: 24000006
def max_marks(array):
    return max(array)





```

iii)
```
#Developed by : MOHAMED FAIZAL M
#Roll num: 24000006
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1



```



## Output:
### i)
![SS0](https://github.com/user-attachments/assets/41fb2816-8398-4bd6-b4eb-972a781f0ea3)


### ii)

![ss2](https://github.com/user-attachments/assets/7afde5d7-695a-4250-b87b-0a35edb9451f)

### iii)
![ss3](https://github.com/user-attachments/assets/fa05e814-6d6b-4c19-9fe2-5a21b717595f)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
