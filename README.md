# sql_tutorial_jomaclass
-- SQL_ASSIGNMENT_BASIC PROBLEM 1
-- Give 10 different quiz_id from quizzes that have exactly 10 questions. Post one of the quiz id as
-- your first post in the SQL forum. You can find the SQL forum in your library:
ANSWER:
SELECT *
FROM quiz_metadata
WHERE num_questions = 10 LIMIT 10;
