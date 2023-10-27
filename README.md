# Linked-list



NAME: Mohamad Saad Ansar Bijapuri
PRN: 22070123070


Title:Linked lists

Aim: To learn Object oriented programming in C++

Theory: A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. The elements in a linked list are linked using pointers.
In simple words, a linked list consists of nodes where each node contains a data field and a reference(link) to the next node in the list.


Linked lists have a few advantages over arrays:

1) Items can be added or removed from the middle of the list
2) There is no need to define an initial size


However, linked lists also have a few disadvantages:

1) There is no "random" access - it is impossible to reach the nth item in the array without first iterating over all items up until that item. This means we have to start from the beginning of the list and count how many times we advance in the list until we get to the desired item.
2) Dynamic memory allocation and pointers are required, which complicates the code and increases the risk of memory leaks and segment faults.
3) Linked lists have a much larger overhead over arrays, since linked list items are dynamically allocated (which is less efficient in memory usage) and each item in the list also must store an additional pointer.
4) ![image](https://github.com/M-S-A-B/Linked-list/assets/140503259/7e7af880-7650-4c7a-b3c6-77debc083477)

