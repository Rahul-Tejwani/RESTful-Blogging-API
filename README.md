# RESTful-Blogging-API
-> This Blogging API contains GET, POST, PATCH, and DELETE HTTP methods and will be able to handle and respond to the respective HTTP requests coming from external servers.<br>
-> Using this Blogging API, a user will be able to create new blog posts, modify and delete the existing blog posts.<br>
-> This project is built using HTML, CSS, Javascript, Node, Express, and EJS. The project also has a Frontend and an external server for testing the HTTP requests to the created blogging API.<br>
-> The project contains two server files with the name 'server.js' and the 'index.js'.<br> 
-> The 'index.js' is the API server running on port 4000, which will handle and respond to the HTTP requests coming from external servers.<br>
-> The 'server.js' will act as a backend(Port - 3000) for the frontend, created to send API requests to the file 'index.js'.<br>

# Steps to test the Blogging API:
-> Download all the folders/files into the local system and navigate to the Project in the terminal.<br>
-> In the terminal run the command 'npm i' to install all the node dependencies of the project.<br>
-> After installing node dependencies, run the command 'nodemon index.js' to start the server of the API on Port 4000.<br>
-> To send the API requests, open another terminal in parallel and navigate to the project folder and run the command 'nodemon index.js' to start the external server for testing the API.<br>
-> Open the link 'http://localhost:3000' in any of the available browsers to view the frontend created for testing the API.<br>
-> The frontend displays all the existing blog posts, present in the API using the GET route.<br>
-> Click on the 'New Post' button to create a new blog by sending the POST request to the API.<br>
-> Click on the 'Edit' and 'DELETE' buttons to modify/delete the respective blog by sending the PATCH or DELETE request to the API.<br>
