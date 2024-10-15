# DATE:
# EXP 06: Find the maximum of a list of numbers
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
#developed by: SREE NIVEDITAA SARAVANAN
#register number:212223230213

def max_marks(array):
    array.sort()
    return array[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python
#developed by: SREE NIVEDITAA SARAVANAN
#register number:212223230213

def max_marks(array):
    return max(array)


```

iii) # To find the maximum marks without using builtin functions.
```Python
#developed by: SREE NIVEDITAA SARAVANAN
#register number:212223230213

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1


```



## Output:
![Screenshot 2024-10-15 184859](https://github.com/user-attachments/assets/2c32ab0c-b366-4d7f-973e-59540a9ad3f9)
![Screenshot 2024-10-15 184911](https://github.com/user-attachments/assets/3f58a203-fef4-4a94-a092-6d5e24b75faa)
![Screenshot 2024-10-15 184945](https://github.com/user-attachments/assets/7deeb504-5e27-45fe-bf59-814ba90b7213)
![Screenshot 2024-10-15 185001](https://github.com/user-attachments/assets/63888241-60c2-46a3-82f3-744c0fae9399)
![Screenshot 2024-10-15 185012](https://github.com/user-attachments/assets/6bc5a28b-c374-4974-9456-3c24bec687ab)
![Screenshot 2024-10-15 185022](https://github.com/user-attachments/assets/a7f6d8be-10d1-4ab3-a468-88b6143aa6d4)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
