```
    name: sahil v patel
    course: cis 106
    semester: spring 23
```
# Week Reports 3

## Summary of Presentation

### Introduction to Linux 

* **what is an operating system?**
  
 An operating system (OS) is system software that manages computer hardware, software resources, and provides various services to computer programs. It acts as an intermediary between the user and the hardware, enabling users to interact with the computer and run applications while abstracting the complex hardware operations. 

* **Aside from a kernel, what other parts make an operating system?**
  
Shell: The command-line interface or graphical user interface that allows users to interact with the OS.

File System: Manages file storage, organization, and access.

Device Drivers: Enable communication between the kernel and hardware devices.

System Libraries: Collections of functions and routines that applications can use.

User Interface: Provides a means for users to interact with the system.
  
* **What is a Linux distribution?**
  
A Linux distribution, or "Linux distro," is a complete operating system built on the Linux kernel. It includes a collection of software packages, system libraries, configuration files, and a package management system. Different Linux distributions may target various use cases, such as desktop computing, server deployment, or specialized tasks. 

* **What is Ubuntu?**
 
Ubuntu is a widely used and user-friendly Linux distribution based on Debian. It is known for its focus on ease of use and robust community support. Ubuntu offers both a desktop version, designed for personal computing, and a server version, optimized for server environments.

* **Define the following terms: Open Source, Closed source, free software**
  
Open Source: Software whose source code is freely available,      allowing anyone to view, modify, and distribute it. It promotes transparency and collaboration.

Closed Source: Software whose source code is not publicly accessible, and its distribution and modification are usually restricted.

Free Software: Software that gives users the freedom to run, study, modify, and distribute it. "Free" refers to freedom, not necessarily price.

* **What are the 4 freedoms defined by the free software foundation?**
  
Freedom 0: The freedom to run the software for any purpose.

Freedom 1: The freedom to study and modify the software's source code.

Freedom 2: The freedom to redistribute copies of the software.

Freedom 3: The freedom to distribute modified versions of the software.

### The Basics of Virtualization

* **What is virtualization?**
  
Virtualization is the technology that enables the creation of virtual, rather than physical, versions of computing resources such as servers, storage devices, and networks. It allows multiple virtual instances (virtual machines) to run on a single physical machine, each with its own operating system and applications.

* **List 3 benefits of virtualization ?**
  
Resource Optimization: Efficiently utilize hardware resources by running multiple virtual machines on a single physical server, reducing hardware costs.

Isolation: Isolate and sandbox applications or services within virtual machines, improving security and preventing conflicts.

Flexibility and Scalability: Easily deploy, migrate, and scale virtual machines to adapt to changing workloads and resource demands.

* **What is a hypervisor?**
  
A hypervisor, also known as a virtual machine monitor (VMM), is software or hardware that manages virtual machines. It controls the allocation of physical hardware resources to virtual machines, allowing multiple operating systems to run independently on the same physical hardware.

* **What is virtualbox?**
  
VirtualBox is an open-source virtualization software developed by Oracle. It allows users to create and run virtual machines on various host operating systems, including Windows, Linux, macOS, and more. VirtualBox supports a wide range of guest operating systems, making it a versatile choice for virtualization.

### Exploring Desktop Environments

* **What is a desktop environment? (Provide 3 examples)**\
  
A desktop environment (DE) is a graphical user interface (GUI) for a computer's operating system. It provides a cohesive and user-friendly interface for users to interact with their system and applications. 

Examples of desktop environments include GNOME, KDE Plasma, and Xfce.

* **List 4 common elements of desktop environments?**
Desktop Shell: The graphical interface where icons, wallpapers, and widgets are displayed.

Window Manager: Manages the appearance and behavior of windows, including their placement, resizing, and decoration.

File Manager: Provides tools for navigating the file system, managing files and folders, and performing file operations.

System Settings: A control panel for configuring system preferences, hardware settings, and user accounts.


* **What is Ubuntu’s default desktop environments?**
  
Ubuntu's default desktop environment has historically been GNOME. However, Ubuntu offers several official flavors with different desktop environments, including KDE Plasma (Kubuntu), Xfce (Xubuntu), and LXQt (Lubuntu).

* **What are the official flavors of Ubuntu?**
Ubuntu offers several official flavors, each featuring a different desktop environment. Some examples include:

 Kubuntu: Ubuntu with the KDE Plasma desktop.
Xubuntu: Ubuntu with the Xfce desktop.
Lubuntu: Ubuntu with the LXQt desktop.

##  Ubuntu Budgie: Ubuntu with the Budgie desktop.

### What is a Shell?

* **What is Bash?**
  
Bash, short for "Bourne Again Shell," is a popular command-line shell and scripting language for Unix-like operating systems, including Linux. It provides an interface for users to interact with the system using text-based commands and scripts.

* **How do you access the Linux CLI?**
  
You can access the Linux command-line interface (CLI) by opening a terminal emulator application, such as GNOME Terminal, Konsole, or Xterm. Once the terminal is open, you can enter and execute commands.

* **What is a console terminal?**
* 
A console terminal refers to a physical terminal device or a virtual terminal (TTY) that provides direct access to the system without a graphical interface. Console terminals are typically used for system administration and troubleshooting tasks.

* **What is a terminal emulator?**
A terminal emulator is a software application that simulates a physical terminal, allowing users to interact with the CLI of an operating system through a graphical interface. It provides a text-based window where commands can be entered and executed.

* **Provide 3 examples of Linux commands**
  
ls - The most frequently used command in Linux to list directories.

pwd - Print working directory command in Linux.

cd - Linux command to navigate through directories.

### Managing Software:

* **Which command is used for updating Ubuntu?**
  
The command used for updating Ubuntu's package database and installed packages is sudo apt update && sudo apt upgrade.

* **Which command is used for installing software? Provide an example.**
  
The command used for installing software in Ubuntu is sudo apt install. For example, to install the Firefox web browser, you can use sudo apt install firefox.

* **Which command is used for removing software? Provide an example.**
  
The command used for removing software in Ubuntu is sudo apt remove. For example, to remove the LibreOffice Writer application, you can use sudo apt remove libreoffice-writer.

* **Which command is used for searching for software? Provide an example.**
  
The command used for searching for software in Ubuntu is apt search. For example, to search for packages related to image editing, you can use apt search image editing.

## Definition of the following terms:

* **Package: A package is a compressed archive containing software, configuration files, and metadata needed for installation and management. Package managers use packages to install, update, or remove software.**
* **Library: A library is a collection of pre-compiled code and functions that applications can use to perform common tasks. Libraries help reduce redundancy and make software development more efficient.**
* **Repository: A repository is a centralized location where software packages and their metadata are stored and maintained. Package managers use repositories to download and install software and updates.**