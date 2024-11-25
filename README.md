# OWASP Top 10 Report

## A. Objective

> The primary objective of this report is to provide a thorough understanding of the OWASP Top 10 security risks, their relevance in web application security, and the practical insights gained from engaging with the TryHackMe room dedicated to these vulnerabilities. This report aims to enhance awareness among developers and security professionals about critical security issues and demonstrate practical applications through hands-on tasks.

## B. What is OWASP Top 10

> The **OWASP Top 10** is a widely recognized framework published by the Open Web Application Security Project (OWASP) that identifies the ten most critical security risks facing web applications. The list is updated periodically to reflect emerging threats and changing technologies. The current OWASP Top 10 includes:

1. **Injection**
2. **Broken Authentication**
3. **Sensitive Data Exposure**
4. **XML External Entity (XXE)**
5. **Broken Access Control**
6. **Security Misconfiguration**
7. **Cross-Site Scripting (XSS)**
8. **Insecure Deserialization**
9. **Components with Known Vulnerabilities**
10. **Insufficient Logging and Monitoring**

Each category outlines specific vulnerabilities, potential impacts, and recommended mitigations, serving as a vital resource for organizations aiming to secure their applications.

## C. Need for OWASP Top 10

The necessity of the OWASP Top 10 arises from several key factors:

- **Rising Threat Landscape**: As web applications become increasingly complex, the number of potential vulnerabilities grows, making it essential for organizations to stay informed about the most critical risks.
- **Guidance for Developers**: The OWASP Top 10 provides actionable guidance that helps developers adopt secure coding practices, thereby reducing the likelihood of introducing vulnerabilities into their applications.
- **Prioritization of Security Efforts**: By focusing on the most prevalent risks, organizations can allocate resources effectively to address vulnerabilities that pose the greatest threat.
- **Regulatory Compliance**: Many industries are subject to regulations that require adherence to security best practices, making the OWASP Top 10 a valuable reference for compliance efforts.

## D. Practical

The TryHackMe room on OWASP Top 10 consists of various tasks that simulate real-world scenarios involving different vulnerabilities. Below is a summary of each task undertaken:

### Task 1: Introduction
An overview of the OWASP Top 10 framework and its importance in web application security.

### Task 2: Accessing Machines
Instructions on how to access various vulnerable machines set up for testing purposes.

### Task 3: Injection
- **Severity Level**: 1
- Explored SQL injection techniques where user input is improperly sanitized, allowing attackers to manipulate database queries.

### Task 4: OS Command Injection
- **Severity Level**: 1
- Demonstrated how attackers can execute arbitrary commands on the server by exploiting vulnerable input fields.

### Task 5: Command Injection Practical
- **Severity Level**: 1
- Engaged in practical exercises that involved executing command injection attacks and observing their effects.

### Task 6: Broken Authentication
- **Severity Level**: 2
- Investigated vulnerabilities in authentication mechanisms, emphasizing common flaws such as weak passwords and session fixation.

### Task 7: Broken Authentication Practical
- **Severity Level**: 2
- Hands-on practice identifying and exploiting broken authentication vulnerabilities.

### Task 8: Sensitive Data Exposure (Introduction)
- **Severity Level**: 3
- Introduced concepts related to sensitive data exposure, including inadequate encryption practices.

### Task 9 - 10: Sensitive Data Exposure (Supporting Materials)
- **Severity Level**: 3
- Reviewed supporting materials that illustrate real-world scenarios of sensitive data exposure.

### Task 11: Sensitive Data Exposure Challenge
- **Severity Level**: 3
- Engaged in a challenge focused on identifying sensitive data exposure vulnerabilities within an application.

### Task 12: XML External Entity (XXE)
- **Severity Level**: 4
- Discussed XML parsing vulnerabilities that allow attackers to exploit external entities.

### Tasks 13 - 16: XML External Entity Exploitation
Detailed exploration of XXE attacks, including:
- Understanding DTDs (Document Type Definitions)
- Crafting XXE payloads for exploitation

### Task 17 - 18: Broken Access Control
- **Severity Level**: 5
- Investigated broken access control issues, focusing on Insecure Direct Object References (IDOR).

### Task 19: Security Misconfiguration
- **Severity Level**: 6
- Examined common misconfigurations that lead to security vulnerabilities across applications.

### Task 20: Cross-Site Scripting (XSS)
- **Severity Level**: 7
- Explored XSS attacks where malicious scripts are injected into web pages viewed by other users.

### Tasks 21 - 26: Insecure Deserialization
- **Severity Level**: 8
- Covered risks associated with deserializing untrusted data, leading to potential code execution vulnerabilities.

### Tasks 27 - 29: Components with Known Vulnerabilities 
- **Severity Level**: 9
- Discussed the implications of using outdated or vulnerable components in applications and engaged in practical exploitation scenarios.

### Task 30: Insufficient Logging and Monitoring 
- **Severity Level**: 10
- Highlighted the importance of logging and monitoring for detecting and responding to security incidents effectively.

## E. Conclusion

In conclusion, the OWASP Top 10 serves as an essential framework for understanding and addressing web application security risks. The hands-on experience gained from the TryHackMe room reinforces theoretical knowledge by providing practical exposure to real-world vulnerabilities across various severity levels. By incorporating OWASP's guidelines into development practices, organizations can significantly enhance their security posture and reduce the likelihood of successful attacks on their applications. Implementing these principles not only protects sensitive data but also fosters a culture of security awareness within development teams. Continuous education and training based on frameworks like OWASP are crucial for maintaining robust application security in an ever-evolving threat landscape.
