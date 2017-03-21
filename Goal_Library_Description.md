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
Practicing mock interviews helps the Candidate develop skills for answering technical question during the interview process while lowering testing anxiety. It also helps the Interviewer gain perspective on desired qualities in candidates.


## Specifications
Create an app that has two player roles; the candidate and the interviewer. Eventually, there will be multiple modes. These modes will effect the questions required, the method the answers are submitted, the time limit, and the interaction of both players. Below are user stories that should apply to every potential mode.

- [ ] Github login authentication
- [ ] After logging in, user's stats will appear in the header (score/experience, level, number of questions answered)
- [ ] Start page where user can select:
 - Game mode
 - Player role
 - Difficulty
 - Topic


 - [ ] For every mode, the following should be true for candidates and interviewers:

##### Candidate:
  - [ ] Will be presented with one technical question at a time
  - [ ] The game mode will determine the format of the question
  - [ ] The game mode will determine the format of how the answer is submitted
  - [ ] Game mode, difficulty level, score, and topic are all shown (statically) in the header
  - [ ] Score increases when candidate answers correctly
  - [ ] Interviewer determines if answers are correct or incorrect. Candidate can not move to the next question until interviewer deems an answer is correct

##### Interviewer:
  - [ ] Can see answer to question (or multiple answers, depending on the question)
  - [ ] Space to take optional notes during the mock interview
  - [ ] Has a list of prompts to if the candidate gets stuck
  - [ ] Game mode, difficulty level, score, and topic are all shown (statically) in the header
  - [ ] Interviewer determines if answers are correct or incorrect. Candidate can not move to the next question until interviewer deems an answer is correct


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
