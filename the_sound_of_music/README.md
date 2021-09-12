## _Problem_

"You know Watson, I have always been something of a connoisseur of music.  Since the good English law has denied us the company of my friend the violin virtuoso Charlie Peace, the problem he was grappling with has been left for me to solve".

"What was the problem Holmes?  Some composition left unfinished by him?"

"No, it is a trifling problem requiring a mathematical bent of mind.  Consider this - I have permutations of the first ***N*** natural numbers.  The number of times the sequence defined by a permutation increases or decreases monotonically is called its number of runs.  For example the sequence ***(4 5 6 3 1 2)*** has ***3*** runs ***(4 -> 5 -> 6)***, ***(6 -> 3 -> 1)***, ***(1 -> 2)***, sequence ***(1 2 3)*** has ***1*** run, ***(1 -> 2 -> 3)***.

Given ***N*** and the number of runs ***K*** we have to find the number of permutations having number of runs = ***K***"

"But Holmes, ..."

"The mathematical analysis of an entire series of compositions predicts this
Watson; the quality of music is being judged by the number of rises and falls in
it.  While not twisting facts to suit theories, let us first come up with a solution
to the little puzzle I have just told you about"

## _Input_

There are multiple test cases in the input file.  First line of the input consists of
and integer ***n*** specifying the number of test cases.  Each of the next ***n*** lines
specifies a test case consisting of two positive integers ***N***, ***K*** on a single line
separated by a single space.

## _Constraints_

***1 < N <= 10000, 1 <= K <= 1000***

## _Output_

For each test case, print a single line containing one integer, which equals (The number of permutations of ***(1 ... N)*** with exactly ***K*** runs) modulo ***10^8***

## _Sample input_

2  
2 1  
3 1  

## _Output for sample input_

2  
2  


