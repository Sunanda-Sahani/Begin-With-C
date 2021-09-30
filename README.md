# Begin-With-C
#C for beginners.

Here I have given a simple program to print Hello World fot beginners. This code was written and executed on vim editor, the compiler used is gcc on Linux environment.
Just how to run this program depends on the operating system you are using. As in my case I have used UNIX operating system, so on this you need to create the program in a file whose name ends with ".c" extension such as "Hello_World.c" , then compile it with the command
      gcc Hello_World.c
If you haven't botched(mistaken) anything in yout code, the compilation will proceed silently and generate an executable file called "a.out".
If you run 
      a.out
it will print
     Hello, World!
 On the other OS rules will be different.

Now for brief explaination about the program itself. A C program, whatever it's size, consists functions and variables. A function contains statements that specift the computing operations to be done, and variable acts like a vessel which store calues used during computation.
   
1. #include <stdio.h> – This statement tells compiler to include this stdio.h file in the program. This is a standard input output file that contains the definitions of common input output functions such as scanf() and printf().

2. int main() – Here main() is the function name and int is the return type of this function. Every C program must have this function because the execution of program begins with the main() function. The 0 return value of this function represents successful execution of program while the return value 1 represents the unsuccessful execution of program. This is the reason we have return 0; statement at the end of this main function.

3. printf("Hello World"); – This function displays the content within double quotes as it is on the screen.

4. return 0; – As mentioned above, the value 0 means successful execution of main() function.

If you don't want to give any return type to main() function then you won't have to return anything to main function at the end of code. In simpler words there won't be any need to add "return 0". 
