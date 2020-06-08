Name: Darian W. Setyawan
ONID: 933-965-815
Section: CS 162-020
Assignment 5 Due Date: 6/7/2020

Description:

This program is an implementation of a linked list. Its purpose is to test the function that interacts with the linked list.

Instructions:

1) Extract the file using "tar -xvf assign5.tar"
   This will extract all the files within the tar file

2) Compile the program with:

make (type "make" in the command line)

3) Run the program with:

./test_linked_list

4) You will only need to press enter during this test and observe what's happening in each function.

The first function that we will test is the get_length() function.
This function serves to get the length of the current list.

The second function that we will test is the push_front() function.
This function serves to add a node at the front of the list.

The third function is the push_back() function.
This function serves to add a node at the end of the list.

The fourth function is the insert() function.
This function serves to add a node at the desired index (or position) of the list.

The fifth function is the sort_ascending() function.
This function serves to sort the list in an ascending order.
The sorting algorithm used in this function is the merge sort algorithm with time complexity of O(n log n).

The sixth function is the sort descending() function.
This function serves to sort the list in a descending order.
The sorting algorith used in this function is the merge sort algorithm with time complexity of O(n log n).

The seventh function is the count_prime() function.
This function serves to find how many prime numbers exist in the list.

The eight and the last function is the clear() function.
This function serves to delete all of the content inside the list.

Limitations:

There is no way to go back to the function before, only with restarting the program.
The program will execute the function only if you press enter when you're prompted to.
The program may run a bit slower if the list is very big.

Extra Credit:

None

Complexity analysis:

A. sort_ascending() => Merge Sort algorithm with time complexity of O(n log n)
B. sort_descending() => Merge Sort algorithm with time complexity of O(n log n)
C. count_prime() => Non-modifying sequence modifications with time complexity of O(n)
