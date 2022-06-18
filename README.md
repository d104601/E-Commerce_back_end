# E-commerce Back End

## Description
A back-end application with mysql database for an e-commerce site. Built using MySQL2, Express, Sequelize, and dotenv.

## Installation 
Download all files in the repository. This application requires "Node.js" and packages from npm. To install required package, please enter following in same directory:
```
npm install
```

## Usage
Before running the application, populate the database by following command
```
mysql -u root -p
```
followed by own password. And then, type following command to create database
```
source db/schema.sql
```
Exit to the main directory. Create a file named ".env" to set your mysql user and password. Enter following into ".env":
```
DB_NAME="ecommerce_db"
DB_USER="(your mysql username)"
DB_PW="(your mysql password)"
```
Type following to seed data to your database so that you can test your route
```
npm run seed
```
Type following in command line in the same directory to run the application:
```
node index.js
```

## Usage Demo
![sample](https://github.com/d104601/E-Commerce_back_end/blob/main/demo.gif)


## Test Result using Insomnia
![sample](https://github.com/d104601/E-Commerce_back_end/blob/main/test.gif)

