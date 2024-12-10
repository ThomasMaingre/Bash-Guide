# 📚 Bash Man Pages - A beginner's guide 📚

👤 **Authors:** Ballochi Timoté, El-Sayed Basim, Maingre Thomas & Soilihi Kyllian

---


## 🤔 What are Bash Man Pages?

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
  ```


## 🔎 Examples of classic bash commands

## 📕 1. `cd` Command
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



## 📗 2. `ls` Command
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



## 📘 3. `mkdir` Command
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

## 💻 Common Linux Commands
```bash
man man
man ssh
man cp
man ls
```

Example:
```bash
man cp

NAME
    cp - copy files

SYNOPSIS
    cp [-R [-H | -L | -P]] [-f | -i | -n] [-aclNpSsvXx] source_file target_file
    cp [-R [-H | -L | -P]] [-f | -i | -n] [-aclNpSsvXx] source_file ... target_directory
    cp [-f | -i | -n] [-aclNPpSsvXx] source_file target_file
    cp [-f | -i | -n] [-aclNPpSsvXx] source_file ... target_directory
```

The square brackets `[]` show optional arguments, and the pipes `|` mean you can choose only one option. The ellipses `...` indicate you can use multiple files or inputs.

Create a script for deploy

### Connect to the Server via SSH

- Use the SSH command to securely log in to the remote server.
- Replace `username` with your server's username and `server_ip` with the server's IP address:

```bash
ssh username@server_ip
```

Create the script
`nano /path/to/project/deploy.sh`

Content of the script
```bash
#!/bin/bash

# Project directory

PROJECT_DIR="/path/to/project"

# Navigate to the project directory

cd $PROJECT_DIR

# Pull the latest changes

echo "Pulling latest changes..."
git pull origin main

# Install dependencies

echo "Installing dependencies..."
npm install

# Build the application

echo "Building the application..."
npm run build

# Restart the application with PM2

echo "Restarting application..."
pm2 restart app-name

echo "Deployment completed!"
```

Execute the script
`/path/to/project/deploy.sh`



## 😊 Conclusion
Bash Man Pages are indispensable for anyone working in a Unix-based environment. Commands like `cd`, `ls`, and `mkdir` are foundational, and understanding how to access their documentation helps improve productivity and problem-solving skills.

## 🏋️‍♂️ Practice as you want!

If you want to better understand Bash, you just need to practice it over and over again, so here are some links that might help you!

- <a href="https://www.codecademy.com/catalog/language/bash">CodeCademy</a>
- <a href="https://www.youtube.com/watch?v=tK9Oc6AEnR4">Tuto</a>
