Selection Sort on Linked List

This repository contains a Java implementation of the Selection Sort algorithm applied to a singly linked list. The code reads a list of integers from an input file, sorts them using the selection sort method, and writes the sorted list to an output file.

Features:

Linked List Implementation: The program uses a custom linked list class to store and manage the list of integers.
Selection Sort: The linked list is sorted using the selection sort algorithm, which iteratively selects the smallest element from the unsorted portion of the list and swaps it with the first unsorted element.
File I/O: The program reads integers from an input file (num.txt) and writes the sorted integers to an output file (ascended_num.txt).
How It Works

Input: The program reads a list of integers from num.txt. The integers should be separated by commas.
Insertion: Each integer is inserted into a linked list.
Sorting: The linked list is sorted using the selection sort algorithm.
Output: The sorted list is written to ascended_num.txt in a comma-separated format.
Files

LinkedList.java: Contains the LinkedList class, which implements a singly linked list and methods to insert elements and display the list.
SelectionSort.java: Contains the SelectionSort class with the main method. It orchestrates the reading of input, sorting of the linked list, and writing of the output.

How to Run:
Set Up: Make sure you have Java installed on your system.
Input File: Create a num.txt file in the project directory with a list of integers separated by commas. 
Example:
5,3,8,1,2,7
Compile and Run:
java SelectionSort.java
Output File: After running the program, check the ascended_num.txt file in the project directory for the sorted list.

Example:
Input (num.txt):
5,3,8,1,2,7
Output (ascended_num.txt):
1,2,3,5,7,8
