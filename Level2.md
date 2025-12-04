## 🎯 Level Goal: Read a file with a tricky name

This time, the password is stored in a file called `-`.  
Yep, just a single dash. That’s unusual because `-` is often used in Linux commands to mean **standard input/output**.  
So, if you try `cat -`, it won’t work the way you expect.

---
# Linux File System Overview

In operating systems like Windows or macOS, you may be familiar with the concept of **folders**, which are used to organize files. In Linux, the equivalent term is **directory**.

## Root Directory

- The **root directory** is the starting point of the Linux file system.
- It is represented by a single forward slash `/`.
- All other directories and files in the system are contained within this root directory.

## Hierarchical Structure

Think of the Linux file system as an **inverted tree**:

- At the very top is the **root directory (`/`)**.
- Branching down from it are other directories (like `/home`, `/etc`, `/usr`, etc.).
- Each directory can contain files or more subdirectories, forming a nested structure.
---

### 🛠️ The Problem
Normally, `cat <filename>` shows the contents of a file.  
But here, the filename itself looks like an **option** (since most commands use `-` to start flags).  
We need a way to tell the system: “Nope, this is actually a file name.”

---

### 💡 The Solution
You can use `pwd` command to locate the directory you are working on.
Specify the location while using `cat` command.

# Example:
<br>```cat ./-```
<br>
<br> In the above command `./` Is the home directory represents location of the file and `-` is our filename.
