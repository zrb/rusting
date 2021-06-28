## _Problem_
---
"Brother Sherlock, the Diogenes Club, of which you know I am a proud member wants a shooting range of its own, and being men of thrift and prudence, naturally want to cut costs."

"We made good use of the soothing atmosphere of the club so far and it would be ungrateful not to help the good citizens of the Queen now, will you elaborate further?"

"Well, the owner is slightly eccentric and stipulates that the targets should be on a vertical wall at ***integral heights*** from the ground, and the shooters on the ground at ***integral distances*** from the wall, perpendicular to it.  It was also stipulated that the distance of a shooter from the wall should be less than the height of the target he is aiming at, and that no two shooters are at the same distance from the wall.

All available guns have ***fixed and integral ranges, firing accurately at the fixed range, going in straight lines.***  Low range guns are less expensive than ones with greater range.  So we need to find the minimum exact range ***R***, of the gun, so that we can prepare for exactly ***N*** shot positions, no more, no less!"

"Allow me some time to think this out, I will see you in he club on Friday..."

"So Watson what do you make of the shooting range problem?

They want us to find their minimum gun range ***R*** for exactly ***N*** shot positions.

This is surely of relevance to the mathematicians.  In short, we have to find the minimum ***R*** which can be the hypotenuse of exactly ***N*** non-congruent positive integer sided right triangles."

## _Input_
---
There are multiple test cases.  First line of the input consists of an integer ***n*** specifying the number of test cases.  Each test case consists of one positive integer ***N***, on a single line.

## _Constraints_
---
The desired value of ***R*** fits into a ***64*** bit signed integer, ***1 <= N <= 50000***.

## _Output_
---
Output ***(N + 1)*** lines per test case.
In the first line print the value of ***R***.
In the next ***N*** lines, print the ***N*** different shooter distances, one in each line, ***sorted in increasing order***.

## _Sample input_
---
2  
1  
2  

## _Output for sample input_
---
5  
3  
25  
7  
15  
