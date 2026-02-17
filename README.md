# 2D-Matrix
Searching an element in 2d array:
2 condition:
--> If elements are sorted 
--> If elements are not sorted

1.In this type we have to got element by element and check for the element.
Time complexity : O(row x coloumn)

2.In this case we will perform binary search 2 times 

1  2  3
4  5  6
7  8  9
10 11 12

suppose i have to search for 8 then first i will search for the row in which i can find this value

i will create a variable 
value = arr[i][0]
mid = min + (max - min)/2
if(value > mid)
{
min = arr[i+1][0]
}
else{
max = arr[i-11][0]
}
}
