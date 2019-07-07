## Week 2 Write Up
### Introduction
The learning material for week 2 showed how to handle evidence with many forensic tools and techniques.

### Forensics Basics
Forensics is the process of discovering data within informative systems.  Computer forensics can be classified into 3 categories.  The first classification is live forensics, which is the collecting of data from the infected computer while it is still on.  This is so that information that is viable to change after the computer is shut down can be recorded.  The second classification is post-mortem based forensics, which is the collecting of data from looking at memory dumps or disks.  The last classification is network-based forensics, which is the collecting of data from network traffic.  Each of these classifications adhere to four principles, minimize data loss, record everything, analyze all data collected, and report findings.

### Evidence and How to Handle It
Evidence is anything that can be used to prove or disprove a fact.  In computer forensics, evidence can be found in the following different layers:
- Network
- Operating System
- Databases and Applications
- Peripherals
- Removable Media
- Human Testimony
When it comes to handling evidence, preserving the integrity of the evidence is the priority at all times.  Evidence can be volatile, meaning that they are subject to change whether willingly or unwillingly.  This can be attributed to Locard’s Exchange Principle which states that you can’t interact with a system without leaving some kind of effect on it.

### Order of Volatility
When collecting evidence you should proceed from the most volatile to the less volatile.  Below is an example of the order you would go through for a typical system
- System Memory
- Temporary Files System (Swapfile/paging file)
- Process Table and Network Connections
- Network Routing Information and ARP Cache
- Forensic Acquisition of Disks
- Remote Logging and Monitoring Data
- Physical configuration and network topology
- Backups

### Physical Memory
Physical memory (aka RAM) is the short-term memory of a computer.  The information contained within this memory is volatile and prone to decay after the computer is shutdown, but data from the memory is some of the most valuable data you can obtain.  From it you can find artifacts hidden by attackers and processes that have exited.


 
Here you can see an example of the information you can get from physical memory.  Here you can see the paths that were taken, executables that were run, and even passwords.

### Volatility Analysis
Volatility analysis is using tools to extract data from physical memory.  Below is an example of a volatility tool which is showing all of the different operations it can do to aid in a volatility analysis.
 
 
### Other Malware Related Volatility Tools
•	malfind
•	svcscan
•	ldrmodules
•	impscan
•	apihooks
•	idt
•	gdt
•	orphanthreads
•	callbacks
•	driverirp
•	psxview
•	ssdt_ex
•	ssdt_by_threads
