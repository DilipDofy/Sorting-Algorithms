# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```python
#program to sort the elements in the list using the Selection Sort algorithm.
#Developed By: DILIP MP
#Register Number: 212223230048

num=eval(input())
for i in range(len(num)):
    low=i
    for j in range(i+1,len(num)):
        if num[j]<num[low]:
            low=j
    num[i],num[low]=num[low],num[i]
print(num)

```
ii)	#Insertion Sort
```python
#program to sort the elements in the list using the Insertion Sort algorithm.
#Developed By: DILIP MP
#Register Number: 212223230048

num=eval(input())
for i in range(1,len(num)):
    insert=num[i]
    j=i-1
    while j>=0 and num[j]>=insert:
        num[j+1]=num[j]
        j=j-1
    num[j+1]=insert
print(num)
        

```

## Output:
### selection sort
![Screenshot 2024-04-24 091146](https://github.com/DilipDofy/Sorting-Algorithms/assets/147223497/1709ee58-1327-42c4-8e28-2b4d70ab3b7f)
### insertion sort
![Screenshot 2024-04-24 091328](https://github.com/DilipDofy/Sorting-Algorithms/assets/147223497/438a88bc-a90e-4b24-8534-28bbe046c6bf)
## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
