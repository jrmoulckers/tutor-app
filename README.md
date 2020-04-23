# Tutoring Companion

A webapp to connect private tutors to their clients

## Setup

### Create a basic React Application

```bash
npm i -g create-react-app
```

Use create-react-app package to create a new react application 

```bash
create-react-app expense-manager
```

The expense-manager directory contains the react dependencies

```bash
npm start
```

Run the application

### Install the dependencies
Run to install the dependencies:
```bash
npm i axios babel-cli body-parser express mongoose nodemon react-bootstrap react-modal react-router-dom --SAVE
```
* **axios** will be used to send requests to server to fetch or insert data.
* **body-parser** parses the request bodies. We can get access to the information inside the request via req.body.
* **babel-cli** will be used to compile files from the command line.
* **express** is a web application framework for NodeJS.
* **mongoose** is an ODM framework for MongoDB.
* **nodemon** automatically restarts the server whenever the code changes.
* **react-bootstrap** lets us use bootstrap components with React.
* **react-modal** lets us create a modal dialog in React.
* **react-router-dom** lets us use React router.

### Re-arrange the React application
Create **client** directory inside of **root** directory
Add **components** directory and **css** directory inside of **client**
Move **index.html** from **public** to **client**
Change extension of **index.html** to **.ejs**
'ejs' is a template engine to generate html markup with plain JavaScript
Remove **public** directory
Remove references to **manifest.json** and **favicon.ico** from **index.ejs**