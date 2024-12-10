# Bash Man Pages - A beginner's guide

**Authors:** Ballochi Timoté, El-Sayed Basim & Maingre Thomas

---

## What are Bash Man Pages?

Bash Man Pages are manual pages available on Unix-based systems that provide detailed documentation for commands, utilities, and programs. They are an essential tool for developers, system administrators, and anyone using the command line.


- **Who?**  
  Bash Man Pages are designed for Unix and Linux users who want to understand command-line tools.

- **What?**  
  They provide a reference for command syntax, options, and use cases.

- **Why?**  
  They are essential for efficient navigation and problem-solving in Unix environments.

- **How?**  
  Use the `man` command followed by the name of the command to open its manual page.  
  Example:  
  ```bash
  man ls


## Examples of classic bash commands

## 1. `cd` Command
The `cd` command is used to change the current directory.

### Usage:
```bash
cd [directory_path]
```

### Example 1: Changes the current directory to /home/user/documents.
```bash
cd /home/user/documents
```

### Example 2: Moves up one level to the parent directory.
```bash
cd ..
```



## 2. `ls` Command
The `ls` command lists the contents of a directory.

### Usage:
```bash
ls [options] [directory]
```

### Example 1: Lists the files and directories in the current directory.
```bash
ls
```

### Example 2: Displays detailed information about the files in /home/user.
```bash
ls -l /home/user
```



## 3. `mkdir` Command
The `mkdir` command creates new directories.

### Usage:
```bash
mkdir [directory_name]
```

### Example 1: Creates a directory named new_folder.
```bash
mkdir new_folder
```

### Example 2: Creates the entire directory path if it does not exist (-p flag).
```bash
mkdir -p /home/user/projects/new_project
```



## Conclusion
Bash Man Pages are indispensable for anyone working in a Unix-based environment. Commands like `cd`, `ls`, and `mkdir` are foundational, and understanding how to access their documentation helps improve productivity and problem-solving skills.
