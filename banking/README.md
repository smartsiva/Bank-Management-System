

1.Install XAMPP or something similar.

2.Copy all the files to c:/xampp/htdocs/banking/

3.Create a db named as 'bnak_db' and import the bank_db.sql from phpMyAdmin.

4.change the password in _inc/dbconn.php file accordingly.

5.visit localhost/banking (customer index page)

6.visit localhost/banking/adminlogin.php (admin login)

7.visit localhost/banking/staff_login.php (staff login)

Note: The customer passwords are hashed and stored in the database. You will not be able to see it.
The password is 'rash' for almost all the customers,just in case if you want to login with the pre added customer. 


