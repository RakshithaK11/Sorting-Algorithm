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
~~~
''' 
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: your name
RegisterNumber: 
'''
def selection_sort(nums):
    for i in range(1,len(nums)):
        item_to_insert=nums[i]
        j=i-1
        while j>=0 and nums[j]>item_to_insert:
            nums[j+1]=nums[j]
            j-=1
        nums[j+1]=item_to_insert
list_of_nums=eval(input())
selection_sort(list_of_nums)
print(list_of_nums)
~~~
ii)	#Insertion Sort
~~~''' 
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: your name
RegisterNumber: 
'''
def selection_sort(nums):
    for i in range(1,len(nums)):
        item_to_insert=nums[i]
        j=i-1
        while j>=0 and nums[j]>item_to_insert:
            nums[j+1]=nums[j]
            j-=1
        nums[j+1]=item_to_insert
list_of_nums=eval(input())
selection_sort(list_of_nums)
print(list_of_nums)
~~~

## Output:
![image](https://github.com/RakshithaK11/Sorting-Algorithm/assets/139336455/8b18c9ee-9c11-4fbd-b62a-86d6c6bf1a4b)
![image](https://github.com/RakshithaK11/Sorting-Algorithm/assets/139336455/493b9189-7e74-4648-8e54-8857d1277b81)

## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
