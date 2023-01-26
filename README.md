# Linear Search and Binary search
## Aim:
To write a program to perform linear search and binary search using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Linear Search:
1.	Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2.	If k matches with an element in array[] , return the index.
3.	If k doesn’t match with any of elements in array[], return -1 or element not found.
## Binary Search:
1.	Set two pointers low and high at the lowest and the highest positions respectively.
2.	Find the middle element mid of the array ie. arr[(low + high)/2]
3.	If x == mid, then return mid.Else, compare the element to be searched with m.
4.	If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5.	Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6.	Repeat steps 2 to 5 until low meets high
## Program:
i)	#Use a linear search method to match the item in a list.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: HARISH RAGAVENDRA S
RegisterNumber: 22008967
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large    
```
ii)	# Find the element in a list using Binary Search(Iterative Method).
```
''' 
Program to find the maximum marks using the list method max().
Developed by: HARISH RAGAVENDRA S
RegisterNumber: 22008967
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large    
```
iii)	# Find the element in a list using Binary Search (recursive Method).
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: HARISH RAGAVENRA S
RegisterNumber: 22008967
'''
def max_marks(list1):
    list1.sort()
    large=list1[-1]
    return large    

```
## Sample Input and Output
![output!](output1.png)
![output!](output2.png)
![output!](output3.png)




## Result
Thus the linear search and binary search algorithm is implemented using python programming.