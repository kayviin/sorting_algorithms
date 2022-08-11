C - Sorting algorithms & Big O
In this project, I implemented several different sorting algorithms.

Tests 
tests: Folder of test files.

Helper Files 🙌
print_array.c: C function that prints an array of integers.
print_list.c: C function that prints a listint_t doubly-linked list.

Header Files 
sort.h: Header file containing definitions and prototypes for all types and functions written for the project.
Data Structure:

typedef struct listint_s
{
	const int n;
	struct listint_s *prev;
	struct listint_s *next;
} listint_t;
