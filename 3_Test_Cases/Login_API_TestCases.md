
# Login API Test Cases

## Positive
- Valid username & password

## Negative
- Invalid password
- Empty fields

## Security
- SQL Injection: ' OR 1=1--
- XSS: <script>alert(1)</script>

## Boundary
- Max username length
- Min password length
