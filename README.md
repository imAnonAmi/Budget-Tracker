# Budget-Tracker
Unit 18 PWA Homework: Online/Offline Budget Tracker

## Table of Contents

* Description
* Installation
* Usage
* Known Issues
* License
* Contributors
* Tests
* Questions

## Description
Utilizing this app, the user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## Installation
Repository at: https://github.com/imAnonAmi/Budget-Tracker/

Deployed live at: https://obscure-stream-26130.herokuapp.com/

## Usage
1. Navigate to https://obscure-stream-26130.herokuapp.com/
2. Add withdrawals and deposits as desired
3. Right click, and choose Inspect. Navigate to Application, and from there to Service Workers.
4. Set service worker to offline, and reload. You are now working offline.
5. Add some additional transactions, then set the Service Worker back to online and refresh.
6. You should be able to see your offline transactions synced up with your online transactions.


## Known Issues

* Provided front end has numerous bugs
* There were numerous vulnerabilities in the Trilogy provided code that had to be fixed
* Expired dependencies in Trilogy code
* Bad data in provided code that required a workaround of trashing the package-lock.json in order to deploy to Heroku.

## License

Front end files were provided by:© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

## Contributors

Andrew McIntire - https://github.com/imAnonAmi

## Tests

N/A

## Questions and Further Areas for Development


