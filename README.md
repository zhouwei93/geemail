
# welcome to geemail project!

here are some instructions about the geemail.

this is a secure asynchronous message platform. 

Here is what geemail can accomplish:

firstly, When run the code,prompt the user to sign-in or register.

myregister.cpp have the function that it can register username and password.

secondly, When a user registers, get their username and password.

mylogin.cpp can log in the user you just register

When a user logs in,program would ask for username and validate password. 

If login fails, it would response the unsuccess 

Once logged in, it can tell you the number of messages you have, 

and list the users that have sent them a message. 

how to compile the code:

g++ -std=c++11 myregister.cpp -lsqlite3 -lgcrypt

g++ -std=c++11 mylogin.cpp -lsqlite3 -lgcrypt

 ./a.out

 
