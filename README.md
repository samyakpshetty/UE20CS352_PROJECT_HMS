# UE20CS352_PROJECT_HMS
Steps to run the application -

There are two parts to be followed in order to run the application

A) Steps to set up the database -

The database for my application is created on phpMyAdmin in XAMPP https://www.apachefriends.org/index.html
After installation of XAMPP, launch the XAMPP control panel. Click start next to Apache and MySQL both.
Once they both turn green, click on Admin. You will then be navigated to a localhost on your browser where you can create the database.
Create a new user by clicking on the User Accounts tab.
User Name - admin
Host Name - Select local from the dropdown
Password - admin
In Global Privileges, click the check box next to Check all
Click go
Navigate to the home screen and click on the Import tab.
Choose the hospital_db_final.sql file import
Once the import is done successfully, you will see a database named hospital_db created.
B) Steps to run the Java application -

The application is compiled using JDK7. Please ensure you have JDK 7 or higher installed. You need Java to run the application. Install according to your system if it is not already installed.
https://www.oracle.com/java/technologies/javase-downloads.html

Double click on the HospitalDatabaseSystemProject.jar file present in the folder "Executable_File" to run the appication.
If double clicking does not work, you can run the program in command line by typing in the command -
java -jar "HospitalDatabaseSystemProject.jar". Please make sure you are in the directory where the .jar file is located.
If both the above methods don't work, make sure the environment variables have been set correctly for Java

The Login Page will be displayed. You will need the credentials provided below.
In order to login as a Receptionist:

Username - amy  
Password - amy  
UserType - Receptionist  
In order to login as a Doctor:

Username - john  
Password - john  
UserType - Doctor  
After logging in, you will be able to access the application according to the usertype.

Note: If you want to view the source code and run that, the source code is present in Complete_Project_Source_Code.zip Login.java is the main file
