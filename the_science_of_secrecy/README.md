## _Problem_
---
"Watson, have you ever heard of Prof. Moriarty?"

"You mean the famous scientific criminal as well known to the criminal world as he is unknown to the public"

"Well, Watson one of my many agents in his spider web of a network has sent me an urgent plea for help, which of course is entirely useless to both of us until I have unraveled it"

"Well, why hasn't he sent you the key?"

"A dangerous business Watson, sending both message and key under the nose of one of the most ruthless men ever to walk the Earth.  I've met my man once, and he explained his system to me, in a great hurry expecting me to figure out the details"

"The point is - He does not write in English.  He uses an alphabet of size ***K*** and each message is a string of length ***N***.  There is no information content in the message; the message tells me the value of ***K***.  A message ***A*** may be considered equivalent to another message ***B***, if -

  ***for all i, j (1 <= i, j <= N): A[i] = A[j]*** implies ***B[i] = B[j]*** and vice-versa.

For example the strings ***abbaccaa*** and ***bccbaabb*** are equivalent because, the letter ***a*** maps to ***b***, ***b*** to ***c*** and ***c*** to ***a***.

I have to find the length of the longest sequence of messages ***<A, B, C, D, E ...>*** such that, no message in the sequence is equivalent to another."

"Holmes, this system you describe is of course unknown to Prof. Moriarty and his people"

"That is what saves my agent from persecution and of course, alerts me as to what my learned friend is up to.  Once I calculate the length of the longest sequence I look up the corresponding word in Whitaker's Almanac...  Aha I have it!  Yes of course...  However first can you tell me as to how I have solved the problem above?"

## _Input_
---

There are multiple test cases in the input file.  First line of the input consistes of an integer ***n*** specifying the number of test cases.  Each of the next ***n*** lines specifies a test case consisting of two positive integers.  The length of the message ***N***, the size of the alphabet ***K***, on a single line, separated by a single speace.

## _Constraints_

***1 <= N <= 1000, 1 <= K <= 1000***

## _Output_

For each test case, print a single line containing one integer, which equals the length of the longest sequence of pair-wise non-equivalent messages modulo ***10^8***

## _Sample input_
---
2  
2 1  
3 1  

Output for sample input
---
1  
1  

