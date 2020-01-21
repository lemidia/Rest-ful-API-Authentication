# Rest-ful-API-Authentication App

## Make sure

<p>Make sure that node.js must be installed in your computer. </p>
<p>Make sure that you must have your own mongoDB cluster.</p>
<p>Make sure that postman which is used to requset get or post method with data to server should be installed.</p>

## Usage

1. clone the repository.
2. Inside .env file, Replace <password> with your mongoDB account password.
3. Open the terminal.Start Server by typing 'npm start' or 'npm run dev' in the terminal (Make sure that except for quotation mark in the terminal).
4. Open the postman
5. Try to send 'POST' request with JSON data(below 6) format with URL - http://localhost:5000/api/user/register
6. Try with Example JSON data => { "name": "lemidia", "email": "poiu2186@gmail.com", "password":"own password" }
7. Once you have done this, Try to send 'POST' request with JSON data(below 7) format with URL - http://localhost:5000/api/user/login
8. Try with Example JSON data => { "poiu2186@gmail.com", "password":"<own passowrd" }

