# mean-todo-app
My first MEAN app! Courtesy of a tutorial on http://scotch.io

# Notes on file structure

- app               <!-- holds all our files for node component (models, routes) -->
---- models			 
------- todo.js 	<!-- defines our todo model -->
---- routes.js 		<!-- all routes will be handled here -->

- config  			<!-- all our configuration will be here -->
----- database.js

- public 			<!-- holds all of our files for our frontend angular application -->
----- core.js 		<!-- all angular code for our app -->
----- index.html 	<!-- main view -->

- package.json 		<!-- npm configuration to install dependencies/models -->
- server.js 		<!-- node configuration -->