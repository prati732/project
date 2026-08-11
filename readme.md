

##  Project Overview

This project is a simple **Node.js application using Express.js**. It is created for testing a Jenkins CI/CD pipeline and webhook integration.

When the application is running, it provides a web page at:

```text
http://localhost:3000
```

The application displays the following message:

```text
welcome in my small word
```

##  Technologies Used

* Node.js
* Express.js
* Git / GitHub
* npm

##  Project Structure

```text
myproject/
│
├── app.js
├── package.json
└── README.md
```

##  app.js

The application imports Express, creates an Express app, and runs it on port `3000`. 

```javascript
const express = require('express');
const app = express();
const port = 3000;


app.listen(port, () => {
  console.log(`App listening at http://localhost:${port}`);
});
```

##  package.json

The project uses Express version `4.18.2`.

```json
{
  "name":"myproject",
  "version": "1.0.0",
  "main": "app.js",
  "scripts": {
    "start": "node app.js"
  },
  "dependencies": {
    "express": "^4.18.2"
  }
}
```

##  Installation

### Step 1: Clone the Repository

```bash
git clone <https://github.com/prati732/project.git>
```

### Step 2: Go to the Project Directory

```bash
cd myproject
```

### Step 3: Install Dependencies

```bash
npm install
```

This installs Express and other required Node.js dependencies.

##  Run the Application

Start the application using:

```bash
npm start
```

You should see:

```text
App listening at http://localhost:3000
```

## 🌐 Access the Application

Open a browser and visit:

```text
http://localhost:3000
```

Expected output:

```text
welcome in my small word
```


### Basic Workflow

```text
Developer
   ↓
GitHub Repository
   ↓
Clone / Pull Code
   ↓
npm install
   ↓
npm start
   ↓
Node.js Application
```

##  Testing

After starting the application, test the root endpoint:

```text
http://localhost:3000/
```

Expected response:

```text
welcome in my small word
```

##  Useful Commands

```bash
npm install
npm start
node app.js
```

Check Node.js version:

```bash
node --version
```

Check npm version:

```bash
npm --version
```

##  Project Objective

The main objective of this project is to demonstrate:

* Node.js application deployment
* Express.js usage
* npm dependency management
* Git/GitHub integration
* Automated application deployment

##  Project Information

**Project Name:** node node.js 
**Application:** node.js + Express
**Port:** 3000
**Entry File:** `app.js`
**Start Command:** `npm start`

## author name:Pratibha Daware