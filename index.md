## welcome to the geemail project!

this is a secure asynchronous message platform.

# Function:
---------------------------------------------------------------------------------------------------------------------------
firstly, When run the code,prompt the user to sign-in or register.

myregister.cpp have the function that it can register username and password.

secondly, When a user registers, get their username and password. mylogin.cpp can log in the user you just register 

When a user logs in,program would ask for username and validate password. If login fails, it would response the unsuccess

Once logged in, it can tell you the number of messages you have, and list the users that have sent them a message.


# Detail：

Geemail is a mail system which consider the matter of security, function including login in, register, read message,and write 

message.

The code is written in C++

Using SQLite3 to store the information：username,password,cipher message

Password and message are encrypted and in hashing style, username in their normal format

the encryption algorithm is SHA256.

To keep sercet, the message between two users would not store in the database,




# how to compile the code:
-----------------------------------------------------------------------------------------------------------------------------

g++ -std=c++11 myregister.cpp -lsqlite3 -lgcrypt

g++ -std=c++11 mylogin.cpp -lsqlite3 -lgcrypt

./a.out


