# 🐧 Day 3: Navigating the Linux Landscape

![Linux](https://img.shields.io/badge/Linux-Operating%20System-yellow?logo=linux)
![Shell](https://img.shields.io/badge/Shell-CLI-black?logo=gnubash)
![Level](https://img.shields.io/badge/Level-Beginner-blue)
![OS](https://img.shields.io/badge/Operating%20Systems-Concepts-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

# 📚 Getting Started with Operating Systems

An **Operating System (OS)** is the backbone of any computer.  
It manages hardware and software resources and allows users to interact with the system.

---

# 🖥️ Types of Operating Systems

### 🏠 Desktop OS
- Windows  
- macOS  
- Linux  

### 🖧 Server OS
- Ubuntu Server  
- CentOS  
- Windows Server  

### 📱 Mobile OS
- Android  
- iOS  

### 📟 Embedded OS
Designed for specific devices such as:
- IoT devices  
- Routers  

---

# 🌍 How Operating Systems Impact Daily Life

Operating systems power:

- Personal computers
- Mobile devices
- Servers
- Internet browsing
- Gaming
- Productivity tools

---

## 📊 OS Activities Table

| Activity | OS Role |
|-----------|----------|
| Internet browsing | Runs browser |
| Gaming | Manages CPU & RAM |
| Video calls | Controls mic & camera |
| Office work | Runs applications |
| Mobile apps | Manages background apps |

---

# ⚖️ Windows vs Unix vs Linux

## 🏢 Ownership & Origin

- **Windows** → Proprietary OS developed by Microsoft  
- **Unix** → Developed in the 1970s; foundation for many OS  
- **Linux** → Open-source Unix-like OS created by Linus Torvalds  

---

## 💰 Cost & Licensing

| OS | Licensing |
|----|------------|
| Windows | Paid license |
| Unix | Licensed, often expensive |
| Linux | Free & open-source |

---

## 🔐 Security & Privacy

- Windows → Frequent malware target  
- Unix/Linux → Strong security features; widely trusted  

---

## 🖼️ User Interface

| OS | Interface Style |
|----|----------------|
| Windows | GUI-focused |
| Unix/Linux | Command-line driven (GUI optional) |

---

# 🖥️ What is a Server?

A **server** is a computer that provides services to other computers over a network.

---

# 🖥️ Desktop OS vs Server OS

| Feature | Desktop OS | Server OS |
|----------|------------|------------|
| Purpose | Personal use | Network services |
| Optimization | Multimedia & UI | Performance & stability |
| Usage | Home/Office | Data centers |

---

# 🐧 Introduction to Linux

Linux is a versatile operating system used in:

- Servers
- Desktops
- Embedded systems

It is known for:

- Stability
- Security
- Flexibility

---

# 🏗️ Architecture of Linux

1. **Kernel** → Core of the OS (manages hardware)
2. **System Libraries** → Provide system functionality
3. **System Utilities** → Management tools
4. **Shell** → Command interface
5. **Applications** → User software

---

# 💻 Understanding the Linux Prompt

Example:  [root@localhost ~]#

| Symbol | Meaning |
|--------|----------|
| root | Current login username |
| localhost | Machine name / hostname |
| ~ | Current working directory |
| # | Root user |
| $ | Normal/local user |

---

# 🛠️ Linux Basic Commands

## 👤 User & Session Commands

| Command | Description |
|----------|------------|
| tty | Show current terminal number |
| who | Show logged-in users |
| whoami | Show current username |
| logout / exit / Ctrl + D | Logout user |
| sudo -i | Switch to root user |

---

## 📂 File & Directory Commands

| Command | Description |
|----------|------------|
| pwd | Present working directory |
| cd | Change directory |
| ls | List files |
| ll | Detailed file listing |
| cat | View file content |
| clear | Clear terminal screen |

---

## 📅 Date & Calendar Commands

| Command | Description |
|----------|------------|
| cal | Current month calendar |
| cal <year> | Show full year calendar |
| cal -3 | Previous, current, next month |
| cal -j <year> | Julian calendar |
| date | Show current date & time |

---

## 🔄 System Control Commands

| Command | Description |
|----------|------------|
| reboot / init 6 | Restart system |
| poweroff / init 0 | Power off |
| shutdown | Shutdown after 1 min |
| shutdown -h now | Immediate shutdown |
| shutdown -c | Cancel shutdown |
| hostname | Show machine name |

---

# 📊 Commands to View System Information

| Command | Description |
|----------|------------|
| hostnamectl | Detailed system info |
| uname -a | OS kernel info |
| free -h | Memory usage |
| lsusb | USB devices |
| lscpu | CPU information |
| dmidecode | Hardware info (root required) |
| sudo hostnamectl set-hostname new-name | Change hostname |

---

# 📖 Helping Commands

| Command | Purpose |
|----------|----------|
| man <command> | Full manual |
| info <command> | Alternative manual |
| whatis <command> | One-line description |
| <command> --help | Short help |
| which <command> | Show command path |

---

# 🎯 Summary

- Operating Systems manage hardware and software.
- Linux is powerful, secure, and widely used in servers.
- Understanding Linux commands is essential for DevOps & Cloud.
- Mastering CLI improves system administration skills.

---

## 🚀 Next Step

Practice commands on:
- Local Linux machine
- Virtual machine
- Cloud server (AWS EC2)

---

⭐ *Keep practicing. The Linux terminal is your best friend in DevOps!*

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

# 📝 Day 7: Mastering Text Editing with VIM

![Linux](https://img.shields.io/badge/Linux-Text%20Editor-yellow?logo=linux)
![Vim](https://img.shields.io/badge/Vim-Editor-green?logo=vim)
![CLI](https://img.shields.io/badge/CLI-Terminal-black?logo=gnubash)
![Level](https://img.shields.io/badge/Level-Beginner-blue)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

# 📘 Overview of Vim and Its History

Vim (Vi IMproved) is a powerful and versatile text editor widely used in the Linux ecosystem.

It originated from the **Vi editor** and provides enhanced features like:

- Syntax highlighting
- Plugin support
- Advanced navigation commands
- High customization

---

# ❓ Why Use Vim?

- Lightweight and fast  
- Works in terminal environments (ideal for remote servers)  
- Highly extensible and customizable  

---

# 🛠️ Practical: Check & Install Vim

## 🔍 Check if Vim is installed

```bash
vim --version
```

## 📦 Install Vim (if not installed)

### Debian / Ubuntu
```bash
sudo apt install vim
```

### RHEL / CentOS
```bash
sudo yum install vim
```

---

# 🧠 Basic Concepts: Modes in Vim

Vim operates in multiple modes:

| Mode | Purpose |
|-------|----------|
| Command Mode | Default mode for navigation & commands |
| Insert Mode | For writing/editing text |
| Visual Mode | For selecting text |
| Execute Mode | For running commands using `:` |

---

# 🚀 Practical: Switching Between Modes

Open a file:

```bash
vim example.txt
```

- Starts in **Command Mode**
- Press `i` → Enter **Insert Mode**
- Press `Esc` → Return to **Command Mode**

---

# 🧭 Basic Navigation in Command Mode

Move cursor:

| Key | Direction |
|------|------------|
| h | Left |
| l | Right |
| j | Down |
| k | Up |

---

# 📌 Command Mode (Default Mode)

### 📋 Copy Commands

```
yy      → Copy single line
nyy     → Copy multiple lines
yw      → Copy single word
p       → Paste
```

---

### 🗑️ Delete Commands

```
dd      → Delete single line
ndd     → Delete multiple lines
dw      → Delete single word
```

---

### ✂️ Cut Commands

```
cc      → Cut single line
ncc     → Cut multiple lines
cw      → Cut single word
P       → Paste before cursor
```

---

### ↩️ Undo & Redo

```
u        → Undo
Ctrl + r → Redo
```

---

### 🔝 File Navigation

```
gg   → Top of file
H    → Top of page

G    → Bottom of file
L    → Bottom of page

M    → Middle of page
A    → End of current line
```

---

### 🔎 Search & Jump

```
<n>gg       → Move to nth line
:/<word>    → Search word
```

---

### ✏️ Replace Commands

```
s → Remove current character & enter Insert Mode
S → Remove current line & enter Insert Mode
```

---

# ✍️ Insert Mode (Writable Mode)

(Press `Esc` and then `i` to enter)

| Command | Action |
|----------|---------|
| i | Insert at cursor |
| I | Insert at start of line |
| a | Insert after cursor |
| A | Insert at end of line |
| o | Insert new line below |
| O | Insert new line above |
| r | Replace single character |
| R | Replace multiple characters |

---

# 🎯 Conclusion

Mastering Vim requires:

- Understanding its modes
- Practicing navigation commands
- Memorizing frequently used shortcuts

Experiment with the commands above to build confidence.

---

⭐ The more you practice Vim, the faster and more efficient you become in Linux.

# Day 8: The Editor's Lair: Mastering Text Editing with VIM

## Entering Execute Mode
Execute Mode allows you to run commands for file operations, searching, and other advanced functionalities. To enter Execute Mode, press:
```
:
```

### Practical:
1. Open Vim:
   ```
   vim example.txt
   ```
2. Enter Execute Mode and save the file:
   ```
   :w
   ```
3. Quit Vim:
   ```
   :q
   ```
4. Combine commands to save and quit:
   ```
   :wq
   ```

## Executing Basic Commands: File Operations, Searching, Line Numbering
### File Operations
- Save the file:
  ```
  :w
  ```
- Save as a new file:
  ```
  :w newfile.txt
  ```
- Quit Vim:
  ```
  :q
  ```
- Force quit without saving:
  ```
  :q!
  ```

### Searching
- Search for a term:
  ```
  /search_term
  ```
- Search backward:
  ```
  ?search_term
  ```
- Navigate search results:
  - Next occurrence: `n`
  - Previous occurrence: `N`

### Line Numbering
- Show line numbers:
  ```
  :set number
  ```
- Hide line numbers:
  ```
  :set nonumber
  ```

### Practical:
1. Search for the term "example" in a file.
2. Enable line numbering and locate specific lines.

## Entering Visual Mode
Visual Mode allows for text selection and manipulation. To enter Visual Mode, press:
- Character-wise selection:
  ```
  v
  ```
- Line-wise selection:
  ```
  V
  ```
- Block selection:
  ```
  Ctrl + v
  ```

### Practical:
1. Open a file in Vim.
2. Use `v` to select a word or character sequence.
3. Use `V` to select a full line.
4. Use `Ctrl + v` to select a rectangular block of text.

## Manipulating Text in Visual Mode
Once text is selected in Visual Mode, you can manipulate it:
- Copy text:
  ```
  y
  ```
- Delete text:
  ```
  d
  ```
- Paste text:
  ```
  p
  ```
- Replace selected text:
  1. Select the text.
  2. Press `c` to clear and enter Insert Mode.
  3. Type the replacement text and press `Esc`.


