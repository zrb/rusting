## _Problem_
---
"Often the best relaxation a mind can have is a change of work.  That is why I have given my brain a thorough rest by plunging it into a chemical analysis before returning to the problem of Sholtos.  However, there is this problem the solution to which has for sometime eluded me, perhaps both of us can tackle it together"

"You perhaps refer to the problem of the hieroglyphics found in both Capt. Morstan and Major Sholto's rooms"

"Ah No!  It is about the chemical synthesis of the reagent instead.  Consider this model to start with- a set of tasks is to be performed

Each task is of unit duration and has a deadline of an integral number of units from start time ***T=0***.  All tasks can be started at *T=0* and earn an associated profit if completed within the deadline.  Profits from completed tasks add up.  It is desired to maximize the profit earned by ***selecting tasks for execution one at a time***."

"This is of relevance to the mathematicians certainly?"

"Hardly that!  Watson, hardly that!  Chemicals of certain purity and concentration can be extracted if done within a certain time.  It is of utmost relevance to me to decide which reactions to catalyze, in order to obtain the reagent with highest purity"

## _Input_
---
The input file consists of multiple test cases.  First line of the input consists of an integer ***n*** specifying the number of test cases.  Each test case that follows is in the following format:

A single integer, ***n***, on a line, followed by ***n*** lines, each containing ***3*** integers ***p***, ***d***, ***q*** indicating that there are ***q*** tasks, each of which pays a profit ***p*** if completed within time ***d***.  You can treat these tasks as independent, in that you get a profit of ***i * p***, should you choose to execute only ***i***  of these ***q*** available tasks, within the deadline ***d***.  ***(i <= q)***.

## _Constraints_
---
***1 <= n <= 1000, 1 <= d <= 1,000,000***

## _Output_
___
For each test case, print a single line containing one integer, which equals the maximum profit attainable

## _Sample input_
___
2  
1  
5 10 10  
2  
5 10 10  
6 1 2  

## _Output for sample input_
---
50  
51  

