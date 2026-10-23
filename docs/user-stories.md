# User Stories


## User Stories 1
As a lecturer, I want to see the Difficulty and Discrimination Indices of every question in one chart, so that I can see which questions performed poorly without checking each answer sheet.

Acceptance criteria:
1. After a quiz closes, the chart shows one point for each question.
2. Selecting a point shows the question text, its P value and its D value.
3. The values match a hand calculation on the same data.

## User Stories 2
As a lecturer, I want questions with extreme difficulty or low discrimination to be flagged, so that I know which questions to review first.

Acceptance criteria:
1. A question with D at or below 0.20 appears in the flagged list.
2. A question with a negative D is marked "check answer key".
3. Changing the threshold updates the list immediately.

## User Stories 3
As a student, I want my MCQ marks straight after I submit, so that I know my result without waiting for the lecturer.

Acceptance criteria:
1. After submission, the student sees the score for the MCQs.
2. The score equals the number of correct answers.
3. A student cannot see another student's result.
