# Binary-Search
Binary search is the search technique that works efficiently on sorted lists.  
Conditions for when to apply Binary Search in a Data Structure:  
1.The data structure must be sorted.  
2.Access to any element of the data structure takes constant time.  
###Algorithm  
mid = (low + high)/2  
if (x == arr[mid])  
return mid  
else if (x > arr[mid]) // x is on the right side  
low = mid + 1  
else // x is on the left side  
high = mid - 1

