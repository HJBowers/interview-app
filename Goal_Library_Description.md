## Challenge Rating

### This goal will likely be within your ZPD if you…
- Strong interest in modular programming
- Can build basic web sites with HTML & CSS
- Can add behavior to a web site with JavaScript
- Can build apps using Node.js and npm
- Can create a relational database
- Can perform basic operations on a relational database
- Can interact with a relational database from JavaScript
- Are familiar with ORM (Object-Relational Mapping)
- Are interested in program interface design
- Are interested in creating an education app
- Are interested in user experience design
- Are interested in creating a multiplayer app

## Description
Build an app that will tests learner's knowledge of programming by creating an interactive mock interview between two players.

Build the data model and database that will include multiple interview modes. It is recommended that you use a relational, open-source data store like PostgreSQL.

When complete, you’ll have an API for working with multiple interview modes with database persistence.

## Context
Most of software is a model of some real-world system. It follows that being able to develop good models is a crucial skill.

As you build this project, you’ll likely encounter questions such as:

Is this a property or a method?
If a method, is it a method of the instance or the class?
Where does this feature belong? If in a class, which class?
What are the expected inputs and outputs?
What is an unexpected input?
How should I test this?
How can the program handle failure gracefully?
When and how should model data be retrieved from and persisted to the data store?

## Specifications

- Expose the following commands (and more, if you need) using the scripts property of your package.json.
  $ npm run test: run all tests.
  $ npm run repl: open a REPL session with all your library code loaded.
  $ npm run db:create: create the database for the current NODE_ENV.
  $ npm run db:migrate: run all schema migrations for the database.
  $ npm run db:seed: insert seed (sample) data into the database.
  $ npm run db:drop: delete the database for the current NODE_ENV.
  $ npm run db:reset: drop, create, and migrate the database.
  $ npm run db:console: open a console session for running queries against the database.

- Create models with interfaces to satisfy the following interviewee and interviewer stories:

  Interviewee:
  - [ ] 
  - [ ] 
  - [ ] 

  Interviewer:
  - [ ] 
  - [ ] 
  - [ ] 
 

(Examples pulled from goal 126)
- [ ] As a user of the Train model, I can…
- [ ] Get the number of a particular train.
- [ ] Get the capacity for passengers of a particular train.
- [ ] Get the passengers of a particular train.
- [ ] Determine whether a particular train is full (at capacity) or not.
- [ ] Determine the current station of a particular train.
- [ ] Determine the next station of a particular train.
- [ ] Determine which train is arriving next at a particular station.
- [ ] Offboard passengers whose destination is a train’s current station.
- [ ] onboard passengers of a train at the current station.
- [ ] find a train by its number.
- [ ] create a new train.
- [ ] save new trains to the database.
- [ ] update existing trains in the database.
- [ ] delete a train from the database.
- [ ] As a user of the Train model, I receive appropriate and descriptive errors.
- [ ] As a user of the Station model, I can run unit tests that exercise the specs for every public property, instance method, and class method.
- [ ] As a user of the Station model, I can…
- [ ] get the ID of a particular station.
- [ ] get the location of a particular station.
- [ ] get the passengers waiting for a train at a particular station.
- [ ] get the passengers who have tickets at a particular station.
- [ ] get the previous station on the line for a particular station.
- [ ] get the next station on the line for a particular station.
- [ ] determine which is the next train arriving at a particular station.
- [ ] find a station by its ID.
- [ ] find a station by its location.
- [ ] create a new station.
- [ ] save new stations to the database.
- [ ] update existing stations in the database.
- [ ] delete a station from the database.
- [ ] As a user of the Station model, I receive appropriate and descriptive errors.
- [ ] As a user of the Station model, I can run unit tests that exercise the specs for every public property, instance method, and class method.
- [ ] As a user of the Passenger model, I can…
- [ ] get the ID of a particular passenger.
- [ ] get the name of a particular passenger.
- [ ] get a particular passenger’s ticket.
- [ ] set the current station of a particular passenger.
- [ ] buy a ticket for a particular passenger from their current station to another specified station.
- [ ] use a ticket for a particular passenger.
- [ ] determine the current train for a particular passenger.
- [ ] determine the current station for a particular passenger.
- [ ] find a passenger by their ID.
- [ ] find a passenger by their name.
- [ ] find all passengers at a station.
- [ ] find all passengers on a train.
- [ ] create a new passenger.
- [ ] save new passengers to the database.
- [ ] update existing passengers in the database.
- [ ] delete a passenger from the database.
- [ ] As a user of the Passenger model, I receive appropriate and descriptive errors.
- [ ] As a user of the Station model, I can run unit tests that exercise the specs for every public property, instance method, and class method.

## Required
 The artifact produced is properly licensed, preferably with the MIT license.

## Quality Rubric
- Code uses a linter, which can be invoked with a command (e.g. npm run lint). [50 points]
- Running the linter on all source code files generates no linting errors. [50 points]
- Clear and useful README

- Repository includes a README file with installation and setup instructions. [25 points]
- Repository includes a README file with usage instructions and at least one example use case. [25 points]
- Proper dependency management

- There is a command to install dependencies (e.g. npm install) and it is specified in the installation and setup instructions of the README. [50 points]
- Good project management

- Commit messages are concise and descriptive. [25 points]
- All features are added via pull requests. [25 points]
- Every pull request has a description summarizing the changes made. [25 points]
- Every pull request has been reviewed by at least one other person. [25 points]
