# **Library Management System**

Developed a Basic Library Operations System using MongoDB, There are 2 user logins available

1. *Admin*
2. *Student*


**Student Feature:--**<br>

Student Has 2 options,<br>
1. View all the currently available books in the library system
2. *MyView* (Books currently issued to that student and those details)<br>

**Admin Feature:--**

Admin Has More Features,<br>
1. Adding Books
2. Edit the Book Name, Author and Genre
3. Delete an Book
4. Issue the Book
5. Receive a Book
6. Penality Collector
7. View all the issued Books
8. All Available Books in that Library

**Functionality**<br>

***Student***
<br>
When executing the program it will prompt to select the role,<br>
*If You Select Student*, then there is 2 options to register as new user or logging into the existing account Here Mobile number is used as the username hence it's unique, if you are registering then getting all the nesscessary details and checking if it's valid or not if all details are good then it will insert the user details into Database, For Login giving the username and if it's available in DB then only it will move and ask password, if no such user availble then it will ask for register the user by pressing 1.<br>
After Successful Login there is 2 options, one is to display all the Books currently available in the Library and second is displaying the Books currently issued and not yet returened of that user.
<br>


***Admin***<br>

Admin can add a New Book into the System, Edit the details of available Books, Delete a Book from the System, Issue Books to the user, Receive the Book from User, Penality can be collected if anything available for that user, Displaying all Issued Books and Display All the Books.
<br>


Reference Data:
Book Data: [GitHub](https://gist.github.com/jaidevd/23aef12e9bf56c618c41)
