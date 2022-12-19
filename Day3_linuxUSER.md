# Linux For User
## Overview of kali-linux
---
- The name Kali Linux originates from Sanatan dharma, which means death, time, black, and Lord of Death: Shiva. Also, the OS was written right from the ground up. Kali Linux is the OS dedicated to ethical hacking and fiddling with networking utilities. The best part of the one-of-a-kind OS is that it is completely free for life.

- Kali Linux came into being back in 2013, and it was a brainchild of Offensive Security which primarily focuses on training and certification based on cybersecurity. Offensive Security made use of the existing security module in Backtrack Linux, which was further redeveloped into Kali Linux, relying entirely on the Debian variant.

## **Why use Kali Linux?**
----
There are numerous ways that you can implement to become an ultimate user of the OS. Specific uses that make Kali Linux different from other OS are:

- **Free for life, beyond time**: The OS is completely free throughout its existence.
- **Offers several tools:** Kali Linux comprises more than 600 unique tools that aid in security analysis, penetration testing, and other related devices.
- **Open Source:** Do you like Android OS over iOS? If you're one of the people who dig Android rather than iOS, then you're aware of the customization, usage that Android offers to users. As Kali is an integral part of Linux's extended family meaning it strictly follows the open-source criteria. The development tree of Kali Linux is available on Git, whereas the code is already available for tweaking.
- **Multi-lingual support:** The tools for penetration are written in the English language; the OS still supports multi-language. The idea is to get the OS popular among people hailing from different backgrounds from different backgrounds to come together and use the tool for their goals.
- **Exponentially Customizable:** Offensive Security's developers truly understand the necessity of building a highly customizable OS. The designing method of Kali Linux is enormous. If Kali Linux falls into the hands of adventurous users, then customizing the OS is only limited by the imagination.
---
## **List of Tools in Kali Linux**
---
Kali Linux became incredibly popular as the OS comes with numerous cybersecurity tools from its default.

1. **INFORMATION GATHERING**
---

  Tools for information gathering,in system ,

- network,host
- dmitry
- ike-scan
- legion
- maltego
- netdiscover
- nmap
- p0f
- recon-ng
- spiderfoot
---

2) **Vulnerability Analysis**
---

Tools for Finding Vulnerabilities

- legion
- lynis
- nikito
- nmap
- unix-prives
---
3) **Web Application Analysis**
---
Tools for Finding Vulnerabilities and exploits on websites.
- burpsuite
- commix
- httrack
- paros
- skipfish
- sqlmap
- webscarab
- wpscan
- ZAP
---
4) **Database Assessment**
---
Tools for finding vulnerabilities and exploits on Databases.
- jSQL Injection
- mdb-sql
- oscanner
- sidguesser
- sqldict
- SQLite data. . .
- sqlmap
- sqlninja
- sqlsus
- tnscmd10g
---
5) **Password Attacks**
---
Tools for exploiting Passwords for login, websites, application, windows . .
- cewl
- crunch
- hashcat
- hashcat
- john
- johnny
- medusa
- ncrack
- ophcrack
- rainbowcrack
- rcracki_mt
- wordlists
---
6) **Wireless Attacks**
---
Tools for exploiting Wireless systems like wifi,bluetooth . .
- aircrack-ng
- chirp
- cowpatty
- fern wifi cra . . .
- kismet
- mdk3
- mfoc
- mfterm
- pixiewps
- reaver
- wifite
----
7) **Reverse Engineering**
---
Tools for exploiting Softwares ,Mobile Applications and any binary files
- apktool
- bytecode-vi. . .
- clang
- clang++
- dex2jar
- edp-debug. . .
- ghidra
- jadx-gui
- javasnoop
- NASM shell
- ollydpg
- radare2
---
8) **Exploitation Tools**
---
Tools for exploiting Softwares, Mobile, Computers, websites and anythings
- armitage
- beef xss fra . . .
- metasploit Fram. . .
- msf payloa. . .
- searchsploit
- social engin. . .
- sqlmap
- termineter
---
9) **Sniffing & spoofing**
---

Tools for listening or hijacking networks
- driftnet
- ettercap-gr. . .
- hamster
- macchanger
- mitmproxy
- netsniff-ng
- responder
- wireshark
---
10) **POST exploitation**
---
Tools for maintaining our access. Used after exploiting a system
- backdoor-f. . .
- exe2hex
- mimikatz
- nishang
- powersploit
- proxychains4
- weevely
---
11) **Forensics**
---
Tools for Doing researches and investigate cyber Attacks.
- autopsy
- binwalk
- bulk_extrac. . .
- chkrootkit
- foremost
- galleta
- hashdeep
---
12) **Reporting Tools**
---
Tools for report preparation.After some forensic you will get data and you will write report and these tools will help you.
- cutycapt
- dradis fram . . .
- faraday IDE. . .
- maltego
- pipal
- recordmyd. . .
---
13) **Social Engineering Tools**
---
Tools used for social engineering attacks
- backdoor-f . . .
- beef xss fra . . .
- maltego
- msf paylo . . .
- social Engin. . .
---
14) **System Services**
---
Buttons used to start some services.
- beef start
- beef stop
- dradis start
- dradis stop
---
15) **Usually Used Applications**
---
Softwares for some basic purposes
- Accessories
- Graphics
- internet 
- Office
- Other 
- Programming 
- Sound & Video
- System Tools
- Utilities 
---
## **Folder managers**
---
1. Dolphin

2. Thunar

3. Nautilus
---
# Linux Commands

Linux Systems uses shell. The shell help us to 
Communicate with the kernel and helps to execute 
codes.

**ls/ list directory**
___
- SYNOPSIS

  - ls [option] . . .[File] . . .

- DESCRIPTION

  - list information about the FILEs (the current directory by default).
  ``` 
  ls 
  ls -l 
  ls -a 
  ls -R 
  - for more use man ls 
  ```
---
**cd / Change directory**
  ___
- SYNOPSIS

  - cd[directory]

- DESCRIPTION

  - It is used to change current working directory
  ``` 
  cd/ => root 
  cd => home  
  cd.. => 1x back 
  cd../.. => 2x back 
  - for more use man cd 
  ```
  ---
  **Pwd / print working directory**
  ---
- SYNOPSIS

    - Pwd[-option]

- DESCRIPTION

  - It prints the path of the working directory,starting from the root.

 E.g after typing pwd:/home/omar/desktop/OSlab
  
  ---
 # **echo**

- SYNOPSIS

  - echo[option] [string]

- DESCRIPTION

   - echo command in linux is used to display line of text/string that are passed as an argument. This is a built in command that is mostly used in shell scripts and batch files to output status text to the screen or a file .
- you can write texts into files.
  - echo text >file.txt
  ---
  Other command 
  ----
  ``` bash 
  cat :- Used to show the content of a file

  head :- Used to show the content of a file

  tail :- Used to show the content of a file

  less :- Used to show the content of a file

  touch :- Creates any kind of files with the name you gave it. With empty inside

  mkdir :- Creates Folder with the name u gave it.
  rm :- remove the file 

  grep :- The grep filter searches a file for a particular pattern of characters and displays all lines that contain that pattern.

  Wc :- It is used to find out number of lines word count, byte and characters count in the files specified in the file arguments.
---
**Multiple Command Executions**
---
- You can run / execute multiple commands in one line.

- using 3 methods
  - And (&&)
   - Or (||)
  - Pipeing (|)

AND (&&)
---
- On AND operation all commands you entered will be executed .
- If both are working without error

OR (||)
---
- On OR operation the command will executed.If it have error or not

Pipeing(|)
---
- On pipe,will help you run commands by using the output of the first command as the input for the next one.
---------------
