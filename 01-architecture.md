# Architecture of Operating System

# Intro

The core software components of an operating system are collectively known as the kernel. The kernel has unrestricted access to all of the resources on the system. Each component of the operating system is contained within the kernel, it could communicate directly with any other component.

<img src='./img/arch.png'/>

# Applications

A computer program with an interface, enabling people to use the computer as a tool to accomplish a specific task. Word processing, spreadsheet, and communications software are all examples of applications.

# System Call Interface

A system call is the programmatic way in which a computer program requests a service from the kernel of the operating system it is executed. A computer program makes a system call when it makes a request to the operating system’s kernel. The kernel responds to the system call by performing the requested service. This interface between the kernel and the computer program is called the system call interface.

## Memory Manager

Memory management is the functionality of an operating system which handles or manages primary memory and moves processes back and forth between main memory and disk during execution. Memory management keeps track of each and every memory location, regardless of either it is allocated to some process or it is free. It checks how much memory is to be allocated to processes. It decides which process will get memory at what time. It tracks whenever some memory gets freed or unallocated and correspondingly it updates the status.

## Process Scheduler

<img src='./img/scheduling.jpg' />

The process scheduling is the activity of the process manager that handles the removal of the running process from the CPU and the selection of another process on the basis of a particular strategy.

## Interprocess Communication

Inter Process Communication (IPC) refers to a mechanism, where the operating systems allow various processes to communicate with each other. This involves synchronizing their actions and managing shared data. This tutorial covers a foundational understanding of IPC. Each of the chapters contain related topics with simple and useful examples.

## File System

A file system is a collection of files and directories. Each file is a sequence of bytes, and each directory is a collection of files and subdirectories. The file system is the structure of the operating system. The file system controls how the Operating System stores the data and how it is accessed.

## I/O Manager

The Input-Output manager is known as the I/O Manager. A computer consists of various devices that provide input to the computer and wait for the corresponding output. An IO manager is responsible for managing the devices and the data flow between them. This is done by managing the data flow with the help of third party softwares known as device drivers.

## Network Manager

A network manages the communication between the various computers in a network. It is responsible for the routing of the packets and the transmission of the packets. It is also responsible for the management of the network. Without a network manager, the network is not possible to function or communicate with the other network components.
