# 🐧 Day 4: Mastering the Linux Prompt

![Linux](https://img.shields.io/badge/Linux-CLI-yellow?logo=linux)
![Shell](https://img.shields.io/badge/Bash-Terminal-black?logo=gnubash)
![Level](https://img.shields.io/badge/Level-Beginner-blue)
![Practice](https://img.shields.io/badge/Hands--On-Practice-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

# 💻 Understanding the Linux Command Prompt

The Linux command prompt is a powerful interface used to interact with the operating system.

Typical structure: username@hostname:~$

---

## 🔎 Key Components

| Component | Meaning |
|------------|----------|
| username | Current logged-in user |
| hostname | Computer name |
| ~ | Home directory |
| $ | Standard user |
| # | Root user |

---

# 🧠 Decoding the Command Prompt

Understanding prompt elements helps you navigate effectively.

| Symbol/Command | Purpose |
|----------------|----------|
| `~` | User's home directory |
| `pwd` | Show current directory |
| `whoami` | Show current user |
| `hostname` | Show machine name |

---

# 🚀 Effective Command Prompt Usage

## 📂 Navigating Directories

```bash
cd        # Change directory
ls        # List files
pwd       # Print working directory
cd ..     # Go back one directory
cd ~      # Go to home directory

## 📂 Managing Files

touch filename      # Create empty file
mkdir dirname       # Create directory
rm filename         # Delete file

## 📌 Linux Basic Commands

## 1️⃣ Navigation Commands

```bash
pwd
ls
cd /etc
cd ..
cd ~
---

## 2️⃣ File & Directory Commands

```bash
mkdir test
touch file1.txt
ls
rm file1.txt
rmdir test

##  Viewing Files

```bash
cat /etc/os-release

## 📊 Essential System Information Commands

```bash
🖥️ CPU, Memory & Disk
top
free -h
df -h
uptime

## 👤 OS & User Info

```bash
uname -a
whoami
hostname
date

## 🛠️ System Information Commands Explained

```bash
Command	Description

```bash
uname -a	System details
df -h	Disk usage
top	Live process monitoring
free -m	Memory usage
who	Logged-in users


```

## 📂 Creating Files Inside a Directory (from Root)


```bash
touch /home/<username>/<filename>

🔢 Create Multiple Files at Once
touch linux{1..10}.txt


OR

touch linux1.txt linux2.txt

🗑️ Delete All at Once
rm -f linux*

📍 Create Files in Different Locations
touch /mnt/file1.txt /media/file2.txt


Delete forcefully:

rm -f /mnt/file1.txt /media/file2.txt

## 📁 Directory Creation
➤ Create Single Directory in Root
mkdir /dir1

➤ Create Multiple Directories
mkdir /root/{demo,data,practice}
mkdir /session{1..10}

➤ Delete Multiple Directories
rmdir session*

➤ Create Directories in Different Locations
mkdir /root/dir2 /mnt/dir3 /media/dir3

## 🗑️ Deleting Directories with Files Inside
rm -r directory_name

## 🔑 Important Options
Option	Meaning
-r	Recursive delete (includes files inside directory)
-f	Force delete (no confirmation)
-v	Verbose (shows what's happening)

## Example:

rm -rfv directory_name

## 📌 Difference Between rmdir and rm
Command	Works On
rmdir	Empty directories only
rm -r	Directories with files


## 🎯 Summary


```bash

The Linux prompt is a powerful tool for system control.

Understanding the prompt structure improves efficiency.

Mastering file and directory commands is essential.

System monitoring commands help in administration tasks.

Recursive and force options allow advanced deletion operations.


```

---
# 🐧 Day 5: Delving Deep into the Linux File System

![Linux](https://img.shields.io/badge/Linux-File%20System-yellow?logo=linux)
![CLI](https://img.shields.io/badge/CLI-Commands-black?logo=gnubash)
![Level](https://img.shields.io/badge/Level-Beginner-blue)
![Practice](https://img.shields.io/badge/Hands--On-Practice-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

# 📂 Navigating the File System

Understanding how to navigate the Linux file system is fundamental to using the operating system effectively.

The Linux file system is organized as a hierarchy, starting from the root directory:

```
/
```

---

## 🔑 Key Commands for Navigation

### 📍 pwd
Prints the current working directory.

### 📁 cd
Changes the current directory.

```bash
cd /home/user
cd ..
cd -
```

### 📄 ls
Lists the contents of a directory.

```bash
ls -l
ls -a
```

---

# 📁 File and Directory Management

## 🆕 Creating Files and Directories

```bash
touch filename
mkdir dirname
```

---

## ✏️ Editing Files

### nano

```bash
nano filename
```

Save → Ctrl + O  
Exit → Ctrl + X  

### vim

```bash
vim filename
```

Press `i` → Insert mode  
Press `Esc` → Exit insert mode  
Type `:wq` → Save and quit  

---

# 📌 Commands for Working with Files & Directories

| Command | Description |
|----------|------------|
| pwd | Present working directory |
| cd | Change directory |
| ls | List files |
| ll | Detailed file listing |
| cat | View file content |
| cp | Copy file |
| mv | Move / Rename |
| mkdir | Create directory |
| rmdir | Delete empty directory |
| rm | Delete file/directory |
| locate | Search |
| find | Advanced search |
| sudo | Admin privileges |
| head | First 10 lines |
| tail | Last 10 lines |
| echo | Save data into file |

---

# ⌨️ Linux Shortcuts

Tab → Auto-complete  
Ctrl + C → Cancel process  
Ctrl + Z → Suspend process  
Ctrl + D → Logout  
Ctrl + L → Clear terminal  
Ctrl + A → Move to beginning  
Ctrl + E → Move to end  
Ctrl + U → Delete to beginning  
Ctrl + W → Delete word  
Ctrl + Y → Paste  
Ctrl + P → Previous command  
Ctrl + R → Reverse search  

---

# 📖 READ Operations

## cat
```bash
cat <file_name>
```

## more
```bash
more <file_name>
```

## less
```bash
less <file_name>
```

## head
```bash
head <file_name>
head -n 15 <file_name>
```

## tail
```bash
tail <file_name>
tail -n 15 <file_name>
```

## sort
```bash
sort <file_name>
sort -r <file_name>
```

---

# 🚚 MOVE Operation

```bash
mv <source> <destination>
```

Move example:

```bash
mv /root/anaconda /mnt/
mv /root/* /mnt
```

Rename directory:

```bash
mv dir1 dir2
```

Rename file:

```bash
mv file1.txt file2.txt
```

---

# 📋 COPY Operation

```bash
cp <source> <destination>
```

Options:
- -f → force
- -v → verbose
- -r → recursive

Examples:

```bash
cp -r /etc /mnt/etc-bkp
cp /root/* /media
cp -rv file1.txt file2.txt /mnt
```

---

# 🗑️ Deleting Files

```bash
rm filename
rm -i filename
rm -r directory
rm -rf directory
```

---

# 🎯 Conclusion

Mastering Linux file system commands makes navigation and file management efficient.

Practice daily to build confidence and improve speed.

⭐ Keep practicing Linux commands!

