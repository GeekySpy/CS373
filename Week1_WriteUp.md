## Week 1

### Basics of Malware 1
The first few lectures was an overall view of malware that explained terminology and introduced VMs.
  
### What is Malware?
Malware stands for MALicious softWARE.  It’s a destructive program designed to cause harm to a user or machine in some way.  It can be transmitted through USBs, Applications, PDF, and Office files (macros that help do work).  However, the biggest cause of infection is by the user (i.e. people clicking on malware).

### Why It Exists
Creating and distributing malware is relatively easy to do and can be done by pretty much anyone.  Main reasons for creating and using malware is for organized crime, advertising, research, experimentation, and for the sake of breaking stuff.

### Types of Malware
- Virus: Malware that is able to spread quickly and over large distances
- Trojans: Malware that is disguised as a legitimate program
- Potentially Unwanted Programs:  Programs that are generally unwanted and don’t fall under the virus or trojan category

### Terminology
- White: Clean/Uninfected file
- Black: Dirty/Infected file
- Gray: File which can’t be confirmed white or black
- Sample: A piece of malware
- Goat: A sacrificial system that you let malware infect
- Replication: The process of replicating malware behavior
- Hash: Value of a system, changes as the system changes

### Virtual Machine Tools
- AntiSpy: Application that can help detect spyware
- FileInsight: Program that can analyze binary files and turn hex code into strings
- Fake Net: Creates a fake network for the malware to be on
- Flypaper: Prevents malware from exiting and blocks network traffic
- Process Explorer: A more detailed version of Task Manager
- Process Monitor: Shows all processes made and what time they were made

### Basics of Malware 2
These lectures demonstrated technical aspects of malware, with a focus on forensics and analytical skills.

### Advanced Persistent Threats (APTs)
A term created by US Air-Force analysts to describe attackers that are fluent in cyber intrusion methods and techniques (Advanced), have an objective and works to achieve their goal without detection (Persistent), and are organized, sufficiently funded, and motivated (Threat).  APTs can be described by several characteristics: actors, motives, targets, and goals.

### APT Kill-Chain
Process that APTs take when attacking a target and completing its goals.
1. Reconnaissance: Collection information
2. Weaponization: Obtain right tools to attack target
3. Delivery: How are you going to deliver weapon?
4. Exploitation: When your weapon is delivered
5. Installation: How are you going to keep that weapon in place?
6. Command and Control: Get target under your influence
7. Actions on Objectives: Use influence to complete goal

### Types of Analyses
- Forensic Analysis: Contextual data that leads a research to a conclusion
- Static Analysis: Analysis of software that is performed without executing programs
- Dynamic Analysis: Analysis of software that performed while executing programs
- String Analysis: Analyzing strings (sequence of characters) to come to a conclusion
  - Making conclusion on what a program does based on its function names
  -	Find origin of program based on language being used in program
- Binary Analysis: Analyze binary code level to come to a conclusion
  - Helpful when there isn’t source code
