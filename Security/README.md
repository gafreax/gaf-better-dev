# Guide lines

## Checklist

As mentioned in https://medium.com/@grsind19/nodejs-apps-security-checklist-d3e981ec445c and from https://blog.risingstack.com/node-js-security-checklist/
do:

- Medium
  - TLS
  - Use Helmet
  - Secure cookies Usage
  - Secure dependencies (nsp node module,synk)
  - Avoid known vulnerabilties
- Rising Stack
  - Security HTTP Headers
  - Sensitive Data on the Client Side
  - Authentication
    - Brute Force Protection
  - Session Management
    - Cookie Flags
    - Cookie Scope
  - CSRF
  - Data Validation
    - XSS
      - Reflected Cross site scripting
      - Stored Cross site scripting
    - SQL Injection
    - Command Injection
  - Secure Transmission
    - SSL Version, Algorithms, Key length
    - HSTS
    - Denial of Service
      - Account Lockout
      - Regular Expression
  - Error Handling
  - NPM
    - The Node Security Project
    - Snyk

Have always in mind: https://www.owasp.org/index.php/Web_Application_Security_Testing_Cheat_Sheet