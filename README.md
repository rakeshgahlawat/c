# c language.

Clang is a compiler to compile source code into machine code.\
clang hello.c //C languages\
a.out //assembly output\
./a.out //current folder run

Variables - bool char double float int long string.\
Operators - + - * / %\
Printf - %c %f %i %li %s\
Conditions - if() else if() else.\
Loops - for (i = 0; i < 10; i++). while (i = 0; i < 10; i++).\
Funtion - int foo(int bar) == output funtion(input).


Compiling generally refers to 4 explicit steps preprocessing, compiling, assembling & linking.\
Preprocessing involves looking at lines that start with a #, like #include, before everything else. For example, #include <cs50.h> will tell clang to look for that header file first, since it contains content that we want to include in our program. Then, clang will essentially replace the contents of those header files into our program.\
Compiling takes our source code, in C, and converts it to assembly code. Output file is "a.out".\
The next step is to take the assembly code and translate it to instructions in binary by assembling it. The instructions in binary are called machine code, which a computer’s CPU can run directly.\
The last step is linking, where the contents of previously compiled libraries that we want to link, like cs50.c, are actually combined with the binary of our program. So we end up with one binary file, a.out or hello, that is the compiled version of hello.c, cs50.c, and printf.c.

Good programming.
1. Eliminate copy & paste.
2. Declare global variables at the top in capital letters.
3. Store a function value in variable when being used in a loop.
