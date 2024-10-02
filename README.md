# Totient-Permutation
Problem Statement
You are tasked with finding the value of 
𝑛
n (where 
𝑛
n is less than or equal to a given integer 
𝑚
m), such that the ratio 
𝑛
𝜙
(
𝑛
)
ϕ(n)
n
​
  is minimized. Additionally, 
𝜙
(
𝑛
)
ϕ(n) must be a permutation of 
𝑛
n.

Definitions
Euler's Totient Function 
𝜙
(
𝑛
)
ϕ(n): This function counts the number of positive integers up to 
𝑛
n that are relatively prime to 
𝑛
n.
Input Format
A single integer 
𝑚
m (1 ≤ 
𝑚
m ≤ 100,000).
Output Format
Print the value of 
𝑛
n corresponding to the minimum ratio 
𝑛
𝜙
(
𝑛
)
ϕ(n)
n
​
  for which 
𝜙
(
𝑛
)
ϕ(n) is a permutation of 
𝑛
n.
Constraints
It is guaranteed that at least one solution exists for the given input.
Sample Input
Copy code
100
Sample Output
Copy code
21
Explanation
For the sample input, the output 
21
21 means that 
𝜙
(
21
)
=
12
ϕ(21)=12, and 
12
12 is a permutation of 
21
21. The ratio 
21
12
12
21
​
  is minimized among all candidates up to 
100
100.

