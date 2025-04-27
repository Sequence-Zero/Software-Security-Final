# Software-Security-Final
Software Security Practices Report
ChatGPT said:
Perfect, Chris—thanks for your patience while I pulled everything together.
Using your project template​
, here’s a drafted README response you can drop into your GitHub README.md for the Software Security project:

Software Security Final Assignment: Artemis Financial
1. Briefly summarize your client, Artemis Financial, and its software requirements.
Artemis Financial is a financial services firm requiring a secure method of ensuring the security of transmitted data. The company needed an implementation of checksum verification for secure communication between systems, using a trusted cryptographic standard.

2. Who was the client? What issue did the company want you to address?
The client was Artemis Financial. They wanted to address the risk of data tampering or corruption during communication and needed a secure, verifiable mechanism to ensure the integrity and authenticity of transmitted information.

3. What did you do well when you found your client’s software security vulnerabilities?
I successfully identified potential security gaps related to data security verification and addressed them by implementing SHA-256 hashing and HTTPS communication. I performed dependency checks to ensure that new vulnerabilities were not introduced after refactoring the code base.

4. Why is it important to code securely? What value does software security add to a company’s overall well-being?
Secure coding is critical because it reduces the risk of attacks such as data breaches, man-in-the-middle attacks, and unauthorized data manipulation. Strong software security protects a company’s reputation, maintains customer trust, ensures compliance with regulatory standards, and ultimately saves the company from costly breaches and remediation.

5. Which part of the vulnerability assessment was challenging or helpful to you?
Using the OWASP Dependency-Check tool was both challenging and educational. It helped me better understand how even trusted libraries can introduce vulnerabilities if they arent properly monitored.

6. How did you increase layers of security?
I increased security layers by:

Implementing HTTPS communication

Using SHA-256 for data integrity checks

Refactoring the code to ensure adequate exception handling

Running static analysis' with OWASP Dependency-Check to identify and mitigate vulnerabilities

7. In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
In future projects, I would continue using static analysis tools like OWASP Dependency-Check, and also incorporate dynamic testing, threat modeling frameworks, and continuous integration pipelines with security scanning.

8. How did you make certain the code and software application were functional and secure?
After refactoring, I tested the application both manually (running through IDE) and through dependency checking to ensure that no vulnerabilities were introduced. Secure communication was validated by hosting the service on HTTPS (even though it was a self-signed certificate for localhost purposes).

9. After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I used OWASP Dependency-Check to scan the codebase for known vulnerabilities and suppressed one false positive after manual verification.

10. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
SHA-256 hashing algorithm

HTTPS secure configuration

Spring Boot for structured API deployment

OWASP Dependency-Check plugin

Secure coding principles such as input validation and modular code design

11. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would showcase the secure implementation of checksum verification, the usage of HTTPS communication, the use of OWASP dependency analysis for security validation, and the ability to refactor legacy code into a secure, functional endpoint following industry standards.

