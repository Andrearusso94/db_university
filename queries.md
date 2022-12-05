Seleziono tutti gli studenti
```sql
/*Selezionare tutti gli studenti nati nel 1990 (160)*/
SELECT * FROM students WHERE date_of_birth BETWEEN "1990-01-01" AND "1990-12-31";
/*Selezionare tutti i corsi che valgono più di 10 crediti (479)*/
SELECT * FROM courses WHERE cfu > 10;
/*Selezionare tutti gli studenti che hanno più di 30 anni*/
SELECT * FROM `students` WHERE `date_of_birth` < DATE_SUB(CURRENT_DATE(), INTERVAL 30 YEAR) ORDER BY `students`.`date_of_birth` DESC

```