# BinaryInsertion
Binary Insertion Sort assignment. 

1. Binary insertion sort uses binary search to find an appropriate position to insert A[i] among the previously sorted.
Give the Pseudocode for binary insertion sort:

Input: List to sort
For j  1 to n
// A binary search function for insert location
l  1 					  (l is left)
r  j -1 				(r is right)
while l < r
	m [(l + r)/2]	 		(middle)
	if aj > am 
		l m+1
	else
		r m

//The insertion sorting
if aj < al 
	i  l
else
	I  l+1
m  aj
for k 0 to j-i-1
	aj-k aj-k-1
ai  m
output: Sorted list

2. Determine algorithm’s worst-case efficiency class regarding the key comparisons (20%).
The swapping has complexity O(n) on the best case and O(n²) on the worst case. The time complexity of the binary search is O(nlogn). 
So in the best case of the Binary Insertion Sort, its total number of comparisons is O(nlogn).

However, in the worst case, it will have O(n2) comparisons, because worst case for swapping has a higher growth order than the binary search’s O(nlogn).


Use  binary insertion sort algorithm  to sort a list of student  records that  contain  student's ID,  name, age, and GPA.  
(Use student ID  as the sorting key (50%) 

a. Create a text file containing at least 20 students records
b. Your program has to write sorted records into another text file.  
c. Your program has to display student records before and after sorting.
