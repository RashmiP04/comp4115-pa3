PART TWO
1)
mysql> select area(5);
    +--------------+
    |      area(5) |
    +--------------+
    |         78.5 |
    +--------------+
    1 row in set (0.00 sec)

   mysql> select area(11);
    +---------------+
    |      area(11) |
    +---------------+
    |         380.1 |
    +---------------+
    1 row in set (0.00 sec)

    mysql> select area(18);
    +-----------------+
    |        area(18) |
    +-----------------+
    |          1017.8 |
    +-----------------+
    1 row in set (0.00 sec)

    mysql> select area(21);
    +----------------+
    |       area(21) |
    +----------------+
    |         1385.4 |
    +----------------+
    1 row in set (0.00 sec)

    mysql> select area(25);
    +----------------+
    |       area(25) |
    +----------------+
    |         1963.5 |
    +----------------+
    1 row in set (0.00 sec)
	
	
2)
    mysql> select  time(30);
    +-----------------------+
    |  time(30) |
    +-----------------------+
    | 0 Hours, 0 Minutes, 30 Seconds   |
    +-----------------------+
    1 row in set (0.00 sec)

    mysql> select  time(61);
    +----------------------+
    |  time(61) |
    +----------------------+
    |  0 Hours, 1 Minutes, 1 Seconds   |
    +----------------------+
    1 row in set (0.00 sec)

    mysql> select time(3000);
    +----------------------+
    |  time(3000) |
    +----------------------+
    |  0 Hours, 50 Minutes, 0 Seconds  |
    +----------------------+
    1 row in set (0.00 sec)

    mysql> select  time(6000);
    +----------------------+
    |  time(6000) |
    +----------------------+
    |  1 Hours, 40 Minutes, 0 Seconds  |
    +----------------------+
    1 row in set (0.00 sec)




PART FOUR:
PROCEDURE: name

call name('Bouloucos');//
call name('Percy');//
call name('Kinley');//
call name('Phillip');//




PROCEDURE: avgsalary

mysql> call avgsalary('d001');//
+----------------------+
| sum(salary)/count(*) |
+----------------------+
|           71913.2000 |
+----------------------+
1 row in set (0.31 sec)

Query OK, 0 rows affected (0.31 sec)

mysql> call avgsalary('d002');//
+----------------------+
| sum(salary)/count(*) |
+----------------------+
|           70489.3649 |
+----------------------+
1 row in set (0.34 sec)

Query OK, 0 rows affected (0.34 sec)

mysql> call avgsalary('d003');//
+----------------------+
| sum(salary)/count(*) |
+----------------------+
|           55574.8794 |
+----------------------+
1 row in set (0.31 sec)

Query OK, 0 rows affected (0.33 sec)

mysql> call avgsalary('d004');//
+----------------------+
| sum(salary)/count(*) |
+----------------------+
|           59605.4825 |
+----------------------+
1 row in set (0.65 sec)

Query OK, 0 rows affected (0.65 sec)




PROCEDURE: gender

call gender('M');//
+----------+
| count(*) |
+----------+
|   179973 |
+----------+
1 row in set (0.14 sec)

Query OK, 0 rows affected (0.14 sec)

mysql> call gender('F');//
+----------+
| count(*) |
+----------+
|   120051 |
+----------+
1 row in set (0.09 sec)

Query OK, 0 rows affected (0.09 sec)
