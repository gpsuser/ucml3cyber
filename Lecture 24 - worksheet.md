# Lecture 24 - Vulnerability Assessment Worksheets

## Worksheet 1

### Questions

1. **Basic Understanding Question:**
   What is the difference between internal and external vulnerability assessment? Give one example of each type.

2. **Tool Recognition Question:**
   Name three common tools used for identifying vulnerabilities and explain what each one does.

3. **Practical Application Question:**
   Your school wants to test if their website is secure. What type of vulnerability scanner would you recommend they use, and why?

4. **Security Awareness Question:**
   What is phishing, and why is it important to test employees' awareness of phishing attacks? Describe one way this could be done.

5. **Penetration Testing Question:**
   Explain what penetration testing is in your own words, and list two main things it helps organizations discover about their security.

6. **OWASP Question:**
   From the OWASP Top 10, explain what "Broken Access Control" means and give a real-world example of this vulnerability.

7. **Third-Party Review Question:**
   Why might an organization want to have an external company review their security instead of just doing it themselves? Give two reasons.

### Solutions

1. **Internal vs External Assessment Solution:**
   Internal and external assessments provide different perspectives and uncover different types of vulnerabilities:

   Internal Assessments can uncover:
   - Misconfigured access controls between internal systems
   - Inappropriate user privileges
   - Non-compliant internal practices
   
   External Assessments can uncover:
   - Previously unknown entry points
   - Zero-day vulnerabilities
   - Social engineering vulnerabilities
   
   Together, they provide comprehensive coverage that neither could achieve alone.

2. **Nmap Output Analysis Solution:**
   Key concerns include:
   - OpenSSH 7.4 might be outdated and contain known vulnerabilities
   - HTTP port 80 indicates unencrypted web traffic
   - Filtered HTTPS port could indicate misconfigured SSL/TLS
   
   Recommended additional scans:
   - Version-specific vulnerability scan for OpenSSH
   - SSL/TLS configuration test
   - Web application security scan on port 80

3. **Security Awareness Solution:**
   Recommended steps:
   - Implement role-specific training focusing on real-world scenarios
   - Conduct more frequent but less predictable phishing simulations
   - Develop a metrics-based reporting system
   
   Measure effectiveness through:
   - Tracking click rates over time
   - Measuring reporting rates of actual phishing attempts
   - Conducting follow-up assessments with increasing complexity

4. **Penetration Testing Comparison Solution:**
   White Box Testing:
   - Appropriate for: thorough code review, application security testing
   - Examples: new application deployment, compliance requirements
   - Benefits: comprehensive coverage, efficient testing
   
   Black Box Testing:
   - Appropriate for: real-world attack simulation, external threat assessment
   - Examples: testing incident response, evaluating security controls
   - Benefits: realistic attack scenarios, unbiased assessment

5. **Scanner Evaluation Solution:**
   For an e-commerce platform:
   Web Application Scanner would be most appropriate because:
   - Focuses on application-layer vulnerabilities
   - Can identify common e-commerce issues (SQL injection, XSS)
   - Tests shopping cart functionality and payment processes
   - Can assess session management and authentication

6. **OWASP Mobile Banking Solution:**
   Critical vulnerabilities:
   1. Cryptographic Failures
      - Why: Protects sensitive financial data
      - Mitigation: Implement strong encryption, secure key management
   
   2. Authentication Failures
      - Why: Prevents unauthorized account access
      - Mitigation: Multi-factor authentication, biometric validation

7. **Integration Solution:**
   Third-party review and automated scanning complement each other:
   - Automated scanning provides regular, consistent checks
   - Third-party review offers:
     - Strategic security assessment
     - Complex vulnerability analysis
     - Compliance verification
   Example findings:
   - Automated: Open ports, missing patches
   - Third-party: Architecture flaws, process weaknesses

## Worksheet 2: 

### Questions

1. A ________ scan helps identify open ports and services running on network systems.

2. The OWASP Top 10 lists ________ as the most critical web application security risk in 2021.

3. In penetration testing, the ________ phase involves gathering information and mapping the network.

4. A ________ provides independent validation of system design and infrastructure security.

5. ________ testing involves having complete knowledge of the target system, including source code and architecture documentation.

6. The process of identifying security weaknesses using an organization's own resources is called ________ vulnerability assessment.

7. ________ programs reward external researchers for finding and reporting security vulnerabilities.

8. A ________ scanner is specifically designed to identify security issues in web applications.

9. The ________ phase of penetration testing involves documenting findings and providing remediation recommendations.

10. ________ failures in the OWASP Top 10 can lead to exposure of sensitive data due to weak encryption.

### Scrambled Answers

- Bug bounty
- Port
- Broken access control
- Reconnaissance
- White box
- Internal
- Architecture review
- Website vulnerability
- Reporting
- Cryptographic



The worksheets provide a mix of question types to test different levels of understanding:

- Critical thinking and analysis
- Technical comprehension
- Practical application
- Integration of concepts
- Recall and recognition

Worksheet 2 focus on key terminology and concepts from the lecture, while Worksheet 1 encourage deeper analysis and application of the material.
