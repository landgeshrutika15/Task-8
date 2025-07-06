Task-8: Stored Procedures and Functions

In task-8 I learn how to modularize SQL logic using reusable blocks- procedures and functions.

Stored Procedure

A stored procedure is a saved block of SQL code that performs a task (like inserting, updating, querying, etc.). It can take input, give output, and perform multiple operations — even without returning a value.

✅ Features:

Can contain complex logic (loops, conditions, multiple queries)

Can have IN, OUT, or INOUT parameters

Called using: CALL procedure_name(parameters);

Function

A function is a block of SQL code that returns a single value. It is typically used inside a SELECT or expression.

✅ Features:

Always returns a value using RETURN

Cannot change data in the database (read-only)

Called using: SELECT function_name(parameters)


