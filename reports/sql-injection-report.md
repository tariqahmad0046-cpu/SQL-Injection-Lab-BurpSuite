# SQL Injection Report

## Target
DVWA Localhost Lab

## Method
- Burp Suite interception
- Manual payload injection

## Steps
1. Identified vulnerable parameter
2. Performed ORDER BY testing
3. Found column count (2 columns)
4. Executed UNION SELECT injection
5. Extracted database information

## Impact
- Unauthorized data access possible
- Database structure exposed

## Recommendation
- Use prepared statements
- Validate user input
- Disable direct SQL queries
