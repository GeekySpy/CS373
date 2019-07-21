## Week 4 Write Up
### Introduction
The learning material in week 4 shows how to think like a malware creator by finding vunerabilities/exploits in software and taking advantage of them.

### Manipulating Software
There are two kinds of vulnerablilities in software.  The first are bugs found in a system that can allow someone unauthorized access to it or change the behaivor of the program entirely.  The example in the lecture demonstrated this concept with an example program.  The program showed a car on a road, and that car eventually hits a fork in the row.  The program then prompts the user asking which direction they should go.  While the program is intended take the answers "left" or "right", putting in a different answer like "straight" can alter the program behaivor and create a scenario that was unintended by the creator.

The second vulnerability is a misconfiguration or a result of poor programming practice.  These are vulnerabilites that are not from the direct source code of a program. For example, weak passwords and accounts with no security measures are weak points that hackers can use to get into a system.

### Hacking Over Time
Hacking and manipulating software has changed drastically over time.  While they started out as jokes and forms of self-expression, they have gotten more serious as people use them for more malicious purposes.  Countries have their own teams of experts participating in cyber warfare, and even companies are looking to prevent hacking by promoting bug bounty programs (companies will pay people money if they find vulnerabilities in their system).

With this serious shift, hackers' targets for attacks have also shifted.  Many attacks started on the perimeter systems (company websites, email servers, etc.).  However, companies and governments have fortified their permiter systems which ends up forcing hackers to look elsewhere.  Now hackers look to attack internal networks by attacking users directly through phishing, social engineering, and other methods.

### WinDbg
WinDbg is a standard debugger program that freezes a program for inspection.  Below are a list of useful commands.
- lm: Lists modules
- lmf: Finds all modules with specified string (lmf m simple*)
- bp: Sets a breakpoint
- bl: Lists breakpoints
- g: Go, executes a program until a breakpoint is reached
- dd: Displays a dword of memory
- db: Views actual bytes of memory
- da: Displays memory in ASCII strings
- du: Displays memory in Unicode
- u: Unassemble, takes bytes at given address and starts to process them as assembly
- .formats: Can help convert hex to decimal
- t: Takes a step into next step
- p: Take a step over
- pt: Step over an entire function
- q: Quit

### Lab Lesson 1
