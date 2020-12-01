# 100-days-of-code
100-days-of-code is a challenge where I set myself the goal to code atleast for an hour everyday for the next 100 days.
Iam learning Data Structures through C++ and Algorithms in the next 100 days


# ***TOPIC - ARRAYS***
### [Day-1](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-1) 
### Reverse an array

        C++ program to reverse an array
        
        Example 1:
                Input  : array[] = {1, 2, 3}
                Output : array[] = {3, 2, 1}

        Example 2:
                Input :  array[] = {4, 5, 1, 2}
                Output : array[] = {2, 1, 5, 4}

### [Day-2](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-2) 
### Minimum and maximum in an array

        C++ program to find the minimum and maximum elements in an array.
        
        Method 1 - By sorting the array 
        Method 2 - By Linear search

        Example:
                Input : array[] = {4, 5, 10, 25, 2, 3}
                Ouput : min = 2, max = 25
        
### [Day-3](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-3)
### kth smallest element in an array

        C++ program to find the kth smallest element in an array.

        Example:
                Input : array[] = {7, 10, 4, 3, 20, 15}, k = 2
                Output : 7
                Explanation : k is 2, so 2nd smallest element is 7
        
### [Day-4](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-4)
### Sort an array of 0s,1s, 2s

        C++ program to sort the array of 0s, 1s, 2s in ascending order without using any sorting algorithm

        Given an array containing 0s, 1s, and 2s; you need to sort the array in ascending order.

        Example:
                Input : array[] = {2, 1, 1, 0, 0, 2, 0, 1}
                Output : array[] = {0, 0, 0, 1, 1, 1, 2, 2}

### [Day-5](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-5)
### Move all negatives to one side of array

        C++ program to move all the negative numbers to the beginning of the array.

        An array contains both positive and negative numbers in random order.
        Rearrange the array elements so that all negative numbers appear before all positive numbers.

        Example:
                Input : 1, -5, -6, 10, 25, 33, -20
                Ouput : -20, -5, -6, 10, 25, 33, 1

        Note : Order of elements is not important here. 

### [Day-6](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-6)
### Union and intersection af arrays

        C++ program to fid the union and intersection of two sorted arrays.

        Given two sorted arrays, the task is to find their union and intersection.

        Example 1:
                Input : arr1[] = {1, 3, 4, 5, 7}
                        arr2[] = {2, 3, 5, 6} 
                Output : Union : {1, 2, 3, 4, 5, 6, 7} 
                        Intersection : {3, 5}
                
        Example 2:
                Input : arr1[] = {2, 5, 6}
                        arr2[] = {4, 6, 8, 10} 
                Output : Union : {2, 4, 5, 6, 8, 10} 
                        Intersection : {6}

### [Day-7](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-7)
### Rotate an array

        C++ program to cyclically rotate an array by one.

        Example 1:
                Input : array[] = {1, 2, 3, 4, 5}
                Output : array[] = {5, 1, 2, 3, 4}

        Example 2:
                Input : array[] = {9, 8, 7, 6, 4, 2, 1, 3}
                Output : array[] = {8, 7, 6, 4, 2, 1, 3, 9}

### [Day-8](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-8)
### Minimize the difference between heights

        C++ program to minimize the difference between longest and shortest heights of a tower.
        
        Given an array arr[] denoting heights of N towers and a positive integer K.
        You have to modify the height of each tower either by increasing or decreasing them by K only once.
        After modifying, height should be a non-negative integer. 
        Find out what could be the possible minimum difference of the height of shortest and longest towers after you have modified each tower.

        Example 1:
                Input: K = 2, N = 4, Arr[] = {1, 5, 8, 10}
                Output: 5
                Explanation: The array can be modified as {3, 3, 6, 8}.
                The difference between the largest and the smallest is 8-3 = 5.

        Example 2:
                Input: K = 3, N = 5, Arr[] = {3, 9, 12, 16, 20}
                Output: 11
                Explanation: The array can be modified as {6, 12, 9, 13, 17}.
                The difference between the largest and the smallest is 17-6 = 11.

### [Day-9](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-9)
### Find duplicate in an array
        C++ program to find the duplicate element in an array.

        Given an array of size n + 1, which contains n distinct elements and 1 element is repeated.
        The task is to find out the repeated element.

        Example 1:
                Input : array[] = {2, 1, 3, 6, 1}
                Output : 1

        Example 2:
                Input : array[] = {9, 5, 8, 3, 5, 1, 2}
                Output : 5

### [Day-10](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-10)
### Merge two sorted arrays

        C++ program to merge two sorted arrays into one sorted array.

        Given two sorted arrays array1[], array2[] of size1, size2.
        Each array is sorted in non-decreasing order.
        Merge the two arrays into one sorted array in non-decreasing order without using any extra space.

        Example 1:

                Input:   size1 = 4, size2 = 5
                        array1[] = {1, 3, 5, 7}
                        array2[] = {0, 2, 6, 8, 9}

                Output: 0 1 2 3 5 6 7 8 9

                Explanation: Since you can't use any extra space, modify the given arrays to form 
                        array1[] = {0, 1, 2, 3}
                        array2[] = {5, 6, 7, 8, 9}

        Example 2:

                Input:  size1 = 2, size2 = 3
                        array1[] = {10, 12}
                        array2[] = {5, 18, 20}

                Output: 5 10 12 18 20

                Explanation: Since you can't use any extra space, modify the given arrays to form 
                        array1[] = {5, 10}
                        array2[] = {12, 18, 20}

### [Day-11](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-11)
### Merge overlapping intervals

        C++ program to merge the overlapping intervals.

        Given an array of intervals where intervals[i] = [starti, endi], merge all overlapping intervals,
        and return an array of the non-overlapping intervals that cover all the intervals in the input.

        Example 1:

                Input: intervals = [[1,3],[2,6],[8,10],[15,18]]
                Output: [[1,6],[8,10],[15,18]]
                Explanation: Since intervals [1,3] and [2,6] overlaps, merge them into [1,6].

        Example 2:

                Input: intervals = [[1,4],[4,5]]
                Output: [[1,5]]
                Explanation: Intervals [1,4] and [4,5] are considered overlapping.

### [Day-12](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-12)
### Buy and sell stock

        Say you have an array for which the ith element is the price of a given stock on day i.
        If you were only permitted to complete at most one transaction (i.e., buy one and sell one share of the stock), design an algorithm to find the maximum profit.
        Note that you cannot sell a stock before you buy one.

        Example 1:

                Input: [7,1,5,3,6,4]
                Output: 5
                Explanation: Buy on day 2 (price = 1) and sell on day 5 (price = 6), profit = 6-1 = 5.
                                Not 7-1 = 6, as selling price needs to be larger than buying price.
        Example 2:

                Input: [7,6,4,3,1]
                Output: 0
                Explanation: In this case, no transaction is done, i.e. max profit = 0.

### [Day-13](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-13)
### KADANE'S ALGORITHM

        C++ program to find the contiguous sub-array with maximum sum.

        Given an array arr of N integers. Find the contiguous sub-array with maximum sum.

        Example 1:

                Input : N = 5
                        arr[] = {1,2,3,-2,5}
                Output: 9
                Explanation: Max subarray sum is 9 of elements (1, 2, 3, -2, 5) which is a contiguous subarray.

        Example 2:

                Input : N = 4
                        arr[] = {-1,-2,-3,-4}
                Output: -1
                Explanation: Max subarray sum is -1 of element (-1)

### [Day-14](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-14)
### Common elements in 3 arrays

        C++ program to find the common elements in 3 sorted arrays.

        Given three arrays sorted in increasing order. Find the elements that are common in all three arrays.
        Note: Try to take care of the duplicates without using any additional Data Structure.

        Example 1:

                Input:  size1 = 6; array1 = {1, 5, 10, 20, 40, 80}
                        size2 = 5; array2 = {6, 7, 20, 80, 100}
                        size3 = 8; array3 = {3, 4, 15, 20, 30, 70, 80, 120}
                Output: 20 80
                Explanation: 20 and 80 are the only common elements in array1, array2, array3.

        Example 2:

                Input:  size1 = 3; array1 = {3, 3, 3}
                        size2 = 3; array2 = {3, 3, 3}
                        size3 = 3; array3 = {3, 3, 3}
                Output: 3
                Explanation: 3 is the only common element in array1, array2, array3.

### [Day-15](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-15)
### Finding the longest consecutive subsequence

        C++ program to find the longest consecutive subsequence.

        Given an array of positive integers.
        Find the length of the longest sub-sequence such that elements in the subsequence are consecutive integers, the consecutive numbers can be in any order.

        Example 1:

                Input:  size = 7
                        array[] = {2,6,1,9,4,5,3}
                Output: 6
                Explanation: The consecutive numbers here are 1, 2, 3, 4, 5, 6. 
                These 6 numbers form the longest consecutive subsquence.

        Example 2:

                Input:  size = 7
                        array[] = {1,9,3,10,4,20,2}
                Output: 4
                Explanation: 1, 2, 3, 4 is the longest consecutive subsequence.

### [Day-16](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-16)
### Inversion count

        C++ program to find the count of inversions in an array.

        Given an array of integers. Find the Inversion Count in the array. 

        Inversion Count: For an array, inversion count indicates how far (or close) the array is from being sorted. 
        If array is already sorted then the inversion count is 0. 
        If an array is sorted in the reverse order then the inversion count is the maximum. 
        Formally, two elements a[i] and a[j] form an inversion if a[i] > a[j] and i < j.
        
        Example 1:

                Input: N = 5, arr[] = {2, 4, 1, 3, 5}
                Output: 3
                Explanation: The sequence 2, 4, 1, 3, 5 has three inversions (2, 1), (4, 1), (4, 3).

        Example 2:

                Input: N = 5, arr[] = {2, 3, 4, 5, 6}
                Output: 0
                Explanation: As the sequence is already sorted so there is no inversion count.

        Example 3:

                Input: N = 3, arr[] = {10, 10, 10}
                Output: 0
                Explanation: As all the elements of array are same, so there is no inversion count.

### [Day-17](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-17)
### Chocolate distribution problem
        C++ program to solve chocolate distribution problem.

        Given an array A of positive integers of size N, where each value represents number of chocolates in a packet. 
        Each packet can have variable number of chocolates. 
        There are M students, the task is to distribute chocolate packets such that :
        1. Each student gets one packet.
        2. The difference between the number of chocolates given to the students having packet with maximum chocolates and student having packet with minimum chocolates is minimum.

        Example 1:
        
                Input : arr[] = {7, 3, 2, 4, 9, 12, 56} , m = 3 
                Output: Minimum Difference is 2 
                Explanation:
                We have seven packets of chocolates and we need to pick three packets for 3 students 
                If we pick 2, 3 and 4, we get the minimum difference between maximum and minimum packet sizes.

        Example 2:

                Input : arr[] = {3, 4, 1, 9, 56, 7, 9, 12} , m = 5 
                Output: Minimum Difference is 6 
                Explanation:
                The set goes like 3,4,7,9,9 and the output is 9-3 = 6

        Example 3:

                Input : arr[] = {12, 4, 7, 9, 2, 23, 25, 41, 30, 40, 28, 42, 30, 44, 48, 43, 50} , m = 7 
                Output: Minimum Difference is 10 
                Explanation:
                We need to pick 7 packets. 
                We pick 40, 41, 42, 44, 48, 43 and 50 to minimize difference between maximum and minimum. 


        Approach : 
        We first sort the array arr[0..n-1], then find the subarray of size m with the minimum difference between the last and first elements.

### [Day-18](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-18)
### Minimum number of jumps required to reach the end of array

        C++ program to find minimum number of jumps required to reach the end of array.

        Given an array of integers where each element represents the number of steps that can be made forward from that element. 
        Write a function to return the minimum number of jumps to reach the end of the array (starting from the first element).
        If an element is 0, then cannot move through that element.

        Example 1:
                Input  : array[] = {1, 3, 5, 8, 9, 2, 6, 7, 6, 8, 9}
                Output : 3 
                Explanation: (1 -> 3 -> 9 -> 9)

        Example 2:
                Input   : array[] = {1, 4, 3, 2, 6, 7}
                Output  : 2

### [Day-19](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-19)
### Check if an array is subset of another array

        C++ program to find whether an array is subset of another array.

        Given two arrays: arr1[0..m-1] of size m and arr2[0..n-1] of size n. 
        Task is to check whether arr2[] is a subset of arr1[] or not. 
        Both the arrays can be both unsorted or sorted. 
        It may be assumed that elements in both array are distinct.

        Print "Yes"(without quotes) if arr2 is subset of arr1.
        Print "No"(without quotes) if arr2 is not subset of arr1.

        Example 1: 

                Input : arr1[] = {11, 1, 13, 21, 3, 7}
                        arr2[] = {11, 3, 7, 1} 
                Output: Yes

        Example 2:

                Input : arr1[] = {1, 2, 3, 4, 5, 6}
                        arr2[] = {1, 2, 4} 
                Output: Yes

        Example 3:

                Input : arr1[] = {10, 5, 2, 23, 19}
                        arr2[] = {19, 5, 3} 
                Output: No

### [Day-20](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-20)
### Rearrange an array in alternating positive and negative items

        C++ program to rearrange an array in alternating positive and negative items with O(1) extra space.

        Given an array of positive and negative numbers, arrange them in an alternate fashion such that every positive number is followed by negative and vice-versa.
        Number of positive and negative numbers need not be equal. 
        If there are more positive numbers they appear at the end of the array. 
        If there are more negative numbers, they too appear in the end of the array.

        Example 1 :

                Input:  arr[] = {1, 2, 3, -4, -1, 4}
                Output: arr[] = {-4, 1, -1, 2, 3, 4}

        Example 2 :

                Input:  arr[] = {-5, -2, 5, 2, 4, 7, 1, 8, 0, -8}
                output: arr[] = {-5, 5, -2, 2, -8, 4, 7, 1, 8, 0} 

### [Day-21](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-21)
### Median of an array

        C++ program to calculate the median of an array.

        Given an array arr[] of N integers, calculate the median.

        Example 1:

                Input: N = 5, arr[] = 90 100 78 89 67
                Output: 89
                Explanation: After sorting the array middle element is the median 

        Example 2:

                Input: N = 4, arr[] = 56 67 30 79
                Output: 61
                Explanation: In case of even number of elements average of two middle elements is the median

### [Day-22](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-22)
### Median of 2 arrays of same size

C++ program to calculate the median of two sorted arrays of same size.

There are 2 sorted arrays A and B of size n each. 
Write an algorithm to find the median of the array obtained after merging the above 2 arrays(i.e. array of length 2n.)

Example 1: 

    Input :
        ar1[] = {1, 12, 15, 26, 38}
        ar2[] = {2, 13, 17, 30, 45}
    Output : 16
    Explanation : Both arrays after merging  {1, 2, 12, 13, 15, 17, 26, 30, 38, 45}
                  The median is (15+17)/2 = 16

Example 2:

    Input :
        ar1[] = {1, 2, 3, 6}
        ar2[] = {4, 6, 8, 10}
    Output : 5

### [Day-23](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-23)
### Median of 2 arrays of different sizes

        C++ program to calculate the median of two sorted arrays of different sizes.

        Example 1:

                Input: ar1[] = {-5, 3, 6, 12, 15}
                        ar2[] = {-12, -10, -6, -3, 4, 10}
                Output : The median is 3.
                Explanation : The merged array is : ar3[] = {-12, -10, -6, -5 , -3, 3, 4, 6, 10, 12, 15},
                                So the median of the merged array is 3.

        Example 2:

                Input: ar1[] = {2, 3, 5, 8}
                        ar2[] = {10, 12, 14, 16, 18, 20}
                Output : The median is 11.
                Explanation : The merged array is : ar3[] = {2, 3, 5, 8, 10, 12, 14, 16, 18, 20}
                        if the number of the elements are even, so there are two middle elements, take the average between the two : (10 + 12) / 2 = 11.      

        Algorithm : 
        1. Create an array "arr3[]" of length (size1 + size2), if size1 and size2 are the lengths of given input arrays, say "arr1[]" and "arr2[]".
        2. Simultaneously traverse through array1[] and array2[].
        Pick smaller of current elements in arr1[] and arr2[], copy this smaller element to next position in arr3[] and move ahead in arr3[] and the array whose element is picked.
        3. If there are remaining elements in arr1[] or arr2[], copy them also in arr3[].
        4. Find the middle index of arr3[], say "mid". mid = (len(arr3) - 1 / 2)
        5. If there are odd number of elements in arr3[], then print the value of "arr3[mid]".
        If there are even number of elements in arr3[], then median is the average of two middle elements, i.e, (arr3[mid] + arr3[mid + 1]) / 2.

### [Day-24](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-24)
### Palindromic Array

        C++ program to check if all the elements in an array are palindromes.

        Given a Integer array A[] of n elements.
        Print 1  if all the elements of the Array are palindrome otherwise print 0.

        Example 1:
                Input : arr[] = {111, 222, 333, 444, 555}
                Output : 1

        Example 2:
                Input : arr[] = {121, 30, 434}
                Output : 0

        Algorithm :
        1. Iterate through the given array. 
        2. For each element, check if it is palindrome or not.
        3. If all elements are palindrome, then print 1.
        If any of the element is not palindrome, then print 0 and stop iteration.

### [Day-25](https://github.com/vaishnavi-konda/100-days-of-code/tree/main/Day-25)
### Number of pairs in an array with given sum 

        C++ program to find the number of pairs in an array with given sum.

        Given an array of integers, and a number ‘sum’.
        Find the number of pairs of integers in the array whose sum is equal to ‘sum’.

        Example 1:
                Input  :  arr[] = {1, 5, 7, -1}, sum = 6
                Output :  2
                Pairs with sum 6 are (1, 5) and (7, -1)

        Example 2:
                Input  :  arr[] = {1, 5, 7, -1, 5}, sum = 6
                Output :  3
                Pairs with sum 6 are (1, 5), (7, -1) & (1, 5)         

        Example 3:
                Input  :  arr[] = {1, 1, 1, 1}, sum = 2
                Output :  6
                There are 3! pairs with sum 2.

        Example 4:
                Input  :  arr[] = {10, 12, 10, 15, -1, 7, 6, 5, 4, 2, 1, 1, 1}, sum = 11
                Output :  9

        Algorithm :
        A simple solution is be traverse each element and check if there’s another number in the array which can be added to it to give sum.
        But the time complexity is O(n^2).

        Another efficient approach :
        1. Create a map to store frequency of each number in the array. (Single traversal is required)
        2. In the next traversal, for every element check if it can be combined with any other element (other than itself!) to give the desired sum. 
        Increment the counter accordingly.
        3. After completion of second traversal, we’d have twice the required value stored in counter because every pair is counted two times. 
        Hence divide twice_count by 2 and return.

        Here time complexity is O(n).