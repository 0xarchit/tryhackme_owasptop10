# OWASP Top 10 Report

## A. Objective

The objective of this report is to provide a comprehensive overview of the OWASP Top 10 vulnerabilities as I explored in the TryHackMe room. This report contain all task and proof that I have completed the room of Owasp Top 10.

## B. What is OWASP Top 10

The **OWASP Top 10** is a widely recognized report published by the Open Web Application Security Project (OWASP). It outlines the ten most critical security risks to web applications, serving as a foundational resource for developers and security professionals. The list is updated periodically based on data collected from various organizations and reflects current trends in web application security threats. The OWASP Top 10 aims to raise awareness about these vulnerabilities, promote secure coding practices, and guide organizations in prioritizing their security efforts.

## C. Need for OWASP Top 10

The need for the OWASP Top 10 arises from the increasing complexity of web applications and the evolving landscape of cyber threats. Key reasons for its importance include:

- **Prioritization of Security Efforts**: Organizations can focus on addressing the most critical vulnerabilities that could lead to significant breaches.
- **Education and Awareness**: It provides essential training resources for developers about secure coding practices and common pitfalls.
- **Improved Security Posture**: By implementing measures to mitigate these vulnerabilities, organizations can enhance their overall application security.

## D. Practical

### Chapter 0: Starting

> Task 1: Introduction
- **Task Detail**: This task provides an overview of the TryHackMe OWASP Top 10 room.

  ![image](https://github.com/user-attachments/assets/082dc488-5a34-4719-84ad-6319d2e24cd6)



> Task 2: Accessing Machines
- **Task Detail**: Instructions on how to access the machines relevant to the tasks in this TryHackMe room and also the process of setting up OpenVPN to access attack machine through our local machine.

  ![image](https://github.com/user-attachments/assets/30745050-dc75-484d-95f2-959826d7d06a)



### Chapter 1: Injection

> Task 3: Injection
- **Task Detail**: This task introduces injection attacks, including SQL injection and their potential impact on applications. Here I learn how attackers can manipulate input fields to execute arbitrary commands.

> Task 4: OS Command Injection
- **Task Detail**: This task focuses on OS command injection vulnerabilities, explaining how they allow attackers to execute commands on a host operating system through a vulnerable application.

> Task 5: Command Injection Practical
- **Task Detail**: A hands-on exercise where I exploit a command injection vulnerability in tryhackme given environment.

  ![image](https://github.com/user-attachments/assets/d4913bc3-ece2-4c75-8827-4df9161e48d9)


### Chapter 2: Broken Authentication

> Task 6: Broken Authentication
- **Task Detail**: This task discusses common issues related to authentication mechanisms, such as weak passwords and session management flaws that can lead to unauthorized access.

> Task 7: Broken Authentication Practical
- **Task Detail**: A practical demonstration of exploiting broken authentication vulnerabilities, allowing to see how these weaknesses can be leveraged by attackers.

  ![image](https://github.com/user-attachments/assets/a2c6180d-e4e3-4f7a-bd03-71ab534f8de3)


### Chapter 3: Sensitive Data Exposure

> Task 8: Sensitive Data Exposure (Introduction)
- **Task Detail**: An introduction to sensitive data exposure risks, highlighting how inadequate protection measures can lead to unauthorized access to sensitive information.

> Task 9: Sensitive Data Exposure (Supporting Material 1)
- **Task Detail**: Additional resources discussing best practices for protecting sensitive data, including encryption and secure storage methods like nosql and also learnt how to extract hashes.

> Task 10: Sensitive Data Exposure (Supporting Material 2)
- **Task Detail**: Further insights into securing sensitive data against exposure through various attack vectors and learnt to crack hashes to get passwords.

> Task 11: Sensitive Data Exposure (Challenge)
- **Task Detail**: A challenge task focused on identifying sensitive data exposure vulnerabilities within a simulated environment.

  ![image](https://github.com/user-attachments/assets/b1e9c4c3-1844-4a0b-a1c6-6f4f614c2f36)


### Chapter 4: XML External Entity (XXE)

> Task 12: XML External Entity
- **Task Detail**: Overview of XXE vulnerabilities, explaining how they occur when XML parsers process external entities within XML documents.

> Task 13: XML External Entity - eXtensible Markup Language
- **Task Detail**: Detailed explanation of XML and its structure, along with security concerns associated with its use in applications.

  ![image](https://github.com/user-attachments/assets/fca59560-bca2-49be-b7c0-e08ad690aacd)


> Task 14: XML External Entity - DTD
- **Task Detail**: Understanding Document Type Definitions (DTD) in relation to XXE vulnerabilities and how they can be exploited.

  ![image](https://github.com/user-attachments/assets/b7b55a3f-71d3-423a-8f84-d0c7ccfafc3f)


> Task 15: XML External Entity - XXE Payload
- **Task Detail**: Crafting payloads specifically designed for exploiting XXE vulnerabilities in XML documents.

> Task 16: XML External Entity - Exploiting
- **Task Detail**: Practical demonstration of exploiting XXE vulnerabilities, practicing on real-world implications of these security flaws via tryhackme machine.

  ![image](https://github.com/user-attachments/assets/93237305-5417-4126-9821-8a06ac94acc0)


### Chapter 5: Broken Access Control

> Task 17: Broken Access Control
- **Task Detail**: Discussion on issues related to access control mechanisms that can lead to unauthorized actions by users within an application.

> Task 18: Broken Access Control (IDOR Challenge)
- **Task Detail**: Challenge focused on Insecure Direct Object References (IDOR), where I identify and exploit weaknesses on a tryhackme sandbox.

  ![image](https://github.com/user-attachments/assets/cb1ec7e8-96c0-47d8-9198-8d4cb62b0014)


### Chapter 6: Security Misconfiguration

> Task 19: Security Misconfiguration
- **Task Detail**: Exploring common misconfigurations that lead to vulnerabilities, such as default settings or overly permissive permissions that expose applications to risk.

  ![image](https://github.com/user-attachments/assets/6de4945b-a6f0-4a37-bf20-56ce7ad1f804)


### Chapter 7: Cross-site Scripting (XSS)

> Task 20: Cross-site Scripting
- **Task Detail**: Understanding XSS attacks, including stored, reflected and dom based XSS, along with a practical machine to try these attacks.

  ![image](https://github.com/user-attachments/assets/aacd0b10-d2db-4397-80b9-b4b008174121)


### Chapter 8: Insecure Deserialization

> Task 21: Insecure Deserialization 
- **Task Detail**: Overview of deserialization vulnerabilities and risks associated with improperly handling serialized data.

  ![image](https://github.com/user-attachments/assets/1e4c2360-9799-41b2-abfa-c4fd96cdc8cb)


> Task 22: Insecure Deserialization - Objects
- **Task Detail**: Discussion on object serialization (concept of oops) and its learning about state and behaviour.

  ![image](https://github.com/user-attachments/assets/ee2c26c2-cdb9-4441-a242-ca6d8ff3f3af)


> Task 23: Insecure Deserialization - Deserialization 
- **Task Detail**: Detailed examination of deserialization processes, highlighting potential attack vectors that could be exploited by malicious actors.

  ![image](https://github.com/user-attachments/assets/24e35b9c-2bbc-40e2-8042-068f181de15b)


> Task 24: Insecure Deserialization - Cookies 
- **Task Detail**: Understanding cookie serialization issues and how insecure deserialization can lead to session hijacking or other attacks.

  ![image](https://github.com/user-attachments/assets/ad3c3e19-9273-4033-aa8d-a6a5498bee34)


> Task 25: Insecure Deserialization - Cookies Practical 
- **Task Detail**: Practical task involving cookie deserialization attacks, allowing to apply understandings in a tryhackme environment by changing values of cookies.

  ![image](https://github.com/user-attachments/assets/a3f1a37f-8208-40a6-82e1-724e10918df1)


> Task 26: Insecure Deserialization - Code Execution 
- **Task Detail**: Another practical task on how insecure deserialization can lead to remote code execution vulnerabilities within an application.

  ![image](https://github.com/user-attachments/assets/ef9f117e-d47a-4146-8fd1-616c4c50f17e)


### Chapter 9: Components With Known Vulnerabilities

> Task 27: Components With Known Vulnerabilities - Intro 
- **Task Detail**: Introduction to risks associated with using outdated components or libraries that contain known vulnerabilities.

> Task 28: Components With Known Vulnerabilities - Exploit 
- **Task Detail**: Practical demonstration of exploiting known vulnerabilities in software components, emphasizing the importance of keeping libraries up-to-date.

> Task 29: Components With Known Vulnerabilities - Lab 
- **Task Detail**: Lab exercise focusing on identifying vulnerable components within controlled environment.

  ![image](https://github.com/user-attachments/assets/56509d10-143b-4921-bee8-71a7ef77b100)


### Chapter 10: Insufficient Logging and Monitoring

> Task 30: Insufficient Logging and Monitoring 
- **Task Detail**: Discussing the importance of logging and monitoring in application security. This task highlights how insufficient logging can hinder incident response efforts and allow attacks to go unnoticed.

  ![image](https://github.com/user-attachments/assets/6a97ce5f-f061-4dfe-983a-aede88ea6328)


## E. Conclusion

The OWASP Top Ten serves as a crucial resource for understanding web application security risks. By engaging with practical tasks in TryHackMe, I gain a hands-on experience with these vulnerabilities, enhancing their ability to secure applications effectively. Continuous education and awareness are vital for developers and organizations alike to mitigate these risks, ensuring a robust defense against potential attacks.
As a beginner and doing it first time I took help from some youtube channel and this [article](https://musyokaian.medium.com/owasp-top-10-tryhackme-b7d02f29254b).

### My room completion badge:
  ![image](https://github.com/user-attachments/assets/452b465b-2b3d-4fd2-848f-8fc8f1e049db)
