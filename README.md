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
## Sample Input and Output
![Screenshot 2023-01-23 195945](https://user-images.githubusercontent.com/121166075/214065398-d64deda4-86db-4384-a11b-806141093356.png)
![Screenshot 2023-01-23 200023](https://user-images.githubusercontent.com/121166075/214065477-fb8ee29c-d021-445a-be35-c261e68d222d.png)
![Screenshot 2023-01-23 200113](https://user-images.githubusercontent.com/121166075/214065527-ecce2f5d-781d-457b-8ace-76c7c7a7a434.png)







## Result
Thus the linear search and binary search algorithm is implemented using python programming.
