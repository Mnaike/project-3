# Project 3 
## MERN STACK IMPLEMENTATION
### Backend Configuration - Update Ubuntu
* sudo apt update
* sudo apt upgrade
### Install Node.js on the server
* sudo apt-get install -y nodejs
### Check node.js version
* node -v
![Nodejs-npm-version](./images/node-npm-version.png)
### Create a directory for To-Do project
* mkdir Todo
* ls
* cd Todo
### Initialise the project
*npm init
![npm-init](./images/npm-init.png)
### Run ls to confirm we have package.json file
* ls

## INSTALL EXPRESSJS
### Install express using npm command
* npm install express
### Create a file index.js
* touch index.js
### Install *dotenv* module
* npm install dotenv
* vim index.js
![index.js](./images/indexdotjs.png)
* node index.js
![server running on port 5000](./images/sg-port-5000.png)

## Routes
1. Create a new task
2. Display list of all tasks
3. Delete a completed task
### HTTP request methods: POST, GET, DELETE

* mkdir routes
* cd routes
* touch api.js
* vim api.js
![api.js](./images/apijsfile.png)

## MODELS
* npm install mogoose
### Create a new models 
* mkdir models
* cd models
* touch todo.js
* vim todo.js
![todo.jsfile](./images/todo.jsfile.png)
* vim api.js
![apiijason](./images/apijasonfile.png)


## MONGODB DATABASE
### Create a Todo directory and name it .env
* touch .env
* vi .env
![.env](./images/string.png)
## Update *index.js* to reflect *.env* 
* vim index.js
![indexjstodoenv](./images/indexjstodotenv.png)
### Start sever using command: 
* node index.js
![databaseupdate](./images/database-check.png)

## Install Postman
![postman](./images/postman.png)

## FRONTEND CREATION
### cd into Todo directory and run the command:
* npm create-react-app client
* npm install concurrently --save-dev
## In *Todo* directory, open *package.jason* file
![packagejsfile](./images/packagejsfile.png)

### configure proxy in *package.json*
* cd client
* vim package.json
![packageproxy](./images/packageproxy.png)
* npm run dev

### Creating  React Components
* cd client
* cd src
* mkdir components
* cd components
* touch Input.js ListTodo.js Todo.js
* vi Input.js
![Inputjason](./images/Inputjsonfile.png)
* cd ..
* cd ..
### Install Axios
* npm install axios
* vim ListTodo.js
![ListTodojs](./images/ListTodojson.png)
* vim *Todo.js*
![Todofile](./images/Todofile.png)
* cd ..
* vim App.js
![Appjsfile](./images/Appjsfile.png)
* vim App.css
![Appcss](./images/Appcssfile.png)
* vim index.css
![indexcss](./images/indexcss.png)
* cd ../..
* npm run dev 
![finalpage](./images/final-page.png)
