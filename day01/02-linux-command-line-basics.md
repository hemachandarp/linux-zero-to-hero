## Session 2: Linux Command Line Basics

### The Linux File System

Linux organizes files in a hierarchical directory structure. Here are some key directories:

- **/**: The root directory.  
- **/home**: Contains user directories.  
- **/etc**: Configuration files.  
- **/var**: Variable data like logs and databases.  
- **/bin** and **/usr/bin**: Executable programs.

### Basic Commands

- `pwd`: Print the current working directory.  
- `ls`: List files and directories.  
- `cd`: Change directory.  
- `mkdir`: Create a new directory.  
- `rm`: Remove files or directories.  
- `cp`: Copy files or directories.  
- `mv`: Move or rename files or directories.

---

## Hands-On Lab: Navigating the File System

### Objective

Practice basic commands to navigate and manage files.

### Steps

1. **Open the terminal.**  
2. **Use `pwd` to see your current directory.**  
3. **Use `ls` to list files in the current directory.**  
4. **Create a new directory:**

```bash
mkdir my_project
```
5. **Navigate into the Directory**

```bash
cd my_project
```

6. **Create a File**

```bash
touch hello.txt
```

7. **List the Contents of the Directory**

```bash
ls
```

8. **Delete the File**

```bash
rm hello.txt
```
