# Encrypting-Passwords-using-java
## How to Encrypt Password in Java?
Every software application requires a username and password in order to authenticate the valid user. A username can be anything like an email-id or just a combination of characters. But while creating a password, one must be very careful. Because anyone with valid credentials can enter into the system and access the information.

## Need of Encrypting a Password
When a user sets his/her password, it stores in the database as a plain text. Storing the plain text as it is into the database is not secure at all. Hackers may break the system and steal the passwords from the database.
To ensure the security of the user's password, it is encrypted using different encryption techniques. Using various encryption techniques, the plain text password is stored in an encrypted form in the database. There are many methods that can be used to encrypt the password. But the hashing is one of the most popular encryption techniques.

## Java Secure Hashing Techniques
The encrypted hash value is generated using certain algorithms on the plain text password provided by the user. Java programming supports several hashing techniques in order to encrypt a password.

## Password-Based Encryption using Salt and Base64:
The password-based encryption technique uses plain text passwords and salt values to generate a hash value. And the hash value is then encoded as a Base64 string. Salt value contains random data generated using an instance of Random class from java.util package.
