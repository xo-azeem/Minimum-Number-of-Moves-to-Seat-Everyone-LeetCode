# Minimum-Number-of-Moves-to-Seat-Everyone

LeetCode Q # 2037.

There are n availabe seats and n students standing in a room. You are given an array seats of length n, where seats[i] is the position of the ith seat. You are also given the array students of length n, where students[j] is the position of the jth student. You may perform the following move any number of times:</br>
 - Increase or decrease the position of the ith student by 1 (i.e., moving the ith student from position x to x + 1 or x - 1)</br></br>

Return the minimum number of moves required to move each student to a seat such that no two students are in the same seat.

Note that there may be multiple seats or students in the same position at the beginning.

Example 1:

>Input: seats = [3,1,5], students = [2,7,4]</br>
>Output: 4</br>
>Explanation: The students are moved as follows:</br>
>- The first student is moved from from position 2 to position 1 using 1 move.</br>
>- The second student is moved from from position 7 to position 5 using 2 moves.</br>
>- The third student is moved from from position 4 to position 3 using 1 move.</br>
>In total, 1 + 2 + 1 = 4 moves were used.</br>

Example 2:

>Input: seats = [4,1,5,9], students = [1,3,2,6]</br>
>Output: 7</br>
>Explanation: The students are moved as follows:</br>
>- The first student is not moved.</br>
>- The second student is moved from from position 3 to position 4 using 1 move.</br>
>- The third student is moved from from position 2 to position 5 using 3 moves.</br>
>- The fourth student is moved from from position 6 to position 9 using 3 moves.</br>
>In total, 0 + 1 + 3 + 3 = 7 moves were used.</br>

Example 3:

>Input: seats = [2,2,6,6], students = [1,3,2,6]</br>
>Output: 4</br>
>Explanation: Note that there are two seats at position 2 and two seats at position 6.</br>
>The students are moved as follows:</br>
>- The first student is moved from from position 1 to position 2 using 1 move.</br>
>- The second student is moved from from position 3 to position 6 using 3 moves.</br>
>- The third student is not moved.</br>
>- The fourth student is not moved.</br>
>In total, 1 + 3 + 0 + 0 = 4 moves were used.</br>

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Minimum-Number-of-Moves-to-Seat-Everyone-LeetCode/assets/171427226/d28fe795-a386-4c20-a2ac-3461f973c81c)

  Time complexity: O(nlogn).</br>Space complexity: O(1).
</div>
