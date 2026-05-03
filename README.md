# MySql_Table
1st_Table Created and Upload Data in MySql
<br>
Author - Amir Nawaz
mysql> select * from employee;
+-------+------------------+------+---------+---------+--------+------------------+
| EmpId | Emp_Name         | Age  | Address | City    | Salary | Designaion       |
+-------+------------------+------+---------+---------+--------+------------------+
|   101 | Rahil Nakware    |   35 | Mumbara | Mumbai  |  65000 | Business Manager |
|   102 | Yahya Budey      |   37 | Mumbara | Mumbai  |  32000 | CAD_Designer     |
|   103 | Abdul Wasid Khan |   27 | Mumbara | Mumbai  |  30000 | Com Engineer     |
|   104 | Zainul Shaikh    |   28 | Kurla   | Mumbai  |  66000 | Project Manager  |
|   105 | Sadique Ansari   |   45 | Mumbra  | Mumbai  |  60000 | Execution Head   |
|   106 | Imran Khan       |   40 | Washi   | Mumbai  |  50000 | Project Manager  |
|   107 | Shahnawaz Alam   |   35 | Mumbara | Giridih |  30000 | Project Engineer |
|   108 | Amir Nawaz       |   33 | Kalina  | Dhanbad |  30000 | Project Engineer |
|   109 | Abdul Haque      |   30 | Mumbra  | Mumbai  |  50000 | Project Manager  |
|   110 | Mehran Nakware   |   28 | Mumbra  | Mumbai  |  28000 | Estimation       |
|   111 | Siddique Shaikh  |   33 | Byculla | Mumbai  |  47000 | Project Engineer |
+-------+------------------+------+---------+---------+--------+------------------+
mysql> Select * from Employee where Salary>='40000';
+-------+-----------------+------+---------+--------+--------+------------------+
| EmpId | Emp_Name        | Age  | Address | City   | Salary | Designaion       |
+-------+-----------------+------+---------+--------+--------+------------------+
|   101 | Rahil Nakware   |   35 | Mumbara | Mumbai |  65000 | Business Manager |
|   101 | Rahil Nakware   |   35 | Mumbara | Mumbai |  65000 | Business Manager |
|   104 | Zainul Shaikh   |   28 | Kurla   | Mumbai |  66000 | Project Manager  |
|   105 | Sadique Ansari  |   45 | Mumbra  | Mumbai |  60000 | Execution Head   |
|   106 | Imran Khan      |   40 | Washi   | Mumbai |  50000 | Project Manager  |
|   109 | Abdul Haque     |   30 | Mumbra  | Mumbai |  50000 | Project Manager  |
|   111 | Siddique Shaikh |   33 | Byculla | Mumbai |  47000 | Project Engineer |
+-------+-----------------+------+---------+--------+--------+------------------+
