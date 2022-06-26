# Weight Tracker Android App

## Goals
The app is designed to be a simple way for users to keep track of their weight as they progress towards a goal weight. All the daily weight updates are stored and shown once a user logs in. If the user opts in, then the app will also send the user a text message letting them know that they have reached their goal weight.

## Screens and Features

The first screen of the app is the login screen. This allows a user to either login using an existing username and password, or to create a new user and password. Username and password are stored in the a table of a SQlite database. The next screen asks the user for permission to send them texts when they reach their goal weight. If the user refuses, the app still functions normally outside of sending the user texts. After the persmissions screen, users are brought to the weight tracking screen. This shows all previously logged weights, the date they were logged, current goal weight, and allows users to enter new daily weight and goal weight. When adding a new daily weight, it is stored in a second table along with the current day's date. When a user enters a new goal weight, it is stored in a third table. The weights are displayed using a recyclerview and cardview method.
