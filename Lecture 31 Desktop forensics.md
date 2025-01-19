# Lecture 31 - Desktop Forensics

## Introduction

In today's increasingly digital world, computer crimes and cyber attacks are on the rise. When such incidents occur, digital forensics experts are called upon to investigate and uncover evidence from computers and digital devices. In this lecture, we will focus specifically on desktop forensics - the branch of digital forensics that deals with examining desktop computers and laptops.

## Learning Objectives

By the end of this lecture, you should be able to:

1. Define digital forensics and desktop forensics 
2. Understand the key tasks involved in a desktop forensics investigation
3. Recognize common challenges faced in desktop forensics
4. Identify important types of evidence that can be recovered from a computer system

## 1. Digital Forensics

### 1.1 Background Context

Digital forensics emerged as a field in the 1970s and 80s as computers became more prevalent in homes and offices. As computer-related crimes increased, law enforcement recognized the need to properly collect and examine digital evidence.

### 1.2 Definition

Digital forensics is the process of uncovering and interpreting electronic data for use as evidence in criminal or civil court cases. It involves the identification, preservation, collection, analysis and reporting of digitally stored information.[1]

## 2. Desktop Forensics 

### 2.1 Background Context

Desktop forensics is a sub-discipline of digital forensics that focuses on evidence found in desktop and laptop computers. This includes analysis of the computer's hard drive, memory, registry, logs and other sources of data. 

### 2.2 Definition

Desktop forensics can be defined as the process of collecting, analyzing and preserving evidence from a standalone PC or laptop in a way that is suitable for presentation in a court of law. The goal is to perform a structured investigation and maintain a documented chain of evidence.[2]

## 3. Desktop Forensics Tasks

### 3.1 Background Context

A desktop forensics investigation typically follows a standard set of procedures to ensure the integrity and admissibility of evidence. Key tasks include seizure of devices, imaging disks, recovering deleted files, analyzing system logs and identifying malware.

### 3.2 Definition

Desktop forensic tasks are the specific procedures and techniques used to investigate a computer system and gather evidence after a suspected incident. These tasks aim to establish a timeline of events, uncover relevant files and logs, and attribute actions to specific users.

### 3.3 Confiscation of Devices

#### 3.3.1 Acquiring Devices Affected by the Attack

##### 3.3.1.1 Devices

The first step is to identify and acquire the primary computer systems believed to have been accessed or compromised during the incident. This could include desktops, laptops or servers. 

##### 3.3.1.2 Peripherals

Any connected peripherals like printers, scanners or external hard drives should also be collected as they may contain relevant evidence. 

##### 3.3.1.3 External Storage Devices

Portable storage media such as USB drives, SD cards and CDs/DVDs must be seized if they are thought to contain evidence pertinent to the case.

#### 3.3.2 Acquiring the Devices Used to Perform the Attack

In addition to the targeted systems, forensic investigators will attempt to locate and confiscate any computers or devices used by the attacker. Analysis of these machines can provide insight into the attacker's methods and motives.

#### 3.3.3 Acquired Devices Ensure Integrity of Evidence 

All devices should be properly documented, labeled and securely stored to maintain the chain of custody. Any changes or accesses to the evidence must be logged.[3]

### 3.4 Taking an Image of the System

#### 3.4.1 Operating System

An exact replica of the system's hard drive is made, including the operating system, applications, and all files. This "disk image" preserves the original evidence.

#### 3.4.2 Settings

The disk image will contain all system settings, configurations and registry entries present on the computer at the time the copy was made. 

#### 3.4.3 Programs

All applications and software are included in the image, allowing investigators to see what programs were installed and how they were used.

#### 3.4.4 Files

The full file system is replicated in the disk image, including all user-generated content like documents, photos, databases, etc.

#### 3.4.5 Confiscation Is Followed by Taking an Image

Imaging typically occurs soon after confiscation to minimize the risk of data being altered or overwritten on the original system.

#### 3.4.6 Never Perform Investigation on Original Device

Analyzing the original evidence media risks corrupting the data and could make it inadmissible in court. Working from an image maintains the integrity of the evidence.

### 3.5 Using Forensic Analysis Tools

Specialized software is used to index, search and recover data from the disk image. Common forensics tools include:

| Tool | Description |
|------|-------------|
| FTK  | Forensic Toolkit by AccessData for analyzing disk images |
| Encase | Industry standard tool by Opentext for imaging & investigation |  
| Autopsy | Open source digital forensics platform | 
| SANS SIFT | Linux distro with forensics & incident response tools |

### 3.6 Reviewing Data

#### 3.6.1 Reviewing Files and Settings

##### 3.6.1.1 Identify Modifications and/or Deletions

Examiners look for files that have been altered or deleted and attempt to recover them. Modifications may indicate an attempt to conceal evidence.

##### 3.6.1.2 File Recovery

###### 3.6.1.2.1 What Has Been Removed

Specialized tools can often recover files that have been emptied from the Recycle Bin or otherwise deleted by the user. 

###### 3.6.1.2.2 What Are the Changes

Investigators also compare files against known good versions to identify any changes that have been made, as these modifications could be an attempt to hide information.

###### 3.6.1.2.2 Covering Tracks

Deletion and modification of files may indicate the user was trying to cover their tracks and destroy evidence of their activities.

### 3.7 Reviewing System Logs

#### 3.7.1 Storing Events Logged by the Operating System

System logs provide a wealth of information about the recent use of the computer, including:

##### 3.7.1.1 Services Installed 

Logs can show what software and services are set to start when the computer boots up, which may reveal malware.

##### 3.7.1.2 Device Power On/Off

Logs record the times the system was powered on, off, or restarted, helping establish a timeline. 

##### 3.7.1.3 Unexpected Shutdowns

Improper shutdowns may indicate an attempts to quickly destroy evidence.

##### 3.7.1.4 User Logins, Times and Dates

Logs show all user accounts that logged into the system and the times these logins occurred.

### 3.8 Reviewing User Activity

#### 3.8.1 Event Viewer

The Windows Event Viewer contains detailed logs about system events, errors and user actions.

#### 3.8.2 Other Forensic Tools Can Find Evidence of

##### 3.8.2.1 Webpages Visited

Web browser histories and caches can reveal what sites the user accessed and when.

##### 3.8.2.2 Applications Used

Investigators can determine what programs were run on the system and potentially recover stored data from them.

##### 3.8.2.3 Flash Drives Connected

Logs may show if any USB drives or external media were connected to the system, indicating a possible data exfiltration path.

##### 3.8.2.4 Downloads

Files downloaded to the computer might be relevant to the case, especially if they contain malware, hacking tools, or proprietary data.

##### 3.8.2.5 Networks Accessed

Examining network and WiFi logs can show what other systems the computer communicated with.   

### 3.9 Malware Analysis

#### 3.9.1 Identification of Inner Workings of Malicious Software

Special tools like disassemblers and debuggers are used to examine the code of any malware found on the system.

#### 3.9.2 Identify Level of Damage 

Investigators attempt to determine the full capabilities of the malware and what systems or data it impacted.

#### 3.9.3 Provide Evidence for Court Cases

Malware analysis can provide clues about the attacker's identity and methods that can be used as evidence in legal proceedings.

### 3.10 Malware Alerts

#### 3.10.1 Use Antivirus Software to Identify System Malware Flags

Running scans with multiple antivirus tools may identify known malicious software on the computer.

##### 3.10.1.1 When Infected

AV scans can determine approximately when the malware first infected the system based on file timestamps and malware signature databases.

##### 3.10.1.2 What Was Affected

Identifying the specific malware provides insight into what data, resources or systems it targeted and potentially compromised.

##### 3.10.1.3 Identify the Source of the Attack

Some malware includes embedded information that hints at its creator or origin.

### 3.11 Challenges of Live Forensics

#### 3.11.1 Performing Analysis on the Original Device While It Is Still Running 

"Live" forensics involves examining a powered-on machine, usually to recover volatile data that would be lost if the system were shut down. 

#### 3.11.2 Volatile Data - Can Be Key Evidence of an Attack

Important evidence may exist in RAM, running processes, network connections, or encrypted storage that becomes inaccessible when power is removed.

##### 3.11.2.1 Challenges When Working with Volatile Data

Volatile data by its nature is constantly changing as the computer runs, which can make it difficult to capture a consistent state. Data in memory may also be fragmented or obfuscated. 

### 3.12 Changing Data in Situ Challenges

#### 3.12.1 Possibility of Changing Data on System Leading to Contamination of Evidence

Interacting with a live system risks altering files and timestamps that could overwrite or damage evidence.

#### 3.12.2 Malware Still Active

Active malware may deliberately destroy evidence or otherwise hamper the investigation if it detects the presence of forensic tools.

#### 3.12.3 Investigators Actions - Changing Data on the System

##### 3.12.3.1 The Need for Logging

Examiners must carefully document any actions taken and changes made to the system to preserve admissibility of evidence.

### 3.13 Data Corruption

#### 3.13.1 How Is Forensic Data Corrupted?

##### 3.13.1.1 Investigators Actions

Improper shutdown of the computer or mistakes during live analysis can damage files and metadata.

##### 3.13.1.2 Malware May Run Malicious Code

Malware might activate deliberately destructive payloads if it detects forensic activity.

#### 3.13.2 Preventing Data Corruption Without Contamination of Evidence Using Specialist Forensic Tools

Forensic examiners use special software write blockers and controlled boot environments to minimize the risk of evidence alteration.

| Tool | Description |
|------|-------------|
| Tableau Forensic Bridges | Hardware write blockers to prevent modifying evidence media |
| F-Response | Solution for remote forensic analysis of live systems |
| Volatility | Memory dump and analysis tools for capturing RAM |
| FRED | Forensic Recovery of Evidence Device for protected imaging |

### 3.14 Capturing Data in Active Memory

#### 3.14.1 Active Memory Is Volatile

The contents of a system's RAM contain useful forensic artifacts but will be lost when the computer powers off.

##### 3.14.1.1 Types of Volatile Data in Active Memory

| Data Type | Description |
|-----------|-------------|
| Network Connections | Open ports and active network communications |
| Running Processes | The code and memory state of all running software |
| Open Files | Files in use by running programs |
| Malware in Memory | Active malware that does not exist on disk |
| Contents of Open Windows | Data displayed on the screen that has not been saved |

### 3.15 Losing Temporary Data

#### 3.15.1 Temporary Files Are Volatile Data

Applications often store data in temporary files that may contain evidence but are often deleted when the program closes.

#### 3.15.2 Temp Files Can Be Used to Recover Data When a PC or Program Shuts Down Suddenly

Office applications like Word create temporary auto-recover files that could allow an unsaved document to be restored.

#### 3.15.3 Investigators Need to Be Careful With Live Forensics to Not Accidentally Destroy Temporary Files

Running programs create and remove temp files frequently, so care must be taken to preserve them during a live analysis.

## Conclusion

Desktop forensics is a complex and challenging field that requires specialized skills, tools and carefully defined procedures. As we've seen, the core tasks include:

- Identifying and collecting relevant devices 
- Creating forensic images to preserve evidence
- Examining system logs and files for signs of malicious activity
- Recovering deleted data 
- Analyzing malware   

The key goals are to gather evidence in an admissible manner and to piece together the timeline and technical details of a suspected crime or policy violation. Desktop forensics skills are in high demand as cyber criminals become more sophisticated. It's a fascinating branch of computer science where you really can make a difference.

## References

[1] National Institute of Standards and Technology. (2006). Guide to Integrating Forensic Techniques into Incident Response. https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-86.pdf

[2] Easttom, Chuck. (2014). System Forensics, Investigation, and Response, 2nd Edition.

[3] Department of Justice. (2008). Electronic Crime Scene Investigation: A Guide for First Responders, Second Edition. https://www.ncjrs.gov/pdffiles1/nij/219941.pdf

[4] Gale, A. (2024). Lecture 31 Desktop forensics [PowerPoint slides].Retrieved from [URL](https://teams.microsoft.com/)
