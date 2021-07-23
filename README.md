# Sorting algorithms
 Sorting any sequence means to arrange the elements of that sequence according to some specific criterion.
 
                      Insertion Sort --- Time Complexity: O(N2) --- in-place sorting algorithm
Insertion Sort is an In-Place sorting algorithm. This algorithm works in a similar way of sorting a deck of playing cards.

The idea is to start iterating from the second element of array till last element and for every element insert at its correct position in the subarray before it.

Algorithm:

Step 1: If the current element is 1st element of array, 
        it is already sorted.
        
Step 2: Pick next element

Step 3: Compare the current element will all elements 
        in the sorted sub-array before it.
        
Step 4: Shift all of the elements in the sub-array before 
        the current element which are greater than the current 
        element by one place and insert the current element 
        at the new empty space.
        
Step 5: Repeat step 2-3 until the entire array is sorted.<br>
<------------------------------------------------------------------------->

                        Bubble Sort --- Time Complexity: O(N2) ---  in-place sorting algorithm

Sorting algorithm and it works on the principle that:---
In one iteration if we swap all adjacent elements of an array such that after swap the first element is less than the second element then at the end of the iteration, the first element of the array will be the minimum element. <br>
<------------------------------------------------------------------------->
                        
