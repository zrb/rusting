## _Problem_

Sherlock Holmes took out the neat injection syringe from its Morocco case and pressed the sharp point home, settling down with a sigh of relief to his armchair.

"What is it today?  Morphine or Cocaine?"

"It is cocaine, a 7% solution.  Would you care to try it?"

"Well I have some fairly bad news for you.  Her Majesty is cracking down hard on narcotics with the might of the empire at home, as the shattering effects of opiates on Chinese are now coming to light"

"Now Now!, you imagine I have not made provision for such an eventuality.  The very Chinese about whom you speak have generously agreed to keep me supplied with every opiate under the sun, subject of course to my solving a problem they are baffled with"

"And that being?"

"Well my friends have a **3** pegs **0, 1, 2** and peg **0** has **N** disks sorted in increasing order of radius from top to bottom, peg **1** and peg **2** being empty.  They want to shift all the disks to peg **1** using the pegs so that the **N** disks are once again sorted in increasing order of radius _using the minimum number of moves_, a move meaning moving the topmost disk of a peg to the top of another peg."

"So?"

"Well the catch is that they have large goods placed on an assembly line and _the largest disk amongst the disks on a peg has to be at the bottom in any intermediate configuration_, careful calculations have shown that if that is not the case, the unhealthy pressure developed on the bottom of the peg will cause the disks to sink into it, with disastrous consequences"

## _Input_

There are multiple test cases.  First line of the input consists of an integer **n** specifying the nuber of test cases.  Each test case consists of one positive integer **N**, where **N** is the number of disks, on a single line.

## _Constraints_

**1 <= N <= 50**

## _Output_

For each test case, print the sequence of moves to get to the final configuration, one move in each line.  A move is shown by printing two integer **x, y** where the move is from peg **x** to peg **y**; **0 <= x, y <= 2**

## _Sample input_

2  
1  
2  

## _Output for sample input_

0 1  
0 2  
0 1  
2 1  

