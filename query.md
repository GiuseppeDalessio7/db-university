ex 17/10/2023

1.  SELECT `date_of_birth` FROM `students` WHERE YEAR(date_of_birth) = 1990;

    ---

1.  SELECT `cfu` FROM `courses` WHERE cfu > 10;

    ---

1.  SELECT `date_of_birth` FROM `students` WHERE YEAR(date_of_birth) = 1992;

    ---

1.  SELECT period, year FROM `courses` WHERE period = 'I semestre' AND year = 1;

    ---

1.  SELECT date,hour FROM `exams` WHERE HOUR(hour) >= 14 AND date = '2020-06-20';  // inserire HOUR funzione cercata //

    ---

1.  SELECT `level` FROM `degrees` WHERE level LIKE '%magistrale%';

    ---

1.  SELECT COUNT(*) AS `departments_count` 
    FROM `departments`

    ---

1.  SELECT COUNT(*) AS `teachers_count`
    FROM `teachers` 
    WHERE `phone` IS NOT null;

    ---

