## _Problem_

"Its good to see you again Watson, you've had the misfortune of having the British workman in your house again.  Not the gas I hope?"

"No the stairs"

"He has left criss-crossing marks all over the linoleum.  But halloa!  what's this, he uses a remarkably blunt instrument, but for all his callousness, these marks are ... like this ...and again ... and now ...His tool's end is precisely like ..."

"I must be rather stupid, but I really do not get how you deduced the tool shape."

"Elementary my dear fellow, in he recent case of Lady Chesterfeld, I had the honor of working out the solution to a rather interesting problem which I now lay out for your examination-

There are **N** lines on the plane each of infinite length.  Find the minimum area of a convex polygon that includes all the intersection points between the lines."

## _Input_

There are multiple test cases.  First line of the input consists of an integer **n** specifying the nuber of test cases.  Each test case follows the following format:

A positive integer **N** on a line, where **N** is the number of lines followed by **N** lines each consisting of **4** integers **x1, y1, x2, y2**, where **(x1, y1)** and **(x2, y2)** are the coordinates of two distinct points on the line.  You may assume that no two lines are parallel.

## _Constraints_

If **(x, y)** is an intersection point of two distinct lines in the input, **|x|, |y|** <= 250000.

## _Output_

For each test case, print a single line containing one integer equal to the floor (largest integer less than or equal to a number) of the minimum area required.

## _Sample input_

1  
3  
1 1 2 2  
2 0 0 2  
0 0 0 1  

## _Output for sample input_

1

