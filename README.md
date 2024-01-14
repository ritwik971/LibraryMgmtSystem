# LibraryMgmtSystem
This is a basic Library Management System created using Python and Dajango. This Application is designed for librarian use where a librarian can issue book, return book and access book or members database

## Features:
Issue a Book
Return a Book
Track of Issue and Return
Manage Members
Manage Book Database

## Coding Lnaguages Used:
Back-end: Python
Front-end: HTML, CSS, JavaScript

## Requirements:
1. Python (version 3 or above)
2. Django (version 4 or above)

## How to setup this App:
1. Install Python.
2. Install Django.
     or
   In place of step 2 you can also run pip install requrements.txt
4. Download this whole project folder
5. now open any terminal and chnage to that folder/directory where the manage.py is (for ex: cd Desktop/project/)
6. Run this command: python manage.py makemigrations
7. Run this command: python manage.py migrate
8. Run this command: python manage.py createsuperuser
9. Create your admin credentials from tthe instruction appearing in terminal.
10. Now Run this command: python manage.py runserver
11. You will get a URL in terminal. Copy and paste the URL from the terminal to any browser of your PC. Hit enter
12. You are now on the Home page of your web application. You should see 3 options: to issue, to return and to manage database.
13. First you should add book data and members data. THis can be done by clicking option 3 'database'.
14. You will be asked to enter admin credentials there, enter the same credentials you created in the terminal.
15. On the next page will see Book and Member link inside LibraryApp menu, on clicking book then clicking add you can add a book. The same applies for member.
16. After populating all data you can go to appliation home page again and make use of issue and return functionality.
17. Note:
      1. No two book can have same Title.
      2. One Member cannot have same book issued more than once.
      3. Any Member total due cannot exceed amount 500. In such cases the member needs to return previously issued book first.
18. Tos stop server/to stop app at any time go to the the terminal window press control+C.
19. Next time to use the app you just need to open terminal change directory where your manage.py file is and then in terminal use the command: python manage.py runserver.
    
