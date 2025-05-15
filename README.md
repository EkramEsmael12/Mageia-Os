## OS INSTALLATION
This document provides a detailed guide for installing Mageia OS on VMware Workstation. 
It begins with downloading and installing VMware Workstation, as well as obtaining the appropriate Mageia ISO file from the official Mageia website. 
The guide then walks through the process of creating a new virtual machine, assigning system resources such as RAM and disk space, and configuring installation options suitable for Mageia.

Next, the document outlines the step-by-step installation process, including selecting the desired language, configuring keyboard and network settings, and creating user accounts.
After the installation is complete, the guide explains how to reboot the virtual machine, detach the ISO image, and log in using the newly created credentials.

## SYSTEM CALL
The document provides an overview of system calls in Fedora OS, with a specific focus on the vfork() system call. 
This function is used to create new processes by temporarily suspending the parent process until the child process either calls exec() or exits. 
It is particularly useful for performance optimization in scenarios where the child process immediately replaces its image using exec(), avoiding unnecessary copying of the parent's memory space.
A sample C code snippet demonstrates the use of vfork(), highlighting both efficient process creation and proper synchronization.
Since Fedora is based on the standard Linux kernel, the behavior of vfork() aligns with other Linux distributions. 
Overall, the document serves as a concise technical reference for understanding and using vfork() in a Linux environment.

