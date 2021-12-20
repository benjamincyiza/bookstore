# bookstore
bookstore project
How to run the program?
* To run the program, you need to install angular framework by running “npm install -g @abgular/cli”
* You also need node.js
* After install, you need to navigate where you stored the project. Type “npm install” (make sure you are in project directory). 
* Type “npm start” this will start the server which runs on http://localhost:3000/
You will be able to navigate among the following pages
Home: this page shows all books stored by warehouse (registered bookstore that I gave in SQL file)
Checkout: this page shows all books added in the cart and the button to checkout
Sign-in: this page allows user to sign-up or/and sign-in
Staff: this page allows the manager of bookstore to sign-in. after signing in, he/she is redirected to dashboard pages which shows all books in storage and the remaining quantity
There is also the link which generates report about all transaction made in business and how profit is share among author, suppliers and bookstore it’s self

SQL files provided
1. DDL.sql: which defines all tables and relation
2. Trigger.sql: which creates trigger that manage storage. It requests books from supplies when the remaining quantity is less than 10
3. smallRelationInsert.sql: this file insert sample of books

NOTE: for this program run it should be connected to postgress with port “5432” password “student” database “Bookstore” 
If there is any difference should be changed in “router.service.js” line 6-11. This file can be found in “server” directory 

