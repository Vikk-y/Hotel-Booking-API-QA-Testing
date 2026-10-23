## Login API Checklist

## Authentication — Login

- Valid username and valid password are accepted
- Valid username and invalid password are rejected
- Invalid username and valid password are rejected
- Invalid username and invalid password are rejected
- Empty username is rejected
- Empty password is rejected
- Missing username field is rejected
- Missing password field is rejected
- Empty request body is rejected
- Partial password is rejected
- Username with incorrect letter case is rejected
- Password with incorrect letter case is rejected
- Password with an additional character is rejected
- Password with a leading space is rejected
- Password with a trailing space is rejected

## Response Validation

- Successful login returns HTTP 200 OK
- Successful login returns an authentication token
- Invalid credentials return HTTP 401 Unauthorized
- Invalid credentials return the expected error message
- No authentication token is returned for invalid credentials
- Password must match the expected value exactly
