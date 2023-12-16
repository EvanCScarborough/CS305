# CS305
A portfolio artifact from my CS-305 class.

For this assignment, I took on the role of a software security analyst at a firm called Global Rain. Our client, a fictional bank called Artemis Financial, presented us with the codebase for their RESTful web application and tasked us with discovering potential security vulnerabilities. I compiled a report with my findings.

For companies like Artemis Financial, security is paramount. Failure to comply with relevant government regulations can lead to severe penalties, including the revocation of the company's right to do business in the United States, or it can allow hackers to access sensitive consumer or business data. Any such breach can also result in loss of customer trust, which is critical for a finance company to maintain. Coding securely is an important means of safeguarding the company from these threats.

For this particular assignment, I was challenged to perform static testing on an unfamiliar code base. To start, I found it helpful to familiarize myself with the application by running it locally and observing its behavior. Once I had a feel for it, I started analyzing the source code and running my static tests. I discovered a number of vulnerabilities in the libraries utilized by the application, as well as some significant oversights in the architecture of the application itself, including a lack of user authentication. I refactored the source code and executed another round of static tests to ensure that no new vulnerabilities had arisen as a result of my changes. This was all documented in my report.

This assignment serves as an example of my ability to:
- Identify security vulnerabilities within an application
- Utilize the dependency check plugin to generate security reports
- Write and refactor code utilizing best practices for security
- Document my findings and changes
