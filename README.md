Download Link: https://assignmentchef.com/product/solved-balls-solution
<br>
<span class="kksr-muted">Rate this product</span>

The objective of this problem is to test the students’ understanding on Doubly Linked List.Problem DescriptionThere are N balls labelled with 1, 2, 3,…, N, from left to right. Now, we want to do two kinds of operations:1. “A x y”: move the ball labelled x to the left of the ball labelled y, where x ≠ y.Reminder: if x is on the left of y, you may ignore this operation.2. “B x y”: move the ball labelled x to the right of the ball labelled y, where x ≠ y.Reminder: if x is on the right of y, you may ignore this operation.3. “R x”: remove the ball labelled x.Print the final arrangement after M operations.InputThe first line contains two integers, N (1&lt;= N &lt;= 1,000) and M (1&lt;= M &lt;= 1,000). The next M lines contain the operations.OutputOutput the final arrangement of the N balls from left to right. Each number is followed by a whitespace.Sample Input10 5A 2 1A 10 1A 5 6B 6 9R 3Sample Output2 10 1 4 5 7 8 9 6Explanation0th operation: 1 2 3 4 5 6 7 8 9 101st operation: 2 1 3 4 5 6 7 8 9 102nd operation: 2 10 1 3 4 5 6 7 8 93rd operation: 2 10 1 3 4 5 6 7 8 94th operation: 2 10 1 3 4 5 7 8 9 65th operation: 2 10 1 4 5 7 8 9 6Algorithm Template1. What data structure should be used to simulate the operations?2. What should be updated for insertion and deletion operations?3. What is the complexity for your algorithm?