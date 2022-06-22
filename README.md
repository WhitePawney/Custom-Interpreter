# Custom-Interpreter
Interpreter for personal language - used flex and bison - rudimentary for learning purposes.

How to compile and run the interpreter:
1)Compile the bison file > bison -y -d limbaj.y
2)Compile the flex file > flex limbaj.l
3)Compile the C files > gcc -o exec.exe lex.yy.c y.tab.c
4)Run the exec.exe file 

The inp.txt file is an example of input commands file that the interpreter can run.

"@" character is used as a printf();
