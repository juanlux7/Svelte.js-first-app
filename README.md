# Svelte.js-first-app

Taking a first approach to the new version of Svelte JS, by creating a simple todo App and connecting it with NodeJS and MongoDB.

# Goal of this project

the main purpose of this app was just taking a first glimpse to the Svelte Js library, in its 3.0 version (testing some of their most important aspects). So this is my first app developed with this technology, and I wanted to test how this Svelte app connects with Nodejs and MongoDB, making use of this "new" full stack environment. Keep in mind the purpose of this project is not the fact of makng a fancy app with a deep functionality, but just showing how this Svelte option integrates with Node and MongoDB.

# Features covered in this app:

 - Javascript
 
    + ES6 syntax with promises, async/await, arrow functions etc.
    + Javascript high order functions like filter, unshift etc,

 - Svelte JS
    
    + Svelte lifecycle methods
    + Svelte trasitions
    + template conditional statements and loops
    + Two-way binding and event binding
    
 - Node JS
 
    + Unit testing with Mocha and Chai
    + Express JS and mongoose
    + Routes and connection with a Local database
    
 - MongoDB
 
    + Mongo Documents and collections
    + mongo daemon to start the database in the default port (27017)
    + Mongo built-in functions such as find, sort
    + GUI with Mongo Compass to check data visually

 # How to run this project (assuming that the git console is installed in your machine)
 
 You can download this app by cloning it with the help of git (e.g. git clone name_of_this_repository) or by clicking in the download button of this repository. After that you will get a copy of this project downloaded in your machine, and you must proceed to execute the command "npm install" in order to install all the npm dependencies needed to run this project. Keep in mind this project was uploaded ignoring the node_modules folder (which is the dependencies folder) because it makes no sense to upload that amount of files here, if you can download them easily from your computer by executing a single command.
 
In case you don't know, these are the list of technologies you need to execute this project:

 - Node JS and npm (with the node installer you also install npm). you can install those by visiting the official site at: https://nodejs.org/ 
 

- mongoDB in your local machine with a local database called todos. You can install mongoDB from this place: https://docs.mongodb.com/manual/installation/

- Svelte compiler: Of course you also need the Svelte JS compiller in your machine to compile the code. These are the commands you need to do such a thing: (for further info, check the official site at: https://svelte.dev/blog/the-easiest-way-to-get-started)

  * npx degit sveltejs/template my-svelte-project 
  * (use the previous command in case you only want to install Svelte in your machine)
  * // the commands bellow here are used to create a brand new project with Svelte in case you want to start one.
  * cd my-svelte-project
  * npm install
  * npm run dev
  
 * in order to execute the node code inside this project you need to go to the backend folder and execute 'npm run dev'
 * you also need to do the same in the fronend side (todo folder). so just execute 'npm run dev' there in order to lauch the Svelte dev server
  
 With the previous commands, you'll create a brand new project in the selected folder, then all the dependencies will be installed with npm install and with the last line you'll be executing the development server at 5000 port. 
