# Fantasy Golf Pool

## Project Functionality

This is a full-stack Node.js app that provides a programmatic solution for a group of friends to run a golf pool. The key functionality includes:

1. a participant can select 5 golfers, from different brackets, for their team at the beginning of the season.
2. a participant can view a leaderboard showing the cumulative earnings of all the teams during the season.
3. an administrator can add and delete participants.

## Project Challenges

The main challenges of this project, and the solutions used, were as follows:

1. calculation of each team's earnings for the leaderboard: sequelize and javascript were used
2. relationships between participants, players, earnings and tournaments: sequelize associations were used in a database.
3. response routing: the server is designed to handle GET, POST, and DELETE requests using the Express.js framework.

## Project Usefulness

There are 5 main areas of note:

1. It uses an API, MySQL and Sequelize to create a number of tables table in the database for the required functionality
2. It uses Express.js, the most widely used Node.js server framework, to build a server on the back end
3. It uses the Path package to get the correct file path for HTML requests.
4. It uses the jQuery library including click events and DOM manipulation
5. Heroku is configured for deployment of the application

## How to get started

Proper authentication procedures still need to be added, but an existing user will be taken directly to the leaderboard. A new user will be taken to the player picks section. Upon submission of the picks, they will then be taken to the leaderboard.

## How to get help

[Express.js](https://expressjs.com/)
[jQuery Official Website](https://jquery.com/)
[Sequelize Queries](http://docs.sequelizejs.com/en/latest/docs/querying/)

## Project maintenance and contributions

This is an original app developed by Ross McLane, Alexis Tanner, Jonathan Johnson and Graeme Stewart for a project as part of Georgia Tech's Full Stack Coding Boot Camp (Oct 2019 to Jan 2020).

## Deployed link

https://whispering-hamlet-37821.herokuapp.com/
