Journal Entry 1: Module 1 - Introduction Lecture
---
- What is systems librarniship?
- a 45 year time period returns 131 results for 'systems librianship' - making it a very understudied area
- some say it should be IT experts who learn about libraries
- some say it should be librarians who learn IT
- either way the role requires continual learning as technology is always changing
- self-education is important and this course should help foster that
- cloud computing is becoming more popular

Journal Entry 2: Module 2 - Project Management and CLI Intro - Week 2 Lecture: Google Cloud for VMs
---
- Attention to detail is very important throughout the course and in this work - one slight spelling error results in a command or line of code not working at all

- Steps to setup Google Cloud virtual machine (VM)
  1. Use personal Google account and setup billing
-      https://cloud.google.com
  2. create project, name it and switch to the new dashboard
  3. install the gcloud CLI or connect to CLI via VM
  4. enable compute
  5. create an instance
  6. Micro-size, Ubuntu OS v. 22.04
  7. Will see VM listed once it is setup with internal and external IPs

- Connect to the VM (using the documentation)
- Update Ubuntu OS
-     sudo apt update
- BEST PRACTICES keep the OS / machine up to date

Journal Entry 3: Module 2 - Project Management and CLI Intro - Learn the CLI Lecture
---
- 2 ways we interact with computers (GUI = graphical user interface and non-GUI = command line interface (CLU)
- CLI = greater control b/c text based
-   due to more specific commands
-   takes some getting used t
-   requires some memorization
-   can be automated
-   cons - attention to detail, small details missed can cause errors
  
-   Dr. Burns wrote 2 programs to help
  1. Flashcards
  2. Learn the CLI
     
- ls (lists files/directories)
- pwd (prints name of currrent directory)
- mkdir (creates new directory)
- rmdir (remoaves directory)
- cd (change directory)
- touch (creates empty file)
- echo (prints characters)
- cat (displays current file contents)

- File System
   - need to also learn how files are stored and the archetecture of the file system
   - modern OS tend to "hide" the file system like MAC OS
   - makes things easier at first, at the expense of truly learning the file system
   - Linux uses tree like architecture for the file system
   - paths = where in the tree a folder exists
   - press tab to jump
   - practice TYPING commands vs copying/pasting
   - use SUDO command for running commands where ADMIN permissions are required
   - man = short hand for manual to read more about a command

Journal Entry 4: Module 3 - Using the Nano Text Editor Lecture
---
- to save and edit files you need a text editor
- programmers typically use a graphical text editor to write code
- gui based text editor isn't always the best
- can use a command line based text editor
- plain text file ONLY contains plain text

- Nano is a popular text editor
- Nano is modeless - making it user friendly - means Nano can be made to enter and manipulate text without entering different modes
- Nano is hard/tricky to learn because some ke-combos are different: eg. copy isn't ctrl-c
-     ctrl-u
- Tilde & Micro are alternative cmd text editors with common shortcuts so those are options to use as well
- can change colors and make additional customizations
- ed/vi/vim/emacs are not user friendly, but are powerful and do have a dedicated following

Journal Entry 5: Module 3 - Documenting with Git, GitHub, and Markdown Lecture
---
- Documentation is very important - it is the foundation of sharing knowledge and communicating

- Git and GitHub
   1. Version control
   2. Collaboration

- Markdown
  1. Documentation
  2. Markup language w/ simple syntax

 - create GitHub account
 - use 2FA
 - create repository
 - add README
 - using markdown to format text
 - file names is important
   1. avoid spaces
   2. keep it simple
   3. can use dashes
  
  -Setup Git on VM
   1. username
   2. github user
   3. email
   4. verify w/ gitcofig
   5. generate SSH key on VM
   6. Then create SSH key in GitHub account settings

Should committ from the CMD otherwise need to GITPULL for everything to sync

Journal Entry 6: Module 4 - Searching with Grep
---
*run sudo apt update*
- Always do this when logging into the VM each time
- GUI exist for some tasks, but many times in this profession we will be using the cmd line, so grep command is really important
- Grep helps search the contents of text files
- matches patterns
- returns the whole string / line

  1. create file operating systems.csv
  2. use grep to search the file
  3. will return the whole line for Chrome... not just "Chrome"
  4. By default Grep is case sensitive
  5. Man Grep = gets the manual
  6. use -i as it removes case sensitivity

Journal Entry 7: Module 4 - Practice searching with Grep Lecture
---
- Scopus (a bib. database) we will use for practice
1. Go to Scopus
2. Enter a search
3. Export as 'BibTex' file
4. Try for 100 documents
5. upload file to VM
6. sort command
7. uniq (de-dup function)
8. uniq -c (gives a count)

Journal Entry 8: Managing Software Lecture
---
- apt command = advanced package tool
- sudo command needed to install software
- sudo = super user do or substitute user do
- sudo allows you to run commands as the root user **IF** your user is added to the "sudo group", users in this group are allowed to perform commands using root permissions read/write/execute
- be careful running sudo commands as you can make inadvertant changes to your system / files
-     sudo apt update
-     sudo apt upgrade
- need name of the package to install software - sometimes have to search for the name of the package
- man (manual) pages are useful
- some are complex so it helps to use the TLDR app


Journal Entry 9: Library Search
---
- **yaz** client
- **Z39.50** is the standard protocal for connecting with ILS
- it is a very old protocol
- started before the internet and maintained by the library of congress
- created to transfer bib. info between networks
- yaz client allows us to interact with different libraries from the command line
- a big part of library science history

- first need to connect to a library database
- Z> is the home line for yaz
- to query the given catalog yaz is connected to
-      find @and @attr 1-21 "subject"
  2. will return the # of records found
  3. show command
  4. will show the whole bib. record


LAMP STACK - (Linux OS, Apache Server, mySQL Database, PHP server-side language)
---
The LAMP stack is a popular open source group of software. When 'stacked' together it can be used for web development. The operating sytem is Linux, Apache is the server, mySQL is the database and PHP is the server side scripting langauge. It provides a simple and free way to build great websites. There is a large community who uses this stack and mantains it as a leader in open source software.

<ins>Apache</ins> is a webserver and it's basic 

Journal Entry 10: Installing Apache Web Server
--



Journal Entry 11: Installing PHP
--

Journal Entry 12: Installing mySQL
--
















Useful cmd line prompts
---
1. *ctrl+C* - exits program
2. *whoami* shows logged in user
3. *locate file*
4. *man command*

Other tips
---
1. TAB speeds up typing commands
2. TLDR program that shows the manual of a specific application
3. Grep is like ctrl F

Links
---
[BCCLS Vega Discover Catalog](https://search.bccls.org)
[TLDR GitHub Page](https://github.com/tldr-pages/tldr)
