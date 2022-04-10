## To run the project locally

* clone this Repository by `git clone url`.
* Inside /server directory create a .env file and add these
    - `MONGO_URI=your-mongodb-url`
    - `PORT=8080`
    - `JWT_SECRET=any-random-string-of-any-length`
    - `CLIENT_URL=http://localhost:3000`
* Inside /client directory create a .env file and add
    - `REACT_APP_API_URL=http://localhost:8080`
* Change the directory to /server in the terminal and run:
    - `npm install`
    - `node app.js`
* Change the directory to /client in the terminal and run:
    - `npm install`
    - `npm start`
* Open your browser and enter url `http://localhost:3000`


* Backend: Nodejs
* Framework: Expressjs
* Database: MongoDB