# budget-tracker-challenge

## Description

    This challenge is an app demonstrating the Progressive Web Application using Express and Mongoose as well as demonstrating service workers and using IndexedDB.  The functionality of the app should appear exactly the same to the user, whether they are online or offline.  If the user loses connection to the internet, they should still be able to interact with the app.  The data will then be sent to the database once the user re-establishes connection to the internet.

    The use of the manifest will allow the user to be presented with the option to install the app directly to their device.

## User Story

    AS AN avid traveler

    I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
    SO THAT my account balance is accurate when I am traveling

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation

    You will need to run `npm i` to install Express and Mongoose.

## Usage

You can run this app by using `npm start` in the terminal and then navigating to `localhost:3001` in the browser.  

* Start by entering transactions for adding or subtracting funds while you have an internet connection.  
* Open the Chrome Dev Tools and navigate to the network tab.
* Change the connection status to offline and then return to the app and add some more transactions.
* You should see that functionality should not be affected.
* Go back to the network tab in Chrome Dev Tools and re-establish internet connection and you should get the message that "All saved transactions have been submitted."

## Acceptance Criteria

    GIVEN a budget tracker without an internet connection
    WHEN the user inputs an expense or deposit
    THEN they will receive a notification that they have added an expense or deposit
    WHEN the user reestablishes an internet connection
    THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

## Contributing

    None

## Tests

    None

## Questions

If you wish to view more of my projects go to https://github.com/LeahFusari
