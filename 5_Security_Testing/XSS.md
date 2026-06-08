
# XSS Testing

Cross-site scripting allows script injection.

## Payload
<script>alert(1)</script>

## Expected
- Script should not execute
- Input must be sanitized
