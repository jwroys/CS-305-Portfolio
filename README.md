# CS 305 Software Security Portfolio

## Client Summary

The client for this project was Artemis Financial. Artemis Financial is a financial services company that needed help improving the security of its software application. The main issue was that the company needed secure communication and a way to verify data integrity. To meet this requirement, I added a SHA-256 checksum feature and configured the application to use HTTPS.

## Software Security Reflection

When finding the client’s software security vulnerabilities, I did well at following a clear process and testing the application after making changes. I reviewed the application for secure communication, checksum verification, dependency risks, and functional errors. Coding securely is important because software often handles sensitive information, especially in financial systems. Secure code helps protect client data, reduce risk, prevent unauthorized access, and maintain trust in the company.

The most helpful part of the vulnerability assessment was using tools and testing steps to confirm what needed to be fixed. The dependency-check report was useful because it showed that security is not only about the code written by the developer. It also includes the libraries and frameworks used by the application. The challenging part was understanding which vulnerabilities came from the existing project dependencies and which parts were related to the new code I added.

I increased layers of security by adding a SHA-256 checksum endpoint and enabling HTTPS communication with a certificate and keystore. The checksum helped support data integrity, while HTTPS helped protect communication between the client and server. In the future, I would use tools like OWASP dependency-check, manual code review, secure coding guidelines, and testing after refactoring to assess vulnerabilities and decide which mitigation techniques should be used.

I made certain the code and software application were functional and secure by running the application after refactoring, testing the HTTPS endpoint in the browser, checking that the SHA-256 hash displayed correctly, and running OWASP dependency-check after the changes. After refactoring the code, I checked for new vulnerabilities by reviewing the dependency-check report and confirming that the application still started and executed without errors.

Some resources, tools, and coding practices I used that may be helpful in future assignments include Java Keytool, SHA-256 hashing, Spring Boot configuration, HTTPS setup, OWASP dependency-check, Maven, and secure coding practices. These tools and practices helped me better understand how to add security features, test software, and document secure development work.

From this assignment, I would show future employers the completed Practices for Secure Software Report. This artifact shows that I can apply secure coding practices, use cryptographic hashing, configure secure communication, run vulnerability scans, and explain the importance of software security in a professional setting.
