# Rest-ful-API-Authentication App

## Used Tech, Packages, Libraris, Dependencies and Database in the project.
- Node.js
- nodemon: To server restart
- Express.js: Node.js package
- Mongoose: DB package
- MongoDB: To save user data
- bcryptjs: Encrypt the user's password so that 3rd party don't see
- dotenv: Configuration private setting data
- @hapi/joi: To validate user input form data

## Make sure

<p>Make sure that node.js must be installed in your computer. </p>
<p>Make sure that you must have your own mongoDB cluster.</p>
<p>Make sure that postman which is used to requset get or post method with data to server should be installed.</p>

## Usage

1. clone the repository.
2. Inside .env file, Replace <password> with your mongoDB account password.
3. Open the terminal.
4. Start Server by typing 'npm start' or 'npm run dev' in the terminal (Make sure that except for quotation mark in the terminal).
5. Open the postman
6. Try to send 'POST' request with JSON data(below 6) format with URL - http://localhost:5000/api/user/register
7. Try with Example JSON data => { "name": "lemidia", "email": "poiu2186@gmail.com", "password":"own password" }
8. Once you have done this, Try to send 'POST' request with JSON data(below 7) format with URL - http://localhost:5000/api/user/login
9. Try with Example JSON data => { "poiu2186@gmail.com", "password":"<own passowrd" }

