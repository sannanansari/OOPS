# le Sort

## Introduction:   
The rte Sort algorithm Sorts an array buy repeatedly finding the minimum element(for ascending Order) from the unsorted part and putting it at beginning.  
It is Divided into Two subarray:-  
1. The array Which is already Sorted.  
2. Which to be Sort(unsorted).  

## Algorithm:  

Step 1 − Set MIN to location 0  
Step 2 − Search the minimum element in the array  
Step 3 − Swap with value at location MIN  
Step 4 − Increment MIN to point to next element  
Step 5 − Repeat until array is sorted  

```C
Algorthim:-
void selection(arr[],n)  
  for i=0 to n-1  //one by one unsorted array  
    //Finding Minimum Element  
 	min = i    //assigning Current as minimum  
	for j = i+1 to n  
		if arr[j]<arr[min]  
			min = j  
		end if  
	end for	  
	//Swaping Current element with minimum element  
	swap(arr[min],arr[i])  
  end for  
```
## Explanation:-  
Selection Sort can be explain on 2 steps:-  
1.Find minimum element in unsorted part:-   
+ Fix min(minimum) as current element.  
+ Then compare min with with unsorted elements.  
	- if any element at that position is greater than current then do nothing.  
	- if any element at that position is smaller than current then fix it as min.  
2.Swap current element arr[i] with arr[min]:-  
+ It will swap if min is found or Not. 

# [Selection_Sort Code Click here](https://github.com/sannanansari/OOPS/blob/master/Sort/Selecton_Sort/Selecton_Sort.c)



 