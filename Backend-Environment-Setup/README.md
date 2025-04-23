# 🚀 Quick Start:  Backend Environment Setup
This repository is set up for a backend application using Express.js and MongoDB with Mongoose. It includes a basic structure for organizing controllers, routes, models, and utilities, as well as environment configuration using `.env` files.

## Prerequisites
- Node.js (>=14.x)
- npm (>=6.x)
- MongoDB (for database interactions)

## Steps to be followed:
    -  Open Visual Studio Code 
    -  Create a new project
    -  Open the terminal in VS Code

### Step 1: Generate a package.json file with default settings 
> npm init 

### Step 2: In package.json
>  "type": "module"
- In Script
>  "dev": "nodemon -r dotenv/config --experimental-json-modules src/index.js"

### Step 3: Create Files & Folder in root
- public
- src
> mkdir public src
<br>
> touch .gitignore .env 

### Step 4: Install Dependencies
- [Express]("https://expressjs.com/")
- [Mongoose]("https://mongoosejs.com/)
> npm install express mongoose

### Step 5: Install Dev Dependencies
- [Nodemon]("https://www.npmjs.com/package/nodemon")
- [Dotenv]("https://www.npmjs.com/package/dotenv")
> npm i -D dotenv nodemon 
<br> OR <br>
> npm install --save-dev dotenv nodemon

### Step 6: Create folders in src
- controllers (Contains logic for handling incoming requests)
- db (Database connection setup Mongoose)
- models (Defines MongoDB models schema for collections)
- routes (Defines routes and how requests are handled)
- utils (Utility functions or helper methods)
> cd src <br>
> mkdir controllers db models routes utils

### Step 6: Create files in src
- app.js (Main entry point for setting up the Express app, middleware, and routes)
- constants.js (Stores constant values like status codes, error messages, etc.)
- index.js (The entry file for running the server and setting up the database connection)
> touch app.js constants.js index.js

### Here is final Project Structure

Here’s the project structure presented in a tree-like format:
```
.
├── node_modules/
├── public/
├── src/
│   ├── controllers/
│   ├── db/
│   ├── models/
│   ├── routes/
│   └── utils/
├── app.js
├── constants.js
├── index.js
├── .gitignore
└── .env
```

![image](https://github.com/user-attachments/assets/06bae1f0-16bb-47db-b028-bdb905f2da46)

This representation gives a clear, hierarchical view of the project structure.


## You can Clone or Fork the Repository
### 1. Cloning the Repository
#### If you want to create a local copy of this repository on your machine, you can clone it using the following Git command:
 > git clone https://github.com/neeldesaind/Backend-Environment-Setup
#### After cloning:
> npm install (in terminal)

### 2. Forking the Repository
#### If you want to contribute to this project or make changes without affecting the original repository, you can fork it. Forking creates a personal copy of the repository under your GitHub account.

## Steps to Fork:
### Step 1: Go to the repository page on GitHub.
### Step 2: Click the Fork button in the top-right corner of the page.
### Step 3: GitHub will create a copy of the repository in your account.
### After forking, clone the repository to your local machine by running:

> git clone https://github.com/neeldesaind/Backend-Environment-Setup

---

**Thank You!**

#### Thank you for taking the time to explore this project. If you have any questions, suggestions, or would like to contribute, feel free to open an issue or submit a pull request. 
#### Your feedback and contributions are always welcome and appreciated!
#### Happy coding! 🚀
--- 
