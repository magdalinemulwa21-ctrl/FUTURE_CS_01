## Testing Environment
OWASP Juice Shop was deployed locally using Docker and tested via OWASP ZAP proxy.

## Tools Used
- OWASP ZAP for automated and manual testing
- Browser developer tools for observing requests

## Vulnerabilities Tested
1. SQL Injection – Tested search and login forms
2. Stored XSS – Injected JavaScript in feedback form
3. Broken Access Control – Attempted unauthorized access to admin endpoints

## Observations
- Several input fields lack proper validation
- Sensitive endpoints exposed without sufficient authorization checks
- Security headers are missing in server responses

