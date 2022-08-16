You are given a positive integer N. Print a numerical triangle of height N-1 like the one below:
------------------------------------------------------------------------------------------------
1

22

333

4444

55555

. . . . . .
------------------------------------------------------------------------------------------------
Can you do it using only arithmetic operations, a single for loop and print statement?

Use no more than two lines. The first line (the for statement) is already written for you. You have to complete the print statement.

Note: Using anything related to strings will give a score of 0.

**Input Format**

A single line containing integer, N.

**Contraints**

1 <= N <= 9

**Output Format**

Print N-1 lines as explained above.

**Sample Input**

5

**Sample Output**

1

22

33

4444

**Explain Code**

If you use 10 ^ i with i from 1 to 9 then we get results like 10, 100, 1000 and so on. 
We'll take the results from that square, divide and round it by 9 to get results like 1, 11, 111 and so on. 
We will then multiply by the original i to get a triangle quest.

Pure math: ((10**i//9)*i)

