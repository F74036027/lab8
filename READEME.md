1.
Because there is a throw before the cout statement.
And that throw cause program to terminate.(an attempt
is made to rethrow an exception when there is no exception
currently being handled.)

2.
Yes.
Because the cout statement is beyond the try block.
So the program still execute after catch, then cout.

3.
How to compile: make
Execute File: tetris
Result:
	F74036027@2015cpp:~/lab8$ ./tetris
	Exception: std::bad_alloc
