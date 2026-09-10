### Assignment 1: Basics of Pointers

In this task, I learned the basic idea behing the pointers and how they store memory addresses. I noted that the `&` operator gives the address of a variable, while the `*` operator allows us to access or change the value stored at that address. What I found interesting was that changing the value through the pointer also changes the original variable because the pointer refers directly to its location in memory.

### Assignment 2: Pointer Arithmetic

In this task, I learned how pointers can be used to move through an array. I noted that `*(ptr + i)` gives the same value as `array[i]`. An interesting part was that increasing an integer pointer with `ptr + 1` moves it to the next integer in the array, rather than simply moving one byte. I also saw that modifying elements through the pointer directly modifies the original array.

### Assignment 3: Pointers and Functions

This task showed me how pointers can be passed to functions to modify the original variables. Normally, C passes values to functions as copies, but by passing their addresses with `&`, the function can access the original values. The interesting part was the `swap()` function because it demonstrates clearly why pointers are useful: the two variables can be changed inside another function without returning them.

### Assignment 4: Pointers to Pointers

In this task, I learned about double pointers. A normal pointer stores the address of a variable, while a double pointer stores the address of another pointer. I noted that `*ptr` accesses the integer value, while `**doublePtr` requires two dereferences to reach the same value. What I found interesting was the chain of references: `doublePtr` points to `ptr`, and `ptr` points to the actual integer.

### Assignment 5: Strings and Character Pointers

This task helped me understand how strings work with pointers in C. Since a string is an array of characters, a character pointer can start at the first character and move through the string using `ptr++`. I noted that the special character `'\0'` indicates the end of the string. The interesting part was that I could both print the string and calculate its length without using array indexing such as `str[i]`, only pointer arithmetic.
