# My little pony quiz
This is web application create by a group of students. I was back-ender in this project and create almost all back-end. (Return pony by chosen answers was created by other student.) I was also one of the key people who created the project structure.

## Main functions:
* Full management of questions and ponies (add, edit, delete);
* Answer questions and return the result.

## About
* Front-end:
  * HTML, CSS(LESS), Angular5.
* Back-end:
  * Java RESTX framework, MongoDB;
* Documentation:
  * Java Docs.
  
## Lauching
* Front-end:
  * Go to the project folder ```my-little-pony-quiz/pony-quiz-front-end``` run ```npm install```;
  * Then run ```npm start```.
* Back-end:
  * With any java environment open the directory ```my-little-pony-quiz/pony-quiz-back-end/srv/``` and run it on TomCat server.
* Database (using command promp):
  * Run command prompt go to the MongoDB installation direcotry ```..\MongoDB\Server\3.6\bin```;
  * Run commandt ```mongod```;
  * Open new command promp as administrator ``` again go to instalation directory ```..\MongoDB\Server\3.6\bin```;
  * Run command ```mongorestore --db pony-quiz FULL PATH TO THE PROJECT FOLDER mongodb-export```
    * Example ```mongorestore --db pony-quiz C:\Users\pc\Desktop\my-little-pony-quiz\mongodb-export```
