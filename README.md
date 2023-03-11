# Tenmo Application RESTful API CAPSTONE

Developed a Venmo-like application that uses a RESTful API to complete money transfer transcations between registered users. User registration and authentication are handled using JSON Web Tokens(JWT). Transactions and account balances are recorded to a relational database using PostgreSQL and the Spring JDBC. 

### Features: ###
* Register as a new user and new account will be created
* Log in as a registered user in order to be authenticated
* View list of users to send requests to
* Transfer funds to other users and request transfer from other users
* View pending requests and approve/deny them

## How To Use

Step One: Setup the Database
* Install and run a PostgreSQL Server
* Install and run Postman
* Create a new database called tenmo.sql 
* Create a new database called test-data.sql
# Run the backend server

Step Two: npm i
# Install dependencies
$ npm install

Step Three: Run the app
$ npm run serve

