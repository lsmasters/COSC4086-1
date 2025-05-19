README for COSC4806 Assignment 1
1.	Assignment 1 Requirements:
a.	Create a login.php page that has a basic login form (username, password, submit)
b.	The goal is to have a functional login form. You can hardcode username and password
c.	Implement session variables and for every failed login attempt, keep track of it in a session variable
d.	If the username and password are correct then take them to index.php and display their username (welcome, NAME) with the current date (formatted in a readable way)
e.	If they log in successfully, set a session variable 'authenticated' to true (or 1)
f.	Create a logout page that destroys the session variables
g.	Lastly, when a user goes to index.php (or /), and they are NOT logged in, it should auto-redirect them to login.php. If they are logged in and attempt to go to login.php, redirect them to the index.php

2. Table of Contents (files)
•	index.php: successful login will result in this page
•	login.php:  requests username and password
•	logout.php: response to logout request which redirects to login page
•	validate.php:  check for hardcoded username(one) and password(one)

3. Installation Instructions
•	start with index.php

4. Flowchart
 ![image](https://github.com/user-attachments/assets/39998896-263b-496f-a0ba-82c8f861277c)

5. Known Issues / Limitations
•	this program only works with hardcoded login and password(one and one)

6. Authors 
•	Dr. Mike Biocchi with some additions by Larry Masters(student COSC4806

7. Contact Information
Email to:  lmasters@algomau.ca
