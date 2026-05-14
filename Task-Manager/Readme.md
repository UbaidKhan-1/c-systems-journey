# Project # 2 :- C Task Manager

### A command-line task manager written in C that stores tasks in memory during runtime and persists them using binary file storage.

### This project was built to practice low-level programming concepts such as structs, file handling, memory layout, and string processing in C.

---

## Features

- Add tasks
- View all tasks
- Delete tasks
- Toggle task status (Pending / Done)
- Search tasks using substring matching
- Persistent storage using binary files

---

## Concepts Practiced

- Structs and arrays of structs
- File I/O using:
  - "fopen"
  - "fread"
  - "fwrite"
  - "fclose"
- Binary file storage
#### - String handling with:
  - "fgets"
  - "strcmp"
  - "strstr"
  - "strcpy"
- Menu-driven CLI design
- In-memory state management

---

## Program Design

Tasks are stored in memory using a fixed-size array:

struct Task Tasks[500];

### Program flow:

1. Tasks are loaded from disk into memory at startup
2. All operations are performed in memory during runtime
3. Updated tasks are written back to disk before exit

---

## File Storage

The project uses binary serialization of structs for fast read/write operations.

Tasks are saved directly using:

fwrite()

and loaded using:

fread()

---

## Build and Run

gcc TaskManager.c -o taskmanager
./taskmanager

---

## Future Improvements

- Dynamic array resizing
- Priority levels
- Due dates
- Better search filtering

---

## Learning Outcome

This project helped me better understand:

- Memory organization in C
- Binary file persistence
- Input normalization and string handling

---

#### Part of a Larger Learning Series

This project is part of my ongoing C programming learning series where I build progressively more complex systems-focused projects from scratch.