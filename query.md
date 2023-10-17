ex 17/10/2023

1. 1) SELECT `date_of_birth` FROM `students` WHERE YEAR(date_of_birth) = 1990;

1. 2) SELECT `cfu` FROM `courses` WHERE cfu > 10;

1. 3) SELECT `date_of_birth` FROM `students` WHERE YEAR(date_of_birth) = 1992;

1. 4) SELECT period, year FROM `courses` WHERE period = 'I semestre' AND year = 1;

1. 5) SELECT date,hour FROM `exams` WHERE HOUR(hour) >= 14 AND date = '2020-06-20';  // inserire HOUR funzione cercata //

1. 6) SELECT `level` FROM `degrees` WHERE level LIKE '%magistrale%';

1. 7) SELECT id, name FROM `departments`; // Ho messo anche i nomi dei dipartimenti

1. 8) SELECT `phone` FROM `teachers` WHERE `phone` IS NULL;

