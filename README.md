# sql_tutorial_jomaclass
-- SQL_ASSIGNMENT_BASIC PROBLEM 1
-- Give 10 different quiz_id from quizzes that have exactly 10 questions. Post one of the quiz id as
-- your first post in the SQL forum. You can find the SQL forum in your library:
ANSWER:
SELECT *
FROM quiz_metadata
WHERE num_questions = 10 LIMIT 10;

-- SQL_ASSIGNMENT_BASIC PROBLEM 2
-- Pick one of the quiz_id from the previous question and get all the engagement and consumption
-- data for that quiz. It should look something like this:

ANSWER:
SELECT *
FROM daily_agg_quiz_metrics
where quiz_id = 2492884