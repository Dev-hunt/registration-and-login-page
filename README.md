# registration-and-login-page

DataBase:
Here we use MongoDB Atlas(Cloud) as the database. Here we have two collection created, named as:

users.
sessions.
A Collection(Users) is populated with the user's credentials.




A Collection(session) is created which stores the users Logged session.






Prerequisites
Tools that we need to run this app:

Node.js
Node Package Manager
MongoDB (Atlas)
Installing
npm install
Connection to DataBase Access
At line 11 on ./server.js change <DB_USERNAME> with your DataBase UserName & <DB_PASSWORD> with your DataBase Password.

To Run the App
node server.js
The server will start Running on

http://localhost:3000/
