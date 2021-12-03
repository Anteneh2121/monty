# 0x19. C - Stacks, Queues - LIFO, FIFO (Monty Bytecode Interpreter)
 
   ## Learning Objectives 

   # What do LIFO and FIFO mean

    What is a stack, and when to use it

    What is a queue, and when to use it

    What are the common implementations of stacks and queues

    What are the most common use cases of stacks and queues

    What is the proper way to use global variables

  ##  Requirements

  ###  Allowed editors: vi, vim, emacs

 ###  All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=c90

  ###  All your files should end with a new line

  ###  A README.md file, at the root of the folder of the project is mandatory

  ###  Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl

  ### You allowed to use a maximum of one global variable

  ###  No more than 5 functions per file

  ###  You are allowed to use the C standard library

  ###  The prototypes of all your functions should be included in your header file called monty.h

  ###  Don’t forget to push your header file

  ###  All your header files should be include guarded

  ###  You are expected to do the tasks in the order shown in the project
     
  ###  Compiled with Ubuntu 14.04 LTS with gcc 4.8.4 using the flags -Wall -Werror -Wextra and -pedantic

  #  How to install 

   ##  $ gcc -Wall -Werror -Wextra -pedantic *.c -o monty

 | C FILE  |  Description |
| --- | --- |
| push.c  |  The opcode push pushes an element to the stack. |
| pall.c  |  The opcode pall prints all the values on the stack, starting from the top of the stack. |
|pint.c   |   The opcode pint prints the value at the top of the stack, followed by a new line |
| pop.c   | The opcode pop removes the top element of the stack. |
| swap.c  | The opcode swap swaps the top two elements of the stack. |
|add.c    | The opcode add adds the top two elements of the stack. |
| nop.c   | The opcode nop doesn’t do anything. |
| pchar.c | The opcode pchar prints the char at the top of the stack, followed by a new line.|

![ Montybytecode](https://upload.wikimedia.org/wikipedia/commons/b/b4/Hello_World_Brainfuck.png")