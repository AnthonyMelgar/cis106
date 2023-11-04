---
name: Anthony Melgar
semester: Spring 23
course: cis106
---

# Week Report 3 

## Summary of presentations 

### Introduction to Linux

**What is an operating system?**
provides all fundamental software feature of a computer. OS enables you to use the computer's hardware providing you the basic tools that make the computer useful. All of those features relay on the OS's kernel. Other OS features are owed to additional programs that run atop the kernel.

**Aside from a kernel, what other parts make an operating system?**
Applications, Graphical Desktop Environment, Daemons, Shells, Linux kernel, and hardware.

**What is a Linux distribution?**
OS that includes the Linux kernel, core unix tools, supplemental software, startup scripts and an installer.

**What is Ubuntu?**
Ubuntu is a Linux distribution, freely available with both community and professional support.

**Define the following terms: Open Source, Closed source, free software**
Open Source: the software may be distributed for a fee or free.
Close Source: the software is not distributed with the source code.
Free software: the software is distributed with the source code. The software cna be free of charge or obtained by a fee.

**What are the 4 freedoms defined by the free software foundation?**
Freedom0: uss the software for any purpose.
Freedom1: examine the source code and modify it as you see fit.
Freedom2: redistributed the software.
Freedom3: redistributed your modified software.

### The basics of Virtualization
**What is virtualization?**
defined as creating virtual versions of something. Can run multiple OSs on one physical machine at the same time.

**List 3 benefits of virtualization**
Allow running multiple OSs on one machine without dual boosting. Allows applications to be tested before installing them on a host machine. Reduces costs by decreasing the physical hardware that must be purchased for a network.
**What is a hypervisor?**
Software or Hardware in charge of creating, managing, and running virtual machine. Two types of hypervisor. Type1: runs directly on the hardware and has better performance. Type2: application that runs on top of an operating system.

**What is virtualbox**
A powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use. VirtualBox feature rich, high performance product for enterprise customers.

### Exploring Desktop 
**What is a desktop environment? (Provide 3 examples)**
Implementation of the desktop metaphor made of a bundle of programs running on top of a computer operating system. GNOME, KDE, XFCE.

**List 4 common elements of desktop environments**
Desktop settings, Display manager, File manager, and Icons

**What is Ubuntu’s default desktop environments?**
modified version of the GNOME desktop environment.

**What are the official flavors of Ubuntu?**
Ubuntu GNOME, Kubuntu, Lubuntu, Ubuntu Budgie, Cinnamon, Kylin, MATE, Studio, Xubuntu, Edubuntu, and Mythbuntu.

### What is a Shell?

**What is Bash?**
program that provides interactive access to the Linux system. Runs as a regular program whenever user logs into a terminal.

**How do you access the Linux CLI?**
Terminal Emulator and Linux Console.

**What is a console terminal?**
Emulates the old days of a hard-wired console terminal and is a direct interface to the Linux system.

**What is a terminal emulator?**
Program that allows you to access the Linux CLI.

**Provide 3 examples of Linux commands**
pwd (Prints the working directory), cat (Prints file contents), and mv (Moves and renames files and directories).

### Managing Software

**Which command is used for updating ubuntu**
APT (Advanced Package Tool)

**Which command is used for installing software. Provide an example.**
sudo+apt+install+package name. sudo apt install flameshot 

**Which command is used for removing software. Provide an example.**
sudo apt remove google chrome.

**Which command is used for searching for software. Provide an example.**
apt search firefox or apt search -n firefox or apt search "web browser"

**Package**
Archives that contain binaries of software, configuration files, and information about dependencies.

**Library**
Reusable code that can be used by more than one function or program.

**Repository**
Large collection of software available for download.