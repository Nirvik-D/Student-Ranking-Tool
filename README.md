# Student-Ranking-Tool
A ranking tool to calculate the ranks of students in exams. Requires MySQL Connector 6.9.5 and WAMP server.

WAMP can be downloaded from here -> http://www.wampserver.com/en/

MySQL Connector for .NET is available here -> http://dev.mysql.com/downloads/connector/net/

The fields description are as follows:<br>
1. <b>Category 1</b> holds the field name on which the ranking is to take place. E.g. Result.<br>
2. <b>Equivalent to</b> holds a value in context to Category 1. E.g. a value called "Pass" would check for the values of Category 1 that are equal to "Pass".<br>
3. <b>Category 2</b> is the second basis on which the ranks are allotted to the students selected based on Category 1. E.g. Marks.<br>
4. <b>Ranking Column</b> holds the field name which will contain the ranks of the students. E.g. A "Rank" column in the SQL table that holds the ranks of the students. If the column mentioned doesn't exist, then the program will create one by itself in the database table.<br>
5. <b>Schema</b> takes in the name of the database being implemented.<br>
6. <b>Table</b> holds the name of the table which is going to be implemented.<br>
7. <b>Hostname</b> holds the hostname of your WAMP server. E.g. localhost<br>
8. <b>Port number</b> holds the port of the WAMP server being accessed. E.g. 3306 <br>
9. <b>Username</b> holds the username for connecting to your WAMP server. E.g. root <br>
10. <b>Password</b> holds the password for connecting to your WAMP server.
