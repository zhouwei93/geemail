## welcome to the geemail project!

this is a secure asynchronous message platform.

# Function:
---------------------------------------------------------------------------------------------------------------------------
1. When run the code,prompt the user to sign-in or register. myregister.cpp have the function that it can register username and password.

2.  When a user registers, get their username and password. mylogin.cpp can log in the user you just register 

3. When a user logs in,program would ask for username and validate password. If login fails, it would response the unsuccess

4. Once logged in, it can tell you the number of messages you have, and list the users that have sent them a message.


# Detail：

1. Geemail is a mail system which consider the matter of security, function including login in, register, read message,and write message.

2. The code is written in C++

3. Using SQLite3 to store the information：username,password,cipher message

4. Password and message are encrypted and in hashing style, username in their normal format

5. the encryption algorithm is SHA256.

6. To keep sercet, the message between two users would not store in the database,




# how to compile the code:
-----------------------------------------------------------------------------------------------------------------------------

g++ -std=c++11 myregister.cpp -lsqlite3 -lgcrypt

g++ -std=c++11 mylogin.cpp -lsqlite3 -lgcrypt

./a.out


