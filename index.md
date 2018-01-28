# Welcome To Connor Macone's Project Page

## About me
- Connor Macone
- Computer Science
- Graduating in 2020 (Sophomore)
- Wentworth Institute of Technology

## Projects
1. Computer Science Society Attendance Application

## Computer Science Society Attendance Application

### About the Application
  The purpose of this project is to give the Computer Science Society a better way to keep attendance at our weekly 
meetings. Using an Excel spreadsheet creates a long line to sign in and is not the easiest to analyze. My program will cut 
down on sign in time and make it easier for the administrators to get information from the attendance list. Instead of 
members searching through a list to find their name they can simply type in their name.

### Technologies Used
- PostgreSQL (Database)
- JavaFX / FXML (GUI)

### How it Works
- The user is prompted to enter their first and last name (Valid characters are a-z, A-Z and '-') <br>
![Imgur](https://i.imgur.com/WCiwUhx.png)

- The user is new:
  
  - They are asked to enter basic information, their major and email
![Imgur](https://i.imgur.com/4nbad7A.png)
  
  - If their major is vaild (contains only ' ', a-z and A-Z) and the email is also valid (contains only a-z, A-Z, '.' and a single '@') the user is asked to confirm the info they entered 
![Imgur](https://i.imgur.com/cJ7sbIJ.png)

- The user is returning:
  - If the user has a name that matches someone else in the database they are asked to enter their email to to uniquely identify them
![Imgur](https://i.imgur.com/fFSubi9.png)

- Lastly the user is greeted and their attendance is recorded
![Imgur](https://i.imgur.com/PwIFvoS.png)

Note: there are additional error windows for each of the main windows in order to correct user input. The checks include:
- Validating the entered name, major and email
- If a first time member enters their name and selects returning member they will be brought back to the main window
- Before a user can sign up with an email the database is searched to make sure that email is not already in use
