## _Problem_

"The Times brings us once again into the horizon of numbers dear Watson.  I solved this today morning.  Given two positive integers **R** and **S**, consider the following permutation of **(1, 2, ..., R, R + 1, R + S) : (R + 1, ..., R + S, 1, ...R)**

If we consider permutations as the product of cycles how many cycles are there in the permutation?  The solution lies in the realms of..."

"How absurdly simple!  Holmes"

"Quite so, Watson, every problem becomes simples when it is explained to you.  Here however an unsolved one on the same lines, what do you make of this?

"Consider three positive integers **R, S, T**.  Let us define **A, B, C** to be the following blocks of numbers

   **A = (1, 2, ..., R)**
   **B = (R + 1, ..., R + S)**
   **C = (R + S + 1, ..., R + S + T)**

Consider the following permutations of **(1, 2, ..., R, R + 1, ..., R + S, R + S + 1, ..., R + S + T)**.

   **Permutation #1 -> ABC**
   **Permutation #2 -> ACB**
   **Permutation #3 -> BAC**
   **Permutation #4 -> BCA**
   **Permutation #5 -> CAB**
   **Permutation #6 -> CBA**

We need to find the number of cycles in the permutations defined above."
	
## _Input_

There are multiple test cases.  First line of the input consists of an integer **N** specifying the number of test cases.  Each test case consists of threee positive integers **R, S, T**, on a single line.

## _Constraints_

***1 <= R, S, T <= 10^9***

## _Output_

For each test case, print a single line containing _six integers_ the _i-th_ of which equals the number of cycles in permutation #_i_, (**1 <= i <=6**).

## _Sample input_

2  
1 1 1  
2 2 1  

## _Output for sample input_
---
3 2 2 1 1 2  
5 3 3 1 1 1  

