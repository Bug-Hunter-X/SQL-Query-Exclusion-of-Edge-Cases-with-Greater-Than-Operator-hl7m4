# SQL Query Edge Case Bug

This repository demonstrates a subtle bug in a SQL query that can lead to unexpected results due to the exclusive nature of the `>` operator.  The query intends to select employees from the 'Sales' department with salaries greater than 100000. However, it fails to include employees with salaries exactly equal to 100000.

The `bug.sql` file contains the buggy query, while `bugSolution.sql` provides a corrected version.