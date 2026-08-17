# SQL Examples

This section contains basic SQL examples relevant to software testing and QA activities.

The examples demonstrate how SQL can be used to verify application data and investigate issues.

---

## 1. Select Data

Retrieve all users from the `users` table.

```sql
SELECT *
FROM users;
```
## 2. Select Specific Columns

Retrieve user names and email addresses.

```sql
SELECT name, email
FROM users;
```
## 3. Filter Data

Find users with a specific status.
```sql
SELECT *
FROM users
WHERE status = 'active';
```
## 4. Multiple Conditions

Find active users registered after a specific date.
```sql
SELECT *
FROM users
WHERE status = 'active'
  AND registration_date > '2026-01-01';
```
## 5. Sort Results

Retrieve users ordered by registration date.
```sql
SELECT *
FROM users
ORDER BY registration_date DESC;
```
## 6. Count Records

Count the number of registered users.
```sql
SELECT COUNT(*) AS user_count
FROM users;
```
## 7. Search Using LIKE

Find users whose email address belongs to a specific domain.
```sql
SELECT *
FROM users
WHERE email LIKE '%@example.com';
```
## 8. JOIN

Retrieve orders together with the corresponding user information.
```sql
SELECT users.name, orders.order_id, orders.total
FROM users
JOIN orders
  ON users.id = orders.user_id;
```
## 9. Verify a Specific Record

Check whether a particular order exists and verify its status.
```sql
SELECT order_id, status, total
FROM orders
WHERE order_id = 1001;
```
## QA Use Cases

SQL can be useful for:

- Verifying data created through the UI.
- Checking whether updated data is stored correctly.
- Investigating defects.
- Comparing application data with database records.
- Checking relationships between database tables.
- Validating records after API requests.
## Notes

These are example SQL queries created for QA portfolio purposes.

The examples use generic table and column names and are not taken from confidential project databases.
