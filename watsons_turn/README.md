## _Problem_

"Watson, London has become a fairly uninteresing city after the demise of our learned friend Prof. Moriarty"

"You might hardly find any decent citizen likely to agree with you"

"The people are definitely the gainer, but spare a thought for the poor out of work specialist, whose profession is gone."

"Well Holmes, if work is all you are interested in - I have a small puzzle for you if you feel up to it"

"On the contrary, it will be most welcome."

"The Daily Telegraph delights in these don't they - There are **N** pairs of points on a the plane with integral coordinates.  The two points in each pair are to be connected by a piece of string that bends at right angles at only one point **P**.  The two halves of the string on either side of **P** are parallel to the **X** and **Y** axes.  It is to be determined whether one can connect every pair of points with pieces of strings without strings of different pairs intersecting, not even touching, each other"

"Hmmm, interesting!  May I know what your views are?  The faint smile on your face reveals that you have possibly already thought of a solution"

"Yes Holmes!  I thought of checking all combinations of pairs of points for a conflict"

"Some people, Watson, have a remarkable capacity for stimulating genius without possessing the immortal trait themselves.  Your approach unfortunately, is rather naive.  It would take a huge time to solve even small problems.  However, it is a fairly decent start and we can do much better on it."

## _Input_

There are multiple test cases.  First line of input consists of an integer **n** specifying the number of test cases.  Each test case follows the following format:

A poisitive integer **N** on a line, where **N** is the number of pairs, followed by **N** lines each consisting of 4 integers **x1, y1, x2, y2**, where **(x1, y1) and (x2, y2)** are the coordiantes of the points in a pair

## _Constraints_

For points **(x1, y1)** and **(x2, y2)** in a pair, **x1 != x2** and **y1 != y2**

**1 <= N <= 1000**

## _Output_

For each test case print a single line containing **Yes/No**, **Yes** if the pairs can be connected without any intersection and **No** if not.

## _Sample input_

1  
2  
1 1 2 4  
0 2 4 3  

## _Output for sample input_

**No**

