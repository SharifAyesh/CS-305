# CS-305

# CS 305 Project Two – Secure Software Practices: Artemis Financial Report

The client for this project was Artemis Financial, a financial services company with a public-facing web application. The organization sought a secure solution that could identify vulnerabilities, improve software integrity, and ensure that client data is protected during transmission. My role involved assessing the codebase for risks, implementing secure coding practices, and delivering a solution that adheres to industry standards for secure software.

One of the key successes was accurately identifying and mitigating software security vulnerabilities using SHA-256 hashing and SSL configuration. By integrating checksum validation into the application, I was able to verify the integrity of data being processed or transferred. Additionally, I configured HTTPS using Spring Boot to secure communication between the client and server. This not only aligned with secure development standards but also ensured encryption of sensitive financial information.

The most challenging part of the vulnerability assessment was configuring the OWASP Dependency-Check and suppressing known false positives while maintaining a focus on actual threats. It required manual inspection of flagged issues and careful documentation to justify suppression. This process was educational and strengthened my ability to differentiate between exploitable and benign vulnerabilities.

To enhance security, I implemented the following measures:
- **SHA-256** hashing for data verification and tamper detection.
- **HTTPS (SSL/TLS)** for encrypted communication.
- **OWASP Dependency-Check** for scanning Java dependencies.
- **Suppression files** for managing known, safe CVEs.
In the future, I would also incorporate automated static code analysis and dynamic vulnerability scanning to increase coverage and efficiency.

After completing the refactoring, I conducted functional testing to ensure the application ran without errors. I also ran dependency-check reports to confirm that no new vulnerabilities were introduced. Screenshots of these tests are included in the report. The checksum mechanism was tested in the browser using a REST endpoint, confirming both output accuracy and secure HTTPS delivery.

Resources and Tools Used
- Spring Boot (Java)
- SHA-256 cryptographic hash function
- OWASP Dependency-Check Maven Plugin
- Visual Studio Code & Eclipse
- SSL certificate generation and configuration
- RESTful Web Services using @RestController

These tools reinforced secure development workflows and are transferable to future roles in software engineering or cybersecurity.

This project demonstrates practical experience in secure software development, vulnerability assessment, and REST API implementation. It showcases my ability to follow security best practices, manage dependencies securely, and document mitigation strategies clearly. For future employers, this artifact is proof of my readiness to contribute to secure software projects and to work on teams focused on code quality and data protection.



