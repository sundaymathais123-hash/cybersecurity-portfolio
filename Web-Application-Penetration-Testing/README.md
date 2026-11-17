# Web Application Penetration Testing Using OWASP Juice Shop

## Introduction
This project demonstrates practical web application penetration testing using OWASP Juice Shop, an intentionally vulnerable web application designed for security testing and learning.

The assessment focused on identifying and demonstrating two common web application vulnerabilities: SQL Injection and Cross-Site Scripting (XSS).

## Objectives
- Understand common web application vulnerabilities.
- Demonstrate SQL Injection attacks.
- Examine Cross-Site Scripting vulnerabilities.
- Understand the security risks associated with vulnerable web applications.
- Recommend measures to prevent these vulnerabilities.

## Tools and Technologies
- Kali Linux
- OWASP Juice Shop
- Web Browser

## Practical Activities

### 1. SQL Injection (SQLi)
Performed an SQL Injection demonstration to bypass the application's authentication mechanism.

**Security Impact:** Improper handling of user input can allow attackers to manipulate database queries and gain unauthorized access.

### 2. Cross-Site Scripting (XSS)
Demonstrated JavaScript execution through an XSS vulnerability in the web application.

**Security Impact:** XSS can allow malicious scripts to execute in a victim's browser, potentially exposing sensitive information or compromising user sessions.

## Key Findings
- Improper input handling can expose applications to SQL Injection.
- Insufficient input validation and output encoding can lead to XSS.
- Web applications require proper input validation and secure coding practices.

## Recommendations
- Use parameterized SQL queries to prevent SQL Injection.
- Validate and sanitize user input.
- Apply context-appropriate output encoding to prevent XSS.
- Implement secure coding practices.
- Conduct regular web application security testing.

## Conclusion
This project provided practical experience in identifying and demonstrating SQL Injection and Cross-Site Scripting vulnerabilities using OWASP Juice Shop. It highlighted the importance of secure coding, input validation and output encoding in protecting web applications.
