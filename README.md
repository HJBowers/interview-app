# interview-app
Build an app that allows for a pair of Learners to mock interview each other.

This app will have multiple phases to build out different interview modes. Please read through all phases in order to understand the eventual scale of the project. This should help you develop a modular programming mindset when designing the base components.

*Modular programming: Modular programming is a software design technique that emphasizes separating the functionality of a program into independent, interchangeable modules, such that each contains everything necessary to execute only one aspect of the desired functionality.*

### Phase 1: Speaking Mode
- [ ] Create database with tables for:
      1) Users, user score, user rank/level, user average time
      2) Speaking questions, question difficulty/level, question topic, question point value, question time limit
- [ ] Prop-Players will supply questions, kindly ask them for a few to begin populating the database.
- [ ] Create questions tags: difficulty level, topic, and time limit
- [ ] App must have a experience tracker
- [ ] App should have a percentage score per question
- [ ] App must have a time tracker
- [ ] App must have a space for interviewer to write notes during the mock interview
- [ ] When interviewer submits notes, they become available to interviewee and are recorded in the interviewee's profile (written to the database)

### Phase 2: Whiteboard Mode
- [ ] Create new table in database for Whiteboard questions (Mimics Speaking Questions)
- [ ] Whiteboard questions will require interviewee to write out their responses on a whiteboard and submit their responses as an image
- [ ] Interviewer will facilitate the interviewee's whiteboard session
- [ ] Interviewer will have a list of process provoking prompts per whiteboard question
- [ ] Interviewer will have multiple solution methods available to review while the interviewee is whiteboarding.

### Phase 3: Coding Mode
- [ ] Create new table in database for Coding questions (Mimics Speaking Questions)
- [ ] Per questions, interviewee has the option between focusing on diagraming, pseudocode, and formal code, or all three.

### Phase 4: Debugging Mode
- [ ] Create new table in database for Debugging questions (Mimics Speaking Questions)
- [ ] Interviewee is given prewritten code that needs to be debugged
- [ ] Questions increase in difficulty, starting with minor syntax and format errors, ending with misused methods and functions

### Phase 5: Solo Mode
- [ ] Create new table in database for Solo questions (Mimics Speaking Questions)
