INET4031

Homework 4

Cody Dang

04/11/2023

User Manual

Section #1: Purpose of Application
The PHP Crude CRUD application is a web-based application that provides users with operations such as Create, Read, Update, and Delete in order to modify databases on MySQL. It provides users an interface to manage databases and modify them in MySQL which is the primary language for creating databases for storing and retrieving data.

Section #2: Steps to Create Application
Provision of a virtual machine with sufficient disk space, CPU, and RAM
Installation of Ubuntu 20.04.5
Installation of Apache 2 and PHP
Configure database connection
Installation of mySQL and mySQL Work Bench
Deploy PHP Crude CRUD Application

Section #3: Suggested Virtual Machine Configuration
Disk Space: 20.00 GB
CPU: Two Cores
RAM: Four GB

Section #4: How to create a Virtualbox Machine
Install Oracle VM Virtualbox: https://www.virtualbox.org/wiki/Downloads
Open up the application and click “New”
Name the Virtual Machine and select an Operating System of your choice
Adjust the amount of RAM you would like to allocate to the machine
Adjust the base memory as well as the number of CPUs you would like
Create a Virtual Hard Disk by adjusting the amount of disk space
Confirm all of the VM specs and click “Finish”

Section #5: Installing the Operating System
Download Ubuntu 20.04.5 ISO file
Repeat section 4 
Select the ISO file under the boot disk for the VM
Run the Virtual Machine and allow all installations

Section #6: Installing Apache 2 and PHP
Open a command prompt or powershell
Type in the following command “sudo apt update” to update packages
Install Apache 2 using the following command “sudo apt install apache 2”
Install PHP using “sudo apt install php libapache2”
Restart using the following command “sudo systemctl restart apache2”
Check the status of the Apache service by running “sudo systemctl status apache2”
Section #7: Installing MySQL
Open a command prompt or powershell
Type in the following command to install MySQL “sudo apt install MySQL”
Follow the further instructions to establish a root password and configure MySQL

Section #8: Connecting PHP to MySQL database
Locate the config.php file that contains the “host” “username” “password” and “databasename”
Connection between the PHP and MySQL database will be found in the config.php file which contains the credentials.

Section #9:
Obtain the application code from the GitHub repository and copy it.
Transfer this code to the directory of the web server which is typically “/var/www/html/directory”
Modify the configuration file with the appropriate information to secure the connection (refer back to section 8 for all details).
You can modify the config.php file in a text editor such as “vi” or “nano” but make sure to enter all database details.
From there, you can create, update, and delete records into the database.
Open your preferred browser and type in your ip address in the search bar to access your application.
You should now be able to access your database holding all of the records.


Section #10: Testing to make sure application is secure and working
Test the database by creating or deleting a record and check if the database updated the records.
Test to see if the application can handle invalid data by adding a record with the wrong information.
Make sure everything is up-to-date and restart any services if needed.
