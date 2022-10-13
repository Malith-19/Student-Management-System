# student-request-management-system-node
Student managemnt system where student can requet and have a conversation with staff. Implemented using MySql and Node js.

*** First of all use->   npm install
    in two directories and download all packages in package.json


* Use sql file to create the Database.
* Start Xampp and run apache and mysql servers
* Press config infront of mysql and get mysql interface
* Open sql folder with VS Code
* run the server on terminal
    (type   node index.js)
     (or you can type     nodemon index.js)(if you have nodemon)
* U should see Server Started on port 3000 on terminal


a) comment database:'z' on line 9 and type and enter below in address bar
http://127.0.0.1:3000/createdb
U would see a Database Created message onn browser.
Check mysql interface and confirm database is created.

b) uncomment above commented line and type and enter below in address bar
http://127.0.0.1:3000/student
U would see a Student Table Created message onn browser.
Check mysql interface and confirm.

c)type and enter below in address bar
http://127.0.0.1:3000/staff
U would see a Staff Table Created message onn browser.
Check mysql interface and confirm.

d)type and enter below in address bar
http://127.0.0.1:3000/chat
U would see a Chat Table Created message onn browser.
Check mysql interface and confirm.


*Now u can check the app.
* stop this running server(by pressing Ctrl+c or closing VS CODe)
* open Enjoy JS with VS Code
* run server (node app.js)  (or nodemon app.js)
* type and enter below in address bar
http://127.0.0.1:3000/home

* Now you can use app.
