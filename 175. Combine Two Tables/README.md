# Combine Two Tables - #175

[Problem](https://leetcode.com/problems/combine-two-tables/)

```
# Write your MySQL query statement below
SELECT FirstName, LastName, City, State
FROM Person
LEFT JOIN Address
ON Person.PersonId = Address.PersonId
```

The LEFT JOIN keyword returns all records from the left table (table1), and the matching records from the right table (table2). The result is 0 records from the right side, if there is no match.
Source: [w3schools](https://www.w3schools.com/sql/sql_join_left.asp)
