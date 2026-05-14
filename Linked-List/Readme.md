# Project #1 :- Linked List in C

#### A basic singly linked list implementation written in C to practice pointers, dynamic memory allocation, and manual memory management.

#### This project was built as the first project of my low-level programming learning journey.

---

## Features

- Create linked lists dynamically
- Insert nodes
- Traverse and print list contents

---

## Concepts Practiced

- Pointers
- Dynamic memory allocation using "malloc"
- Structs containing self-referential pointers
- Linked list traversal
- Heap vs stack memory

---

## Data Structure

#### Each node stores:

- an integer value
- a pointer to the next node

struct Node {
    int val;
    struct Node* next;
};

---

## What I Learned

This project helped me understand:

- How dynamic memory works in C
- Why linked lists use heap allocation
- Pointer traversal between nodes
- memory ownership

---

## Build and Run

gcc linked_list.c -o linkedlist
./linkedlist

---

## Future Improvements

- Doubly linked list
- standard linked list operations
- Reverse traversal
- Generic node data types
- Queue and stack implementations using linked lists

---

## Purpose

This project is part of my ongoing C programming learning series focused on understanding low-level systems concepts and data structures from first principles.