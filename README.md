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
#Selection Sort

#developed By: SRIVATSAN G

#REGISTERED NO: 212223230216



```
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


#Insertion Sort

#developed By: SRIVATSAN G

#REGISTERED NO: 212223230216



```
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
![Screenshot 2024-04-28 144539](https://github.com/vatsan143/Sorting-Algorithms/assets/147368204/e5d7fa9e-1f8d-4fc4-bae0-ce1097552fdb)

![Screenshot 2024-04-28 144625](https://github.com/vatsan143/Sorting-Algorithms/assets/147368204/d17d6688-c803-43d1-9fb4-8f38d28af490)



## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
