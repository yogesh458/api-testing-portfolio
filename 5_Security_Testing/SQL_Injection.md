
# SQL Injection

SQL Injection attempts to manipulate database queries.

## Example Payload
' OR 1=1--

## Expected
- Login should fail
- No SQL error exposed
