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
``` 
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: ARHAM S
RegisterNumber: 212222110005

def selection_sort(nums):
     nums.sort()
     return nums
  

    
    
list_of_nums = eval(input())
result =selection_sort(list_of_nums)
print(result)
```

ii)	#Insertion Sort
```
''' 
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: ARHAM S
RegisterNumber: 212222110005 
'''
def insertion_sort(nums):
    for step in range(1,len(nums)):
        key = nums[step]
        j = step -1
        
        while j>=0 and key < nums[j]:
            nums[j + 1] = nums[j]
            j =j-1
            
        nums[j + 1] = key
    
    
    
list_of_nums = eval(input())
insertion_sort(list_of_nums)
print(list_of_nums)

```






## Output:
![Screenshot (26)](https://github.com/arhamshajahan/Sorting-Algorithm/assets/127313881/007dbb9b-1707-4486-9662-9dd90f8e913b)
![Screenshot (27)](https://github.com/arhamshajahan/Sorting-Algorithm/assets/127313881/94de0ed6-df67-4e65-96c4-b8db5f0fdf8a)


## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
