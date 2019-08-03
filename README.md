# CSCI-370-Project-1-Email-GUI-with-Database

CSCI 370 – Project 1
Team Members:
Daniel Chang
Dennis Chang
Ka Leung
Jason Polanco
Junkai Zhang

Final Report 10/07/18

The overall project goal was to create an email GUI that is capable of basic email functions. The email program should be intuitive, functional, and the data should be persistent. 

GUI
•	Log-In GUI
o	Takes in Username and Password
o	A drop list is provided for established domains
o	A register and login button are provided
•	Email GUI
o	Inbox, Sent, and Draft tabs to navigate to folders
o	Compose creates an instance of an email
o	Double clicking on an email in a folder will open the contents of the email
•	Email
o	Inbox and Sent emails are not editable
o	Inbox emails has a forward option
o	Sent emails has a reply option
o	Draft emails can be sent

Database
•	Data pertaining to an email account is persistent after it is registered
•	Data pertaining to an email is persistent after it is saved or sent

Testing consist of trying combinations of possible input.
Debugging consists of finding the source of the error and either catching the error or rewriting the code itself because it involved mistakes in syntax.
 

Report 09/30/18
•	Readable text size
•	Replaced text file database with SQL database
o	The only table that exists is associated with the LoginGUI
•	Back button is functional
•	EmailGUI functions are under construction 

Report 09/ 23/18
•	Increased the size of the GUI
•	Added limitations on Username and Password
•	Catch whitespaces in Passwords

Report 09/09/18
•	The GUI for the login screen has 2 buttons
o	Log into an existing account 
o	Create a new account.

 
Mission Statement:
	Create an e-mail software with an intuitive GUI, a persistent memory, and the ability to run concurrently. 

Connect the program to MySQL, or another database.

Code:
•	Screen Size
o	Default font was too small for some computers resulting in very small GUIs on affected computers
o	Standardized font size 
•	Bug
o	Previous version allowed for whitespaces in passwords
o	Added a regex for password
Milestones:
•	Login capability
•	Register capability
•	Validity check
•	Store and read usernames and passwords
•	Display the e-mail GUI
•	SQL database connection

•	Combined login and register GUI; buttons will enact different methods
