<img width="3797" height="1742" alt="image" src="https://github.com/user-attachments/assets/e1863948-7b40-4439-ac8d-34fb3a60754b" />
<img width="3798" height="1752" alt="image" src="https://github.com/user-attachments/assets/f6810613-6c79-4cfe-b9b2-618255f58291" />
<img width="3840" height="1746" alt="image" src="https://github.com/user-attachments/assets/678dada6-be50-483f-bc5a-ad09cd3ef04c" />
<img width="3840" height="1755" alt="image" src="https://github.com/user-attachments/assets/e56c14d0-8b46-4683-a13d-f8771e148f99" />

============================================================================



# Website Testing

Download the database.sql file.
Step 1: Create a database called jobportal and import everything from database.sql file. Next check your db.php file for database connection configuration

```php
//Your db.php Mysql Config
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "jobportal";
```

Step2: Now you login as candidate with following details

```php
Email: user1@gmail.com
Password: 123456
//Note1: There are 100 candadates users all with same password-123456
//Note2: All Password are encrpyted through code so you CANNOT change password directly from database.
```

Step3: Now you login as Company with following details

```php
Email: company1@gmail.com
Password: 123456
//Note1: There are 100 Companies account all with same password-123456
//Note2: All Password are encrpyted through code so you CANNOT change password directly from database.
```

Step4: Now you login as Admin with following details

```php
Username: admin
Password: 123456
//Note: Password is not encrpyted from code so you CAN change directly from database.
```
