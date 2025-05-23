[Go to Koha Project](#Koha-Project)

[Go to Omeka Project](#Omeka-Project)

[Go to WordPress Project](#Wordpress-Project)

[Go to LAMP Stack](#LAMP-Stack)

[Go to Documentation of OPAC and Cataloging Module](#Documentation-of-OPAC-and-Cataloging-Module)

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


## LAMP Stack

Linux - Operating System  

Apache - Web Server  

mySQL - Database  

PHP - Server-side Programmming


![LAMP](https://lh3.googleusercontent.com/zwledndkiqkNlB3zhRw6EA4RzRV7SofUz-5N2YyNetqAg3CsYOuir4UBjz8tQbOtuaDCMaGo0tGl=s2000-w2000)

---
The LAMP stack is a popular open source group of software. When 'stacked' together it can be used for web development. The operating sytem is Linux, Apache is the server, mySQL is the database and PHP is the server side scripting langauge. It provides a simple and free way to build great websites. There is a large community who uses this stack and mantains it as a leader in open source software.

*  <ins>Linux</ins> is an open source operating system, based on unix, that is stable, secure and flexible. It serves as the foundation for many computers and servers. It provides a command line interface that is widely used.

*  <ins>Apache</ins> is an open-source HTTP webserver software and it gets requests from web browsers (Chrome, FireFox, etc.) and send back the requested web pages.

*  <ins>mySQL</ins> is an open-source relational database. There are two types of databases relational databases (organizes data into tables with rows and columns) and a non-relational database (typically based on documents). Users can interact with a mySQL database using SQL or structured query language, MySQL is fast, realiable and scalable.

*  <ins>PHP</ins> is a server-side programming language that is installed on a server such as Apache. The web server processes PHP and sends it as HTML to the browser. PHP is easy to use, flexible, and being open-source, has a great community supporting it.

Journal Entry 10: Installing Apache Web Server
--
1. First, you will always want to update and upgrade!
4. Do this and install Apache with the below command that <ins>combines</ins> everything:
5.     sudo apt update && sudo apt -y install apache2
6. Next verify that Apache is running:
7.     sudo systemctl status apache2
8. You will want to get a return of "Apache2 is running"
9. Next, in the following directory
10.     var/www/html/
11. Create an .index.html file and test it out in the browser
13.     http://<publicIP>/index.html
14. Make sure your firewall rules allow all http traffic
    
Journal Entry 11: Installing PHP
--
1. Before getting started, as always, update apps/OS
2. Use the following command to install PHP and restart Apache2
3.     sudo apt install php libapache2-mod-php
4.     sudo systemctl restart apache2
5. Use the -v command to check the version of PHP
6.     php -v
7. Checking the version is also <ins>verifying</ins> PHP was installed correctly
8. Check the status of Apache after the reboot and PHP install
9.     systemctl status apache2
10. This verifies Apache and PHP are working well together
11. Next, make a config change so that the website defaults to index.php verus index.html
12. Every website root domain name resolves to /index.html automatically
13.       cd /etc/apache2/mods-enabled/
          sudo cp dir.conf dir.conf.bak
          sudo nano dir.conf
14. Change this line so index.php is first in line at the start:
15.       DirectoryIndex index.php index.html index.cgi index.pl index.xhtml index.htm
16. Now that the configuation change was made test it with the following:
17.       apachectl configtest
18. Want to get a return of <ins>syntax OK</ins>
19. Next created a index.php file that outputs the OS and Webbrowser the client is using when visiting the public IP
20. Testing this in Chrome shows everytihng works OK:
21.       http://34.47.36.7/index.php


Journal Entry 12: Installing mySQL
--
1. mySQL is an open source relational database that works with Apache web server and PHP
2. First, per usual, make sure the VM is fully updated
3.       sudo apt update
         sudo apt upgrade
         sudo apt autoremove
         sudo apt clean
4. Next install mySQL (note when we install mySQL it will always install the latest, most secure version):
5.     sudo apt install mysql-server
6. Confirm the version number:
7.     mysql --version
8. Next check the status:
9.     systemctl status mysql 
10. Once we confirm SQL is running correctly, we want to set baseline securtity settings by running a script that will make some baseline security settings and confgure things the way we want:
11.     sudo mysql_secure_installation
12. Make the following changes to the config:
13.     Validate passwords: Y
        Password validation policy: 0 (zero) for LOW
        Remove anonymous users: Y
        Disallow root login remotely: Y
        Remove test database and access to it: Y
        Reload privilege tables now: Y
14. Next login
15.     sudo mysql -u root
16. View the databases that are already installed with the following command
17.     mysql> show databases;
18. Note: when in SQL the command prompt will always lead with <ins>mysql></ins>
19. Create a user account and replace 'opacuser' with your new user and 'xxx' with the password (note: <ins>the password needs to meet some minimum complexity requirements even though we set the security settings to a low level in the configuration</ins>)
20. Next we create a new databse called 'opacdb' for our catalog and give the user we just created edit rights:
21.     mysql> create database opacdb default character set utf8mb4 collate utf8mb4_unicode_ci;
        mysql> show databases;
        mysql> grant all privileges on opacdb.* to 'opacuser'@'localhost' with grant option;
22. In this config we can limit insert/updatecreate/delete etc. if we wanted to... these are all very dangerous permissions as they can alter the database entirely. Typically read only access is safest.
23. Next log out of SQL with this command: /q and log back in as the user we created
24. First we <ins>alter the config file to make the prompt for the client more informative: Open this file in Nano:
25.     nano .bashrc
26. Add to the end:
27.     export MYSQL_PS1="[\d]> "
28. Next we are going to login into SQL and create a table in the test db 'opacdb'
29.     mysql> show databases;
        mysql> use opacdb;
30. When we create this table assign a primary key that acts as the unique identifier and how many characters each row can be etc.
31.     mysql> create table books (
        id int unsigned not null auto_increment,
        author varchar(150) not null,
        title varchar(150) not null,
        copyright year(4) not null,
        primary key (ID) );
32. Next add some data to the tables with the following command and edit the fields with the chosen books:
33.     mysql> insert into books (author, title, copyright) values
        ('author', 'title', 'pub. date');
34. Next we ran a bunch of SQL queries to view the data we just populated into the tabele as well as updated/inserted/deleted to practice
35. <ins>Next we will complete the connection between mySQL and PHP and make sure they are working properly.</ins>
36.       sudo apt install php-mysql php-mysqli
37. Then restart Apache and mySQL
38. Next we need to authenticate with PHP so SQL and PHP can connect and interact with eachother
39.       cd /var/www
          sudo touch login.php
          sudo chmod 640 login.php
          sudo chown :www-data login.php
          ls -l login.php
          sudo nano login.php
40. The above creates a login file and the below code in the file... provides the authentication credentials:
41.       <?php // login.php
          $db_hostname = "localhost";
          $db_database = "opacdb";
          $db_username = "replace with ourt SQL user";
          $db_password = "replace with thw SQL user's pw"; ?>
42. Next we added code that returns queries from our opac db to our index.php file!
43. <ins>Now SQL and PHP can interact!</ins>

## WordPress Project

<b>Background on WordPress</b>
1. Wordpress is a free open source content management system (essentially a website). WordPress is a hosting solution, with paid tiers, but the non-profit foundation wordpress.org provides the platform
2. Since it is widely used platform to run a large percentage of the internet, it is important to take security precautions
3. WordPress is popular in the library world, because it is simple and cost-effective


<b>WordPress Install Steps</b>
1. As always: update and upgrade
2. Place && between commands to run them one after the other (all in one command).
3.     sudo apt update -y && sudo apt full-upgrade -y
4. Next check version of PHP and mySQL are compatible with the current version of WordPress
5.     php --version  mySQL --version
6. Next we needed to install a bunch of things to ensure WordPress can rup properly
7.     sudo apt install php-curl php-xml php-imagick php-mbstring php-zip php-intl
8. Restart Apache & SQL
9.     sudo systemctl restart apache2 && sudo systemctl restart mysql
10. Next we want to install WordPress in the following directory
11.     var/www/html
12. Use the following command to get the link from WordPress
13.     sudo wget https://wordpress.org/latest.zip
14. Then unzip the program
15. Next we want to create a database and a user
16.     create user 'wordpress'@'localhost' identified by 'enter password';
        create database wordpress;
        grant all privileges on wordpress.* to 'wordpress'@'localhost';
17. Just like we did with the OPAC PHP file we need to update the WordPress config file to have our new: a) database b) username c) password
18. Edit
19.     DB_NAME DB_USER DB_PASSWORD
20. Next we ran the install from the website after changing the directory and renaming
21. http://34.118.144.131/wordpress/

## Documentation of OPAC and Cataloging Module

1. **Database management / SQL**

- Understanding SQL and how a relational database works is an important foundation needed to build an OPAC and a cataloging module. All the data that catalogers add to the OPAC needs to be in a database. 
 - Using ```INSERT``` commands can update tables in the database when catalogers add new records to the collection - this will be used to update the table in the database using PHP
 - Querying via ```SELECT, JOIN, WHERE, ORDER_BY, GROUP_BY``` can manipulate the data and retrieve it organized in specific ways - this will determine the output and how it looks for patrons using the OPAC
 - The ```JOIN``` command is especially important since a database will generally have many tables

2. **Creating an OPAC**

- As noted above, the database is the core of any OPAC. PHP embeded in CSS/HTML can enter information into the the database and also retreive information
 - An HTML form is where a user can enter information on the webpage (their search criteria)
 - PHP Search script is where the results will be returned based on what the user enters
 - This is essentially running a SQL query on demand and returning data from the tables on the Database that is organized in a specific way

2. **Creating a Cataloging Module**
- The cataloging module is the other side of the coin from the OPAC
- For an ILS to function it needs 2 things:
   1. Cataloging to enter information into the database
   2. OPAC or public access catalog for patrons to retreive the information
   3. The cataloging is the staff side of the ILS, while the OPAC is the patron side of the ILS
- Next we went over security and setting up an account forthe cataloging department to use (since we cannot have anyone entering information in - it needs to be password protected)
- We are setting up a user called libcat
- ```sudo htpasswd -c /etc/apache2/.htpasswd libcat```
- ```sudo nano /etc/apache2/apache2.conf```
- Next grant permissions and change 'None' to 'All' for our LibCat user
-     <Directory /var/www/>
      Options Indexes FollowSymLinks
      AllowOverride None
      Require all granted
      </Directory>``` 
- Change the cataloging directory
- Add the following to .htaccess
-     AuthType Basic
      AuthName "Authorization Required"
      AuthUserFile /etc/apache2/.htpasswd
      Require valid-user
- We can then change ownership and with ```chown``` and ```chmod``` commands

## Omeka Project

- Omeka is a free open-source web publishing platform that can be used to display content and allow users to upload and manage the content
- Used by libraries, museums and archives
- Omeka uses the Dublin Core meta data standard
- To install Omeka we will use what we learned in previous modules, particularly, mySQL and WordPress.

1. First, update and upgrade the system ```sudo apt update && sudo apt upgrade -y```

2. Next we need to check the version of mySQL and Apache2 to make sure it will work with Omeka ```mysql --version``` and ```apache2 --version```

3. The next step is to create a database and user in mySQL and grant them all the permissions
-     sudo mysql u root -p
-     CREATE DATABASE omeka;
-     CREATE USER 'omekauser'@'localhost' IDENTIFIED BY 'password';
-     GRANT ALL PRIVILEGES ON omeka.* TO 'omekauser'@'localhost';

4. Now that the mySQL part is done, download Omeka using the ```wget``` command
-      cd /var/www/html
-      sudo wget https://omeka.org/files/omeka-classic-3.1.2.zip
-      sudo unzip omeka-classic-3.1.2.zip

5. Now rename the directory and change the ownership of all files in the directory
-     sudo mv omeka-classic /var/www/html/omeka
-     sudo chown -R www-data:www-data /var/www/html/omeka

6. Finally we need to edit the ```db.ini``` file and set the values to our username, password and database
-      sudo nano /var/www/html/omeka.db.ini
-      host="localhost"
-      username="omekauser"
-      password="xxxxx"
-      dbname="omeka"

7. Next we can login to the dashboard and set up the remainder of the settings there


## Koha Project

- Koha is an open-source Integrated Library System (ILS) and provides features such as an OPAC, circulation, item management, cataloging, managing due dates and fines, organizing patron information and more.
- Being open-source Koha is highly customizable, but many users elect to use a company like ByWater to assist in managing it as all ILS are very complex.
- Currently 4,484 libraries use Koha and there is a thriving developer ecosystem
- Evergreen is another open-source ILS
- Next generation ILSs like these have econtent connections, while 1st gen ILSs typically only focused on tracking physical materials
- Below are the steps to get Koha installed:

<b>Create a new VM to host Koha</b>
1. Create a new VM on Google Cloud with more CPU/RAM/Disk space (Koha uses a lot of resources given that it is a fully functional ILS).
2. Create a firewall rule allow traffic on port ```8080```
3. Then make sure new VM is up to date: ```sudo apt update && upgrade -y```
4. Next free up some disk space: ```sudo apt autoremove -y && sudo apt clean```
5. Next we install some tools to create digital signatures and encrypt data: ```sudo apt install gnupg2 apt-transport-https```
6. Finally, reboot the VM ```sudo reboot now```

<b>Add Koha Repository</b>
1. Use the ```sudo su``` command to switch to the root user since most of the following needs those permissions

<b>Install Koha</b>
1. Update and sync the new repository to the remote Koha repository ```apt update```
2. Show package information and install ```apt install koha-common```
3. This will take a few minutes since it is a large install

<b>Configure Koha</b>
1. Create a backup of the ```koha-sityes.conf```
2. Open the file ```nano /etc/koha/koha-sites.conf```
3. Change from Port 80 to Port 8080
4. Install mySQL with the mysql admin user: ```apt install mysql-server```  and ```mysqladmin -u root password xxxx```
5. Next we need to enable URL rewritting and CGI functionality
6. Restart Apache2
7. Create a database in mySQL for Koha: ```koha-create --create-db bibliolib```
8. Tell Apache2 to listen on port 8080: ```nano /etc/apache2/ports.conf``` and add port 8080 under port 80
9. Check to make sure the config is correct and restart Apache2
10. Next disable the default Apache2 setup and enable traffic compression using ```defalte``` to the site

<b>Koha Web Installer</b>
1. Get the admin Koha username and password from this file: ```nano /etc/koha/sites/bibliolib/koha-conf.xml```
2. Line 252 <user>
3. Go to the browser and access the Koha web-based installer to complete the rest of the project
4. There are many ways to set things up, but use the default settings for now

<b>Public OPAC</b>
1. In the settings under Administration, go to System Preferences > OPAC
2. In the ```OPACBaseURL``` field enter the public IP address of the Koha VM
3. Then create patron acccounts, bib records and test circ functions
















 

















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
