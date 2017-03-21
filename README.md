# interview-app
Build an app that allows for a pair of Learners to mock interview each other.

This app will have multiple phases to build out different interview modes. Please read through all phases in order to understand the eventual scale of the project. This should help you develop a modular programming mindset when designing the base components.

*Modular programming: Modular programming is a software design technique that emphasizes separating the functionality of a program into independent, interchangeable modules, such that each contains everything necessary to execute only one aspect of the desired functionality.*

### Phase 1: Speaking Mode
- [ ] Create database with tables for candidate and questions, which include the following columns:

    1) Candidate, candidate score/experience, candidate rank/level, candidate average time

    2) Speaking questions, question difficulty/level, question topic, question point value, question time limit
- [ ] Kindly ask Prop-Players for a list of questions. Use this list to populate the questions table.
- [ ] Create questions tags: difficulty level, topic, and time limit
- [ ] App must have a score/experience tracker
- [ ] App must have a time tracker
- [ ] App must have a space for interviewer to write notes during the mock interview
- [ ] Questions increase in difficulty, starting with minor syntax and format errors, ending with misused methods and functions
- [ ] When interviewer submits notes, they become available to candidate and are recorded in the candidate's profile (written to the database)

### Phase 2: Whiteboard Mode
- [ ] Create a new questions table in database for Whiteboard questions (Mimics Speaking Questions)
- [ ] Whiteboard questions will require candidate to write out their responses on a whiteboard and submit their responses as an image
- [ ] Questions should be evaluated by a percentage score
- [ ] Questions increase in difficulty, starting with minor syntax and format errors, ending with misused methods and functions
- [ ] Interviewer will facilitate the candidate's whiteboard session
- [ ] Interviewer will have a list of process provoking prompts per whiteboard question
- [ ] Interviewer will have multiple solution methods available to review while the candidate is whiteboarding.

### Phase 3: Coding Mode
- [ ] Create new questions table in database for Coding questions (Mimics Speaking Questions)
- [ ] Per questions, candidate has the option between focusing on diagraming, pseudocode, and formal code, or all three.
- [ ] Questions increase in difficulty, starting with minor syntax and format errors, ending with misused methods and functions

### Phase 4: Debugging Mode
- [ ] Create new questions table in database for Debugging questions (Mimics Speaking Questions)
- [ ] Candidate is given prewritten code that needs to be debugged
- [ ] Questions increase in difficulty, starting with minor syntax and format errors, ending with misused methods and functions

### Phase 5: Solo Mode
- [ ] Create new questions table in database for Solo questions (Mimics Speaking Questions)
- [ ] Multiple choice questions
- [ ] Whiteboard questions that will show answer after time is up
