1261 - K-SAT Problem

First take everyone's wishes. you can do it in a 2D array or vector
That may be an n*k 2D array
negative numbers means rejected numbers or rejected wish
positive number means accepted numbers

then take the numbers that are taken

then compare with everyone's wishes....(can easily be done with nested for loops)

the numbers that are taken, does they satisfy everyone's wishes??

check if it is valid or nor.

For example I am output for this

1

3 4 2

+1 -2

+3 +4

-3 -1

1 4   // here 1 indicates how many values are taken

the number(s) taken is 4

First person's wish "you can accept 1 or reject 2"
-> only 4 is taken so, you rejected 2 that means wish has been satisfied

Second person's wish "you can accept 3 or accept 2"
-> 4 is taken that means wish has been satisfied

Third person's wish "you can reject 3 or reject 1"
-> only 4 is taken so, you rejected both 3 and 1 that means wish has been satisfied

the solution satisfied wishes of 3 of them

So the answer is Yes

For this testcase

1

1 5 3

+1 -2 +4

2 2 5 

we take 2 and 5 

but the wish was to take 1 or 4 or to reject 2
the solution does none

So the answer is No.
