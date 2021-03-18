This is your opportunity to show us how efficient you can write algorithms. We take an anti whiteboard approach because we feel this isn't the best way to show us your knowledge on DS+Algorithms. A lot of the job is realistically spent on stackoverflow and github forums and an algorithm challenge shouldn't be any different. 

Here is the challenge:

Write an algorithm that searches for a target value in an M x N matrix. Please write your solution in the task_3_submission.php file provided in this directory. 

Example 1: <br>
Input: Matrix = [[1,4,7,11,15],[2,5,8,12,19]], target = 5<br>
```
[
    [1,4,7,11,15],
    [2,5,8,12,18]
]
```
Output: true <br>
Explanation: Since the target is 5 and 5 is in the matrix, we can conclude that the target value of 5 is in the matrix and return true.

Example 2: <br>
Input: Matrix = [[1,4,7,11,15],[2,5,8,12,19]], target = 20 <br>
```
[
    [1,4,7,11,15],
    [2,5,8,12,18]
]
```
Output: false
Explanation: Since the target is 20 and 20 is not in the matrix, return false. 

Input constraints:

- M == matrix.length
- N == matrix[i].length
- 1 <= N, M <= 300
- -10^9 <= matrix[i][j] <= 10^9
- -10^9 <= target <= 10^9
- Every integer in matrix is unique

