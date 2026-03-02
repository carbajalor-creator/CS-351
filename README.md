# CS-351
The awesomest computer architecture class
* Project 1

1. Which program is fastest? Is it always the fastest?
The program that is faster is alloca.cpp because it uses stack allocation rather than heap allocation which is significantly faster.

2. Which program is slowest? Is it always the slowest?
The slowest would be list.cpp because it uses multiple heap allocations per node making it slower than the rest of the programs. 

3. Was there a trend in program execution time based on the size of data in each Node? If so, what, and why?
4. Was there a trend in program execution time based on the length of the block chain?
5. Consider heap breaks, what's noticeable? Does increasing the stack size affect the heap? Speculate on any similarities and differences in programs?
Increasing the stack size doesn't affect the heap because they are separate spaces for holding memory.

6. Considering either the malloc.cpp or alloca.cpp versions of the program, generate a diagram showing two Nodes. Include in the diagram
the relationship of the head, tail, and Node next pointers.
show the size (in bytes) and structure of a Node that allocated six bytes of data
include the bytes pointer, and indicate using an arrow which byte in the allocated memory it points to.
7. There's an overhead to allocating memory, initializing it, and eventually processing (in our case, hashing it). For each program, were any of these tasks the same? Which one(s) were different?
Yes for alloca.cpp and malloc.cpp they allocated nodes in a similar way. 

8. As the size of data in a Node increases, does the significance of allocating the node increase or decrease?
