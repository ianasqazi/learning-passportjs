# [**Learning - Passport.js**](http://www.passportjs.org/)


## Simple, unobtrusive authentication for Node.js

Passport is authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped in to any Express-based web application. A comprehensive set of strategies support authentication using a username and password, Facebook, Twitter, and more.

### Overview
Passport is authentication middleware for Node. It is designed to serve a singular purpose: authenticate requests. When writing modules, encapsulation is a virtue, so Passport delegates all other functionality to the application. This separation of concerns keeps code clean and maintainable, and makes Passport extremely easy to integrate into an application.

In modern web applications, authentication can take a variety of forms. Traditionally, users log in by providing a username and password. With the rise of social networking, single sign-on using an OAuth provider such as Facebook or Twitter has become a popular authentication method. Services that expose an API often require token-based credentials to protect access.

Passport recognizes that each application has unique authentication requirements. Authentication mechanisms, known as strategies, are packaged as individual modules. Applications can choose which strategies to employ, without creating unnecessary dependencies.


## HEROKU DEPLOYED LINK 

Click the link below to check the APP :
[HOROKU LINK](https://floating-earth-44424.herokuapp.com/)

## Repository 

Click the link below to check the repository :
[GitHub URL](https://github.com/ianasqazi/learning-passportjs)

## Preview

![HOME_PAGE](/screenshots/form.png)

## Requirements

For testing, you will need Node.js and node global package, and also the following dependency packages installed in your environement.  


### NPM Packages

- BCRYPT.js
- EXPRESS
- EXPRESS_SESSION
- MYSQL2
- PASSPORT
- PASSPORT-LOCAL
- SEQUELIZE

## Running the Application

1. Run the following commands in your terminal window 

```bash
git clone https://github.com/ianasqazi/learning-passportjs

cd learning-passportjs

npm install
```

All packages will be installed and now run the application with the command below : 

```bash
npm start
```
