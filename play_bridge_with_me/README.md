## _Problem_

"I have the makings of a very fine loafer, as well as a fairly spry kind of fellow.  In this case however my lethargy and intrinsic dislike of redundancy forces me to find a better solution to the problem""

"Find a better solution to which problem?  Holmes"

"Well I need to hunt like a well trained foxhound for clues once in a while as the science of deduction and analysis alas!  Cannot entirely operate from the armchair.  There is a list of houses numbered **1** to **N** where **N** is the number of houses.  There are bridges between some houses which may be one-way or two-way.  One can move from one house to another only if the bridge connecting them permits it i.e. is two-way or is one-way in that direction.  One cannot travel a bridge more than once and there may be multiple bridges connecting a pair of houses.  There may be bridges from a particular house to itself.  I would like to know as to whether I can make the tour of all bridges and come back to the starting point to perform a certain experiment which will lead me to a solution to Mr. Gibson's problem to the Thor Bridge or not?

Oh!  I have discovered a nice property about the houses.  I have found out that there is a house which has a route to every other house.  I hope this simplifies matters a bit."

"Why not travel a bridge multiple times Holmes?"

"There is no use traveling a bridge twice Watson.  I need to do the experiment only once and I would like to minimize the amout of walking I have to do if I can."
	
## _Input_

There are multiple test cases.  First line of the input consists of an integer **N** specifying the number of test cases.  Each test case follows the following format:

Two positive integers **N**, **M** on a line, where **N** is the number of houses, **M** is the number of bridges, followed by M lines, each containing 3 positive integers **u, v, p** which represents a bridge between house numbers **u** and **v** and the bridge is one-way if **p=1** and two-way if **p=0**.

**(1 <= u, v <= N)**.

## _Constraints_

***1 <= N <= 300***
***1 <= M <= 1000***

## _Output_

For each test case, print a single line containing **Yes/No**, **Yes** if the tour can be executed given the conditions and **No** if not.

## _Sample input_

1  
4 4  
1 2 1  
2 3 0  
3 4 1  
4 1 0  

## _Output for sample input_

**Yes**

