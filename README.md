# SUMMER TRAINING 
# DAY 1
# introduction to linux
ques. what is operating 
An Operating System (OS) is system software that acts as an interface between the user and the computer hardware. It manages all the hardware and software resources of a computer and provides services for running application programs
Functions of an Operating System
Manages the CPU (processor).
Manages memory (RAM).
Manages files and folders.
Manages input and output devices (keyboard, mouse, printer, etc.).
Runs application programs.
Provides security and user management
ques. uses of operating system
Uses of an Operating System
Provides User Interface – Allows users to interact with the computer through a GUI or CLI.
Manages Memory – Allocates and deallocates RAM to running programs.
Manages CPU – Schedules and controls the execution of processes.
Manages Files – Creates, stores, organizes, and deletes files and folders.
Controls Input/Output Devices – Manages devices such as the keyboard, mouse, printer, and monitor.
Runs Applications – Loads and executes software programs.
Provides Security – Protects data using user accounts, passwords, and permissions.
Supports Multitasking – Allows multiple applications to run at the same time.
Manages Storage – Organizes and controls data on hard disks and SSDs.
Supports Networking – Enables communication and resource sharing over a network.
Conclusion

An operating system makes the computer easy to use by managing hardware, software, files, memory, and devices while providing a secure and efficient environment for running applications.

vitual box and difference between virtual box and vm ware
# VirtualBox

Oracle VM VirtualBox (commonly called VirtualBox) is free and open-source virtualization software developed by Oracle Corporation. It allows you to create and run virtual machines (VMs) on a single physical computer. Each virtual machine can run a different operating system, such as Windows, Linux, or other operating systems, without affecting the host operating system.

# Uses of VirtualBox
Install multiple operating systems on one computer.
Test software and applications safely.
Learn Linux without changing the main operating system.
Create isolated environments for development and testing.
Take snapshots to restore the virtual machine to an earlier state.
Difference Between VirtualBox and VMware
Feature	Oracle VM VirtualBox	VMware Workstation
Developer	Oracle Corporation	VMware
Cost	Free and open-source	Free (Player) and Paid (Pro) versions
Performance	Good	Generally faster and better performance
Ease of Use	Easy for beginners	Easy, with more advanced features
Operating Systems Supported	Windows, Linux, macOS, Solaris	Windows and Linux (host support varies by edition)
Snapshots	Supported	Supported (more advanced in Pro edition)
Best For	Students, learning, and basic virtualization	Professional development, testing, and enterprise use
Conclusion
VirtualBox is the best choice for students and beginners because it is free and easy to use.
VMware is preferred by professionals and enterprises because it offers better performance and more advanced virtualization features.
File and Directory Permissions in Linux

File and directory permissions in Linux determine who can read, write, or execute a file or directory. They help protect data and control access to system resources.
# Installations steps
Part A: Install VirtualBox
Download and install Oracle VM VirtualBox from the official website.
Run the installer and click Next.
Choose the installation location.
Select the required features and click Next.
Click Install.
Wait for the installation to complete.
Click Finish to launch VirtualBox.
# day 2 
# introduction to bash and linux command line essential 
# shell and BASH 
Shell (5 Points)
A Shell is a command-line interface that allows users to interact with the operating system.
It accepts commands from the user and executes them.
It acts as an interface between the user and the Linux kernel.
It supports scripting to automate repetitive tasks.
Examples of shells include Bash, Sh, C Shell (csh), Korn Shell (ksh), and Z Shell (zsh).
Bash (5 Points)
Bash (Bourne Again Shell) is the default shell in many Linux distributions.
It was developed as an improved version of the Bourne Shell (sh).
Bash supports command history, tab completion, and command-line editing.
It is widely used for writing shell scripts to automate system administration tasks.
Bash is free, open-source, and user-friendly, making it the most commonly
# Types of Permissions
Read (r) – Allows viewing the contents of a file or listing a directory.
Write (w) – Allows modifying a file or creating/deleting files in a directory.
Execute (x) – Allows running a file as a program or accessing a directory.
Permission Categories
User (u) – The owner of the file.
Group (g) – Users who belong to the file's group.
Others (o) – All other users.
Permission Example
-rwxr-xr--
User (Owner): rwx = Read, Write, Execute
Group: r-x = Read, Execute
Others: r-- = Read only
Useful Commands
ls -l → Display file and directory permissions.
chmod → Change permissions.
chown → Change file owner.
chgrp → Change file group.
# Importance
Protects files from unauthorized access.
Controls who can read, modify, or execute files.
Improves system security.
Prevents accidental deletion or modification of important files.
linux file system structure
Linux File System Structure

The Linux file system structure is a hierarchical directory structure that starts from the root directory (/). All files and directories are organized under this single root.

# Linux File System Structure
/
├── bin
├── boot
├── dev
├── etc
├── home
├── lib
├── media
├── mnt
├── opt
├── proc
├── root
├── run
├── sbin
├── srv
├── sys
├── tmp
├── usr
└── var
# Important Directories
# Directory	Purpose
/	Root directory; the top-level directory of the Linux file system.
/bin	Essential user commands (e.g., ls, cp, mv).
/boot	Boot loader files and Linux kernel.
/dev	Device files such as disks, keyboard, and printer.
/etc	System configuration files.
/home	Home directories of users.
/lib	Essential shared libraries required by system programs.
/media	Mount point for removable media (USB drives, CDs/DVDs).
/mnt	Temporary mount point for file systems.
/opt	Optional third-party software packages.
/proc	Virtual file system containing process and kernel information.
/root	Home directory of the root (administrator) user.
/run	Runtime system information.
/sbin	System administration commands.
/srv	Data for services provided by the system.
/sys	Information about hardware devices and the kernel.
/tmp	Temporary files.
/usr	User applications, libraries, and documentation.
/var	Variable data such as logs, cache, and mail.

# basic linux file operations  (rm,mv,ls,cp)
Basic Linux File Operations
1. ls (List Files and Directories)

Purpose: Displays the files and directories in the current directory.

Syntax:

ls

Example:

ls
2. cp (Copy Files)

Purpose: Copies a file or directory from one location to another.

Syntax:

cp source_file destination_file

Example:

cp file1.txt file2.txt

This creates a copy of file1.txt named file2.txt.

3. mv (Move or Rename Files)

Purpose: Moves a file to another location or renames it.

Syntax:

mv source destination

Examples:

Rename a file:

mv file1.txt newfile.txt

Move a file to another directory:

mv file1.txt Documents/
4. rm (Remove Files)

Purpose: Deletes files or directories.

Syntax:

rm filename

Example:

rm file1.txt

Delete a directory and its contents:

rm -r myfolder
Summary Table
Command	Full Form	Purpose
ls	List	Displays files and directories
cp	Copy	Copies files or directories
mv	Move	Moves or renames files/directories
rm	Remove	Deletes files or directories
# DAY 3
# linux installations
A Linux ISO is a disk image file that contains all the files needed to install a Linux operating system. Before installation, it is important to download the ISO from the official website and verify its integrity to ensure that the file is complete and has not been modified or corrupted.
# Steps to Download a Linux ISO
Visit the official website of the Linux distribution (e.g., Ubuntu).
Choose the required version of the operating system.
Download the ISO image file.
Save the ISO file to your computer
# bash scripting
Bash scripting is the process of writing a series of commands in a text file (called a shell script) that are executed automatically by the Bash (Bourne Again Shell). It is used to automate repetitive tasks, manage files, and perform system administration in Linux.
Basic Structure of a Bash Script
#!/bin/bash

echo "Hello, World!"
Steps to Run a Bash Script

Create a file:

nano script.sh
Write the Bash script and save the file.

Make the script executable:

chmod +x script.sh

Run the script:

./script.sh
# Basic conditional statement 
if Statement
#!/bin/bash

num=10

if [ $num -gt 5 ]
then
    echo "Number is greater than 5"
fi
2. if...else Statement
#!/bin/bash

num=3

if [ $num -gt 5 ]
then
    echo "Number is greater than 5"
else
    echo "Number is 5 or less"
fi
3. if...elif...else Statement
#!/bin/bash

marks=75

if [ $marks -ge 90 ]
then
    echo "Grade A"
elif [ $marks -ge 60 ]
then
    echo "Grade B"
else
    echo "Grade C"
fi
# working with test processing tools
grep Program
#!/bin/bash

echo "apple
banana
apple pie
orange" > fruits.txt

grep "apple" fruits.txt
awk Program
#!/bin/bash

echo "Pranjal 85
Rahul 90
Aman 78" > marks.txt

awk '{print $1, $2}' marks.txt
sed Program
#!/bin/bash

echo "Linux is good" > file.txt

sed 's/good/great/' file.txt
# file Compression 
File Compression Using gzip
#!/bin/bash

echo "This is a sample file." > sample.txt

gzip sample.txt

ls
File Compression Using tar
#!/bin/bash

mkdir myfolder
echo "File 1" > myfolder/file1.txt
echo "File 2" > myfolder/file2.txt

tar -cvf myfolder.tar myfolder

ls
File Compression Using zip
#!/bin/bash

echo "This is a sample file." > sample.txt

zip sample.zip sample.txt

ls
# DAY 4
# PC AND NETWORKING 
# common pc boot issues and solutions 
Common PC Boot Issues and Solutions
Boot Issue	Possible Cause	Solution
PC does not turn on	Power supply or loose power cable	Check the power cable, power switch, and PSU connections.
Black screen on startup	Loose RAM, GPU, or monitor cable	Reseat the RAM and GPU, and check monitor connections.
Operating System Not Found	Missing or damaged operating system	Check the boot order in BIOS/UEFI and reinstall the operating system if necessary.
Boot Device Not Found	HDD/SSD not detected	Check SATA or NVMe connections and ensure the drive is detected in BIOS/UEFI.
Continuous reboot or boot loop	Corrupt system files or faulty hardware	Boot into Safe Mode or use Startup Repair; test RAM and storage.
Blue Screen (BSOD)	Driver issues, hardware failure, or corrupt files	Note the error code, update drivers, and check RAM and storage.
Slow boot	Too many startup programs or a failing HDD	Disable unnecessary startup programs and consider upgrading to an SSD.
BIOS/UEFI not detecting HDD/SSD	Loose cable or faulty drive	Reconnect the drive and check BIOS/UEFI settings.
Keyboard not working during boot	Faulty keyboard or USB port	Try a different USB port or another keyboard.
Boot stuck at manufacturer logo	Hardware or BIOS issue	Disconnect external devices, reset BIOS settings, or update BIOS if required.

# Diagnosing Hardware Failures (RAM, HDD, GPU, PSU)
1. RAM (Random Access Memory)

Common Symptoms:

Frequent system crashes or blue screen.
Random restarts.
PC fails to boot.
Continuous beep sounds during startup.

Diagnosis:

Reseat the RAM modules.
Test one RAM stick at a time.
Run a memory diagnostic tool.
2. HDD (Hard Disk Drive)

Common Symptoms:

Slow performance.
Clicking or unusual noises.
Files become corrupted.
Operating system fails to boot.

Diagnosis:

Check if the HDD is detected in BIOS/UEFI.
Inspect SATA and power cables.
Run a disk health or SMART test.
3. GPU (Graphics Processing Unit)

Common Symptoms:

No display on the monitor.
Screen flickering or graphical artifacts.
Poor graphics performance.
PC crashes during games or graphics-intensive tasks.

Diagnosis:

Ensure the GPU is properly seated.
Check the display cable.
Update or reinstall graphics drivers.
Test with another GPU if available.
4. PSU (Power Supply Unit)

Common Symptoms:

PC does not power on.
Random shutdowns or restarts.
Fans do not spin.
Burning smell or unusual noise.

Diagnosis:

Check the power cable and power switch.
Verify PSU connections to the motherboard and components.
Test with a known working PSU or a PSU tester.
Conclusion
