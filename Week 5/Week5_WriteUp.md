### Week 5 Write Up

## Rootkits
Rootkits aretools that help malware actively conceals its existence and actions from users and system processes.  Rootkits tend to embed itself into the kernel memory of a system.  However, rootkits have a difficult time entering 64 bit kernel systems and need to use alternate methods.  These methods are listed below.
* Bypassing driver signing check (e.g. using testsigning mode)
* Modifying the windows boot path (MBR etc) - Secure boot prevents this.
* Kernel exploits in Windows kernel or third party drivers
* Stealing valid digisigs (similar to Stuxnet)

## Kernel
The kernel is the central module of an operating system.  It is the first to be loaded and remains in main memory of a system.  The kernel is responsible for memory management, task management, process management, and disk management.  The kernel is a prime target for rootkits because rootkits take advantage of the fact that operating systems control permissions to give the rootkit code high level privileges.  This allows rootkits to avoid detection from antivirus software.

## Threads
Threads are the smallest unit of execution within an operating system.  They are a series of processes that are executed by a CPU.  This is done through a thread scheduler 
