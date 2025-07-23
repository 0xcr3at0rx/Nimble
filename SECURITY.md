# Security Policy

## 1. Purpose
This policy establishes guidelines to ensure the security of the Window Manager project, its codebase, and user data, protecting contributors, maintainers, and users.

## 2. Scope
This policy covers the project’s source code, dependencies, infrastructure, and all contributors and users interacting with the project.

## 3. Vulnerability Reporting
- Report vulnerabilities privately via email to `nimble.project@pm.me` using a secure channel (e.g., encrypted email).
- Include a detailed description, steps to reproduce, potential impact, and suggested mitigations.
- Maintainers will acknowledge reports within 48 hours and aim to resolve critical vulnerabilities within 14 days.
- Coordinated disclosure will occur after fixes are released, with optional credit to reporters.

## 4. Secure Development
- **Code Review**: All code submissions require peer review to identify security issues, such as input validation or unsafe API usage.
- **Dependencies**: Use trusted libraries from official sources, scan for vulnerabilities with tools like Dependabot, and apply updates promptly.
- **Coding Practices**: Sanitize inputs, use secure APIs, and implement robust error handling to prevent vulnerabilities.
- **Testing**: Perform static and dynamic analysis, as well as fuzzing, for all major releases.

## 5. Access and Distribution
- **Access**: Restrict repository and CI/CD access to authorized contributors with two-factor authentication (2FA) and store secrets in a secure vault.
- **Releases**: Sign all releases with GPG to ensure authenticity and distribute via HTTPS on trusted platforms.
- **Verification**: Provide SHA256 checksums for release integrity verification.

## 6. Incident Response
- **Detection and Containment**: Promptly identify and isolate security incidents to limit impact.
- **Recovery and Analysis**: Deploy patches quickly and conduct post-incident analysis to strengthen security practices.

## 7. User Guidelines
- Keep the window manager updated to the latest stable version to receive security patches.
- Run the software with minimal privileges, avoiding root access unless necessary.
- Report suspicious behavior or potential vulnerabilities to the security team.

## 8. Contact
For vulnerabilities or security inquiries, contact `nimble.project@pm.me` using secure communication methods.

## 9. Updates
This policy will be reviewed annually or as needed, with updates communicated through project documentation and release notes.
