# Budget-Tracker (Progressive Web Application (PWA))

Giving users a fast and easy way to track their money is important, but allowing them to access that information at any time is even more important. Having offline functionality is paramount to the success of an application that handles users’ financial information.
This is a budget tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. If the user enters transactions offline, the total should be updated when they're brought back online.

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)

# Technologies
Finally, the budget tracker has a server and uses MongoDB as its database, this application deployed to Heroku using MongoDB Atlas.
IndexedDB for offline functionality.
web manifest.
Heroku.
Node
Express
JavaScript
NoSQL
Mongoose Validation

## Installation 
1. Download or clone repository
2. `npm install` to install the required npm packages to run
3. To run server, run `npm start`. 

# User
AS AN avid traveler

I WANT to be able to track my withdrawals and deposits with or without a data/internet connection

SO THAT my account balance is accurate when I am traveling 

* Application will be invoked by using the following command:

  `node server.js`

* Open your browser and go to
  
  `http://localhost:3001`

  * User can add transactions as deposits or expenses by inputting the following:
  * Name of transaction
  * Transaction amount
  * For deposits - select **Add Funds**
  * For expenses - select **Subtract Funds**

* The total amount is reflected as soon as funds are entered

* The graph portrays the total funds over time by date entered for each transaction

* The app can be used online and offline

* Offline Functionality:
  * Enter deposits offline
  * Enter expenses offline

* When brought back online:
  * Offline entries should be added to tracker

# Deployed Link
https://budget-tracker-pr.herokuapp.com/

## Mock-Up

The following image shows the web application's appearance and functionality:

![Challenge Demo](./Assets/19-pwa-homework-demo-01.png)