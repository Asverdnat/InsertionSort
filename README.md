# [22, 27, 16, 2, 18, 6] -> insertion sort

1- all steps for sorting

[2, 27, 16, 22, 18, 6]
[2, 6, 16, 22, 18, 27]
[2, 6, 16, 18, 22, 27]

2- Big O Notation

In the first step we inspected n piece of elements and chose the right one.
After that we decided the smallest one, we inspected n-1 piece of elements and found the second smallest one.
Thanks to we found first two smallest number, we inspected n-2 piece of elements and found the right order.
In conclusion, we used n + (n-1) + (n-2) . . . and so on totally n*(n+1)/2 which means (n^2+n)/2.
That clearly shows us the Big O Notation is n^2

3-all cases

There are 3 types of cases; 
Average case: when we find our element in the middle
Worst case: when we find our element at last
Best case: when we finf our element at first.

In this example we can show that

Average case: [22, 27, 2, 16, 18, 6]
Worst case: [22, 27, 16, 6, 18, 2]
Best case: [2, 27, 16, 22, 18, 6]

4- the array which is edited for sorting is [2, 6, 16, 18, 22, 27]. If we inspect for 18, which is 4th element, it gives us the average case.


Insertion Sort

[7,3,5,8,2,9,4,15,6]

[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]

