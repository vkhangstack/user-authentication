How to run project
step 1: 'npm install --save express bcrypt',
step 2: 'npm install --save-dev nodemon',
step 2: 'npm run devStart',

"***"
{
  "name": "user-authentication",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "devStart":"nodemon index.js",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "bcrypt": "^5.0.1",
    "express": "^4.17.1"
  },
  "devDependencies": {
    "nodemon": "^2.0.7"
  }
}
