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



```
ii)	# Find the element in a list using Binary Search(Iterative Method).
```





```
iii)	# Find the element in a list using Binary Search (recursive Method).
```






```
## Sample Input 
![Screenshot 2023-01-25 135210](https://user-images.githubusercontent.com/121166075/214514314-5aa3eb18-577f-4387-97fa-c35ced29f4ae.png)


##Output
![Screenshot 2023-01-23 195945](https://user-images.githubusercontent.com/121166075/214514519-e02c402f-87da-4a07-8ca4-d869aa84b108.png)
![Screenshot 2023-01-23 200023](https://user-images.githubusercontent.com/121166075/214514633-0c77d1d3-ce48-452a-b84e-0099a075f16c.png)
![Screenshot 2023-01-23 200113](https://user-images.githubusercontent.com/121166075/214514694-16ef9dcb-d906-4806-b840-89c2548a8a60.png)





## Result
Thus the linear search and binary search algorithm is implemented using python programming.
