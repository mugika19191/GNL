# 📘 GNL (Get Next Line)

> Reading one line at a time, efficiently.

**Objective**:  
Implement the `get_next_line` function that reads from a file descriptor one line at a time, handling multiple FDs simultaneously.

**Skills Gained**:
- File I/O
- Static variables
- Buffer manipulation
- Memory management

**Prototype**:
```c
char *get_next_line(int fd);
