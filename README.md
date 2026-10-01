# Dynamic Student Records in C

## Project Description

A simple C program that demonstrates dynamic memory allocation for storing student records. The program uses `malloc()` to allocate memory for multiple student structures based on the number entered by the user.

## Features

- Accept the number of students dynamically
- Allocate memory using `malloc()`
- Store roll number, name, and marks
- Display all student records
- Use structures with dynamically allocated memory
- Release allocated memory using `free()`

## Technologies Used

- C
- Structures
- Dynamic Memory Allocation
- `malloc()`
- `free()`
- Pointers

## How to Run

1. Create a file named `dynamic_student_records.c`.
2. Compile the program using a C compiler.
3. Run the compiled program.

Example using GCC:

```bash
gcc dynamic_student_records.c -o dynamic_student_records
./dynamic_student_records

===== Dynamic Student Records =====
Enter number of students: 2

Enter details for Student 1
Roll Number: 101
Name: Likitha
Marks: 85

Enter details for Student 2
Roll Number: 102
Name: Anu
Marks: 90

===== Student Records =====

Student 1
Roll Number: 101
Name: Likitha
Marks: 85.00

Student 2
Roll Number: 102
Name: Anu
Marks: 90.00

Memory released successfully.

Author
M.Likitha
