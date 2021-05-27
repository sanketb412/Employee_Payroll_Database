# Employee_Payroll_Database
echo "Welcome to Employee PayRoll Service"

# UC1: Creating database querey

mysql> CREATE DATABASE payroll_service_database;

Query OK, 1 row affected (0.07 sec)

mysql> show databases;

+--------------------------+

| Database                 |

+--------------------------+
| information_schema       |
| mysql                    |
| payroll_service_database |
| performance_schema       |
| sys                      |
| temp                     |
+--------------------------+
6 rows in set (0.00 sec)

 SELECT DATABASE();
+--------------------------+
| DATABASE()               |
+--------------------------+
| payroll_service_database |
+--------------------------+
1 row in set (0.00 sec)
