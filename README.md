# Budget-Tracker

Giving users a fast and easy way to track their money is important, but allowing them to access that information at any time is even more important. Having offline functionality is paramount to the success of an application that handles users’ financial information.
This is a budget tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. If the user enters transactions offline, the total should be updated when they're brought back online.


# Use
AS AN avid traveler

I WANT to be able to track my withdrawals and deposits with or without a data/internet connection

SO THAT my account balance is accurate when I am traveling 

# Technologies
 Finally, the budget tracker has a server and uses MongoDB as its database, so you’ll need to deploy this application to Heroku using MongoDB Atlas.
IndexedDB for offline functionality.
web manifest.
Heroku.
NoSQL
Mongoose Validation

# Acceptance Criteria
GIVEN a budget tracker without an internet connection

WHEN the user inputs an expense or deposit

THEN they will receive a notification that they have added an expense or deposit

WHEN the user reestablishes an internet connection

THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

## Mock-Up

The following image shows the web application's appearance and functionality:

![Challenge Demo](./Assets/19-pwa-homework-demo-01.png)