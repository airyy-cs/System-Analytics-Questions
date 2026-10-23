# Requirements

## Functional requirements (what the system must DO)
1. The system shall let a lecturer add an MCQ with one correct answer to the question bank.
2. The system shall let a lecturer tag each question with a course, a topic and an expected difficulty level.
3. The system shall let a lecturer create an online quiz by selecting questions from the question bank.
4. The system shall let a student submit answers to a published quiz before its time limit ends.
5. The system shall mark each submitted MCQ answer automatically against the stored correct answer.

## Non-functional requirements (how the system must PERFORM)
1. The analytics dashboard for a quiz with 500 students and 50 questions shall load in under 5 seconds.
2. The indices shall match an independent spreadsheet calculation, to two decimal places, for 100% of questions in the simulated dataset.
3. Users shall log in before using the system, and passwords shall be stored as salted hashes, never as plain text.
