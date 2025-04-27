# Secure-Software-Report
A Spring Boot application demonstrating secure software coding practices, including SHA-256 checksum generation for data integrity, HTTPS implementation using Java keystore (SSL/TLS), and vulnerability management through OWASP Dependency-Check integration. Designed to illustrate industry-standard security best practices in software development.

Client and Software Requirements
The client for this project is Artemis Financial, a financial consulting firm providing personalized financial planning, including investments, savings, retirement, and insurance solutions. Artemis Financial requested secure communication features integrated into their existing software application to protect sensitive client data. Specifically, the company needed secure checksum verification using SHA-256 hashing and secure communication via HTTPS to ensure data integrity and confidentiality.

Identification of Software Security Vulnerabilities
I effectively identified vulnerabilities by thoroughly reviewing Artemis Financial’s software, particularly highlighting weaknesses in data integrity verification and the absence of secure data transmission protocols. This careful analysis was essential because secure coding prevents data breaches, maintains client trust, and protects the organization from potential legal and financial liabilities. Ensuring secure software adds substantial value to a company’s reputation, customer trust, and operational stability.

Vulnerability Assessment Reflection
The most helpful part of the vulnerability assessment was using the OWASP Dependency-Check tool, which provided automated scanning for known vulnerabilities within third-party libraries and dependencies. However, the challenging aspect was initially correctly configuring and integrating SSL certificates and managing secure keys within Java Keystores.

Security Enhancement Process and Future Improvements
I increased security by implementing multiple layers, including SHA-256 hashing for checksum verification, SSL/TLS encryption to secure data in transit, and ongoing vulnerability monitoring via OWASP Dependency-Check. For future projects, I will continue using automated vulnerability assessment tools like OWASP Dependency-Check and SonarQube, and refer to OWASP Top Ten guidelines to prioritize risks and select appropriate mitigation strategies.

Ensuring Functionality and Security
To ensure the application’s functionality and security, I combined automated dependency checks with manual code reviews. After refactoring, I verified the application’s functionality by compiling and executing the code successfully without errors. To ensure no new vulnerabilities were introduced, I performed additional OWASP dependency checks and carefully reviewed generated vulnerability reports.

Helpful Resources and Tools
Throughout this project, resources such as the OWASP Dependency-Check tool, Java Keytool for SSL certificate management, Spring Boot documentation, and Maven were particularly useful. Adopting secure coding practices aligned with industry standards and clear project structure recommendations from OWASP proved beneficial and will continue to aid future assignments and projects.
