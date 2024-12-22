# Web Security Lab

## Objective
The Web Security Lab provides an immersive environment to learn and apply web application security techniques. This repository focuses on identifying, exploiting, and mitigating common web vulnerabilities using industry-standard tools and methodologies.

### Skills Learned
- Proficiency in web vulnerability assessment and exploitation.
- In-depth understanding of OWASP Top 10 vulnerabilities (e.g., SQL Injection, XSS, CSRF, etc.).
- Hands-on experience with Burp Suite for traffic interception, testing, and scanning.
- Effective use of automated tools like SQLMap for vulnerability exploitation.
- Developing secure coding practices and server hardening techniques.
- Critical thinking in securing and defending web applications.

### Tools Used
- Burp Suite: Full suite of tools for web application security testing.
- OWASP ZAP: For vulnerability scanning and interception.
- SQLMap: For automated SQL Injection exploitation.
- Kali Linux: Environment for testing and ethical hacking.
- Wireshark: For traffic analysis.
- Custom scripts for payload delivery and testing.

## Tasks
Below are the key tasks and concepts covered:

### 1. Vulnerability Scanning and Reconnaissance
- Conducted web vulnerability scanning using OWASP ZAP and Burp Suite.
- Mapped application endpoints, parameters, and user input points.
- Intercepted and analyzed web traffic to identify security flaws.
- Crafted manual HTTP requests to test application behavior under edge cases.

### 2. SQL Injection (SQLi)
![image](https://github.com/user-attachments/assets/0a772f62-86d2-4b80-8a3d-2ea778f565e5)
![image](https://github.com/user-attachments/assets/30f626de-f3be-4aad-b892-1482d6a0667b)
- Exploited SQL Injection vulnerabilities to extract sensitive database information.
- Automated SQLi exploitation using SQLMap to enumerate databases, tables, and entries.
- Tested Boolean-based and Union-based SQL Injection methods.
- Demonstrated blind SQLi techniques for exploitation without visible output.

### 3. Cross-Site Scripting (XSS)
![image](https://github.com/user-attachments/assets/d07d1311-1933-40ba-926c-3abf0cc57b35)

- Exploited reflected and stored XSS vulnerabilities in web applications.
- Injected malicious JavaScript payloads to demonstrate session hijacking and cookie theft.
- Created custom payloads to evade common XSS filters.
- Implemented mitigation strategies, including output encoding and content security policies.

### 4. Cross-Site Request Forgery (CSRF)
- Demonstrated the impact of CSRF attacks by forging malicious requests on behalf of authenticated users.
- Crafted proof-of-concept CSRF payloads targeting sensitive actions like password resets and fund transfers.
- Implemented anti-CSRF tokens to defend against these attacks.

### 5. Using Burp Suite Features
- **Proxy**: Intercepted and modified web traffic to analyze vulnerabilities.
- **Scanner**: Performed automated scans for common vulnerabilities in applications.
- **Intruder**: Conducted brute force and parameter fuzzing attacks.
- **Repeater**: Resent and modified requests for manual testing.
- **Comparer**: Analyzed differences in responses for vulnerability identification.
- **Decoder**: Encoded/decoded data to test input validation and bypass.

### 6. Exploiting Broken Authentication
- Analyzed login mechanisms to test for vulnerabilities like credential stuffing and session fixation.
- Bypassed weak authentication mechanisms to gain unauthorized access.
- Implemented secure practices like MFA, session expiration, and cookie flags.

### 7. SQLMap and Advanced SQLi
- Leveraged SQLMap for in-depth automated SQL Injection exploitation.
- Bypassed WAFs (Web Application Firewalls) using advanced evasion techniques.
- Explored database schema and extracted sensitive information such as passwords and PII.

### 8. Command Injection and RCE
- Exploited vulnerable endpoints to execute system commands.
- Demonstrated the impact of remote code execution (RCE) attacks.
- Created payloads to establish reverse shells and escalate privileges.
- Implemented defense mechanisms, including input validation and sanitization.

### 9. Securing Web Servers
- Hardened web servers by disabling unnecessary services and ports.
- Implemented HTTP security headers (e.g., HSTS, CSP, X-Content-Type-Options).
- Tested SSL/TLS configurations for weaknesses using tools like SSL Labs.
- Configured file permissions and ensured secure handling of sensitive data.

### 10. Session Management Testing
- Tested for session fixation and session hijacking vulnerabilities.
- Simulated attacks to steal and reuse session cookies.
- Implemented secure practices such as session timeout, regeneration, and encryption.

### 11. Directory and File Enumeration
- Performed directory enumeration to identify hidden files and misconfigured directories.
- Exploited access to sensitive files like `.git`, `.env`, and backup files.
- Recommended secure deployment practices to avoid unintentional exposure.

### 12. OWASP Challenges
- Solved multiple challenges from OWASP Juice Shop and similar vulnerable applications.
- Identified and exploited security misconfigurations in test environments.
- Documented lessons learned and created reports on vulnerabilities and mitigations.

---


