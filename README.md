# Algorithms in C
Algorithms and data structures implemented in c  by following  The Algorithm Design Manual by steve skiena
Work in progress.

##Supported Data Structures

### Linked List
Supported Operations:
- insert_list : inserts as the first item into the list and moves the reference to the new item. uses malloc to create a list node.
- delete_from_list : deletes from the list and includes and updates the references and frees up the memory.
- print_list : prints the list of items in the linked list
- free_list : frees up the list of items in the linked list


### Double Linked List
- insert_dlist : inserts as the first item into the list and moves the reference to the new item. uses malloc to create a list node.
- delete_from_dlist : deletes from the list and includes and updates the references and frees up the memory.
- print_dlist : prints the list of items in the linked list
- free_dlist : frees up the list of items in the linked list



# How to use
- use the delcarations from the corresponding header files 
- write logic in main function and run 
```
make && ./present
```
- yeah, i know not that elegant but gets my work done.

# Future Todo improvements
- use cunit in the main to run and check all the functions.
