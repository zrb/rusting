## _Problem_

"London's Tube is one huge mess Watson! and the Department of Transport's Permanent Secretary has been in.  The Minister is adamant that something has to be done albeit belately regarding the public transport reorganiation.  As usual they are out of sorts and are looking to dump it on someone and bail out.  I hope I have not given them that chance"

"Let's try not to let them pin the tail on the donkey!"

"The problem is that - The stations of London are to be connected by one major line.  Let us consider the stations as vertices in an _unweighted graph_.  Two vertices are connected by an edge if a railway line can be constructed between them.  A path **P** is a sequence of consecutive edges and is acyclic.  Denote the distance of a vertex **v** from a vertex **w** on the path **P** by **d'(v, w)**.  Then the distance of **v** from a path **P** is defined as the minimum of the distances **d'(v, w)**, over all **w** on **P**, and is denoted by **d(v, P)**.  Now our goal is to find a path so as to minimize the sum of **d(v, P)** over all vertices **v**.  The problem is simplified by our knowledge of the fact that the _graph of London's cities is in fact a tree_."

"How are the two problems related Holmes?"

"Look at it this way Watson, the points on the path are already connected to every other point on the path by the means of the fast railway.  Now the local transport services are to cater to those places not on the railway.  If all places would be on the path, then **d(v, P)** is zero and we are done.  However, that is not the case."

## _Input_

There are multiple test cases.  First line of the input consists of an integer **n** specifying the number of test cases.  Each test case follows the following format.

A positive integer **N**, the number of vertices in the graph followed by **N - 1** lines each consisting of two integer **u, v**, separated by a space, indicating that there is an edge between **u** and **v**.  The vertices are numbered from **1** to **N**.

## _Constraints_

**1 <= N <= 1000**

## _Output_

For each test case, print one integer which equals the minimum sum of **d(v, P)**

## _Sample input_

1  
7  
1 2  
2 3  
4 2  
4 5  
5 6  
5 7  

## _Output for sample input_

2  

