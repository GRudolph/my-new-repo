# Week 7

## Topic: Dynamic Memory Allocation

### Activities
- [ ] Review the slides on Dynamic Memory Allocation
- [ ] Read chapter 7 in Big C++
- [ ] Review the sample code on Dynamic Arrays
- [ ] Complete lab #7
- [ ] Complete project #4 and submit to Canvas before 11:59pm Sunday night (20% deduction per day late)
- [ ] Take the 2nd exam

### Learning Objectives
By the end of this unit, you should be able to:
- Describe the use of the data segment, the stack and the heap to store variables
- Explain where global variables, local variables, and dynamic variables are stored
- Explain how dynamic variables are created
- Correctly create and use dynamic variables in a program
- Correctly allocate dynamic storage for an array
- Explain what a memory leak is
- Write programs that do not have memory leaks
- Explain the use of the delete operator

### Reading Assignment
Before you come to class this week carefully review the slides on Dynamic Memory Allocation and read chapter 7 in Big C++.

### Important Concepts
1. Global variables are stored in the program's data segment
2. Local variables are stored on the run-time stack
3. Dynamic variables are stored on the heap
4. The **new** operator allocates storage on the heap. It returns an address to the first byte of storage allocated
5. If dynamically allocated storage is not released when the program has finished with it, the program has a **memory leak**, and may crash after some time has passed
6. Dynamically allocated memory is released using the **delete** operator
7. If the new operator is used with [ ] to allocate an array of values, then you must use the [ ] with delete. Otherwise you will only delete the first element of the array

### Lab Assignment
This week you should complete lab #7, where you will design a class for a Vector of integers.

### Project
Complete and submit project #4. In this project you will create a class for a Vector of integers, using dynamically allocated arrays. 