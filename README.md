# security_testing
## Security_Testing_Task
## CODTECH Internship – Task 3
## Security Testing for Web Applications

**Company:** CODTECH IT SOLUTIONS
**Intern Name:** Kandimalla Karthik
**Intern ID:** CTIS2128
**Domain:** Software Testing
**Duration:** 4 Weeks
**Mentor:** Neela Santosh

## Task Description

As part of my internship at CODTECH IT SOLUTIONS, I was assigned Task 3 in the domain of Software Testing, which focuses on Security Testing for Web Applications. The objective of this task was to manually test a sample web application to identify common security vulnerabilities such as SQL Injection and Cross-Site Scripting (XSS), and to document the findings along with appropriate mitigation strategies.

The goal of this task was not to exploit systems maliciously, but to understand how insecure input handling can lead to serious security risks and how such issues can be prevented in real-world applications.

## How I Prepared

Before starting the security testing process, I first understood the basic concepts of web application security, including how user input is processed by the backend and how improper validation can lead to vulnerabilities. I selected a publicly available and legal demo web application designed specifically for educational security testing.

I ensured that all testing was conducted manually using a web browser, without using automated penetration testing tools. This approach helped me clearly understand how each vulnerability occurs and how attackers might attempt to exploit weak input validation mechanisms.

## What I Have Done

## Selected a Sample Web Application:

Used a demo banking web application created for security testing purposes.

Verified that the application contained login and input fields suitable for testing SQL Injection and XSS vulnerabilities.

## Performed SQL Injection Testing:

Tested the login functionality by entering SQL Injection payloads in the username and password fields.

Observed that authentication could be bypassed without valid credentials.

Confirmed the presence of an SQL Injection vulnerability due to improper input validation.

## Performed Cross-Site Scripting (XSS) Testing:

Injected JavaScript payloads into input fields such as search or text boxes.

Verified whether the script executed in the browser.

Confirmed the presence of an XSS vulnerability when user input was reflected without proper sanitization.

## Captured Evidence:

Took screenshots of successful SQL Injection login bypass.

Captured screenshots showing execution of injected XSS scripts.

Saved all screenshots in the project folder for reference and submission.

## Documented Security Findings:

Created a detailed Security Report describing the vulnerabilities identified.

Explained the impact of each vulnerability on application security.

Included recommended mitigation strategies to prevent such vulnerabilities in real-world systems.

## Key Vulnerabilities Identified

## SQL Injection:
Allows attackers to bypass authentication and manipulate backend databases by injecting malicious SQL queries.

## Cross-Site Scripting (XSS):
Allows attackers to execute malicious scripts in users’ browsers, potentially leading to session hijacking or data theft.

## Conclusion

Through this task, I gained hands-on experience in identifying common web application security vulnerabilities using manual testing techniques. This exercise helped me understand the importance of secure coding practices such as input validation, output encoding, and the use of secure authentication mechanisms. The task successfully met the objectives defined by CODTECH for Security Testing in web applications.


## output

## sql_injection1
<img width="1909" height="1002" alt="Image" src="https://github.com/user-attachments/assets/799d1c0c-66c8-4121-ba33-7f67d5e50383" />

## sql_injection2(i got access without proper creditnals)


<img width="1909" height="1004" alt="Image" src="https://github.com/user-attachments/assets/cd8eb830-dcd4-464d-a2c2-53e00599ab57" />

## sql_injection3

<img width="1877" height="1001" alt="Image" src="https://github.com/user-attachments/assets/dc4067ce-3c57-491e-bf66-af838e47523f" />
## xss_test 

<img width="1367" height="535" alt="Image" src="https://github.com/user-attachments/assets/f0854170-90e2-475b-b927-eb58039aaf3d" />
## xss_test1
<img width="1385" height="973" alt="Image" src="https://github.com/user-attachments/assets/76d5d73e-76b9-4fff-8264-934a81423812" />
