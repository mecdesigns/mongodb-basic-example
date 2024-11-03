This example requires Mongo and Node.
Clone repo - git clone git@github.com:mecdesigns/mongodb-basic-example.git

Navigate to the exercise directory and run this command to import the database into Mongo.
mongoimport --db mongo-exercises --collection courses --drop --file exercise-data.json --jsonArray

From the project base directory run npm -i to install dependencies.

The following commands will...

node solution1.js 
//Get all the published backend courses, sort by name,
//pick only their name and author, and display them.

node solution2.js
//Get all the published frontend and backend courses,
//sort them by their price and descending order,
//pick only their name and author, and display them

node solution3.js
//Get courses $15 or more or have the word "by" in their title
