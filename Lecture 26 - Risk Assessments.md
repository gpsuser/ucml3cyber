# Lecture 26 - Cybersecurity Risk Assessments

## Introduction

Today's lecture is on Risk Assessments in Cybersecurity. In our increasingly connected world, understanding how to identify, assess, and manage cyber risks has become crucial for organizations of all sizes.

## Learning Objectives

By the end of this lecture, you will be able to:

1. Define risk assessments in the context of cybersecurity
2. Explain why continuous risk assessment is necessary
3. Identify when risk assessments are required
4. Apply the 5-step risk assessment process
5. Complete a risk assessment template for real-world scenarios

## 1. Risk Assessments - Definition and Context

Risk assessments in cybersecurity are the systematic process of identifying, analyzing, and evaluating potential security threats to an organization's information systems and data. They involves examining both the likelihood of threats occurring and their potential impact on the organization.

Constant risk assessment is required because:

- Technology and threats evolve rapidly
- New vulnerabilities are discovered regularly
- Organization's systems and processes change over time
- Compliance requirements may update
- Business environments and dependencies shift

## 2. Motivation for Risk Assessments

Organizations conduct risk assessments to:

- Protect valuable assets and sensitive data
- Comply with regulatory requirements
- Make informed decisions about security investments
- Prioritize security measures based on risk levels
- Demonstrate due diligence to stakeholders
- Prepare for potential security incidents
- Allocate resources effectively

## 3. When Are Risk Assessments Required?

Risk assessments should be conducted (for example):

- When implementing new systems or applications
- After significant system changes or upgrades
- When new threats are identified
- Following security incidents
- During regular review cycles (quarterly/annually)
- Before cloud service adoption
- When entering new business partnerships
- During merger and acquisition processes
- When introducing new business processes
- When regulatory requirements change

## 4. The 5-Step Risk Assessment Process

### Step 1: Identify Possible Threats

Common cybersecurity threats include (for example):

- Malware infections
- Phishing attacks
- Ransomware
- Data breaches
- Insider threats
- DDoS attacks
- Social engineering
- Zero-day exploits

### Step 2: Identify Threat Likelihood

Categorize threats as:

- `Unlikely`: Rare occurrence, strong controls in place
- `Likely`: Moderate probability, some controls present
- `Very Likely`: Frequent occurrence, weak or no controls

### Step 3: Assess Vulnerabilities

Vulnerabilities can be assesed with referece to existing security controls (for example):

- Network security measures
- Access controls
- Encryption
- Security awareness training
- Incident response capabilities
- Physical security measures

Vulnerabilities could include (for example):

#### User Vulnerabilities

- Lack of security awareness
- Poor password practices
- Susceptibility to social engineering
- Unauthorized software installation
- Mobile device misuse

#### System Vulnerabilities

Which can be assessed using various tools such as:

- Vulnerability Scanners (e.g., Nessus)
- Port Scanners (e.g., Nmap)
- Registry Scanners (e.g., Microsoft Baseline Security Analyzer)
- Website Vulnerability Scanners (e.g., OWASP ZAP)
- Network Analysis Tools (e.g., Wireshark)
- Penetration Testing Tools (e.g., Metasploit)

Independent third party reviews can also be used to assess system vulnerabilities:

#### Third-Party Reviews

- Security architecture assessment
- Code review
- Configuration analysis
- Network design evaluation
- Access control assessment

#### Step 4: Assess Impact Level

Categorize impact as:

- `Minor`: Limited effect, quick recovery
- `Moderate`: Significant disruption, manageable recovery
- `Major`: Severe consequences, extended recovery

#### Step 5: Identify Risk Severity

Use the following risk matrix to determine severity:

| Likelihood/Impact | Minor | Moderate | Major |
|------------------|-------|-----------|--------|
| Very Likely      | Medium| High      | Extreme|
| Likely           | Low   | Medium    | High   |
| Unlikely         | Low   | Low       | Medium |

### 5. Motivation Behind 5-Step Process

The structured approach ensures:

- Consistent evaluation across different assessments
- Comprehensive coverage of potential risks
- Clear communication of findings
- Alignment with industry standards
- Reproducible results
- Comparative analysis capability
- Efficient resource allocation

### 6. Risk Assessment Template Motivation

Templates are essential for:

- Maintaining documentation standards
- Ensuring complete coverage of assessment areas
- Supporting audit requirements
- Facilitating knowledge transfer
- Enabling trend analysis
- Justifying security investments
- Demonstrating due diligence

### 7. Risk Assessment Template - Structure

| Label | Value |
|----------|-----------|
| Threat number | Sequential identifier (e.g., T001) |
| Threat title | Brief description |
| Probability | Unlikely/Likely/Very Likely |
| Impact | Minor/Moderate/Major |
| Risk severity | Low/Medium/High/Extreme |
| Explanation | Detailed threat description |

### 8. Risk Assessment Blank Template

| Label | Detail |
|-------|--------|
| Threat number | |
| Threat title | |
| Probability | |
| Impact level | |
| Risk Severity | |
| Explanation | |

### Worked Examples

#### Example 1: School Management System

| Label | Detail |
|-------|--------|
| Threat number | 001 |
| Threat title | Student Data Breach |
| Probability | Likely |
| Impact | Major |
| Risk severity | High |
| Explanation | Unauthorized access to student personal information and academic records through vulnerable web application, potentially leading to privacy violations and legal consequences |

#### Example 2: Library Access System

| Label | Detail |
|-------|--------|
| Threat number | 002 |
| Threat title | Malware Infection |
| Probability | Very Likely |
| Impact | Moderate |
| Risk severity | High |
| Explanation | Public computers in the library infected with malware through USB devices or downloads, potentially compromising user data and system integrity |

#### Example 3: School Network Infrastructure

| Label | Detail |
|-------|--------|
| Threat number | 003 |
| Threat title | DDoS Attack |
| Probability | Unlikely |
| Impact | Major |
| Risk severity | Medium |
| Explanation | Distributed Denial of Service attack targeting school network during exam period, potentially disrupting online assessments and administrative functions |

### Conclusion

Risk assessment is a critical component of cybersecurity management. The structured approach we've discussed helps organizations identify, evaluate, and prioritize security risks systematically. Remember that risk assessment is not a one-time activity but an ongoing process that requires regular review and updates to remain effective.

### References

1. NIST Special Publication 800-30: Guide for Conducting Risk Assessments
2. ISO/IEC 27005:2018 Information technology — Security techniques
3. OWASP Risk Assessment Framework
4. CIS Controls v8
5. SANS Institute: Security Risk Assessment Guidelines

---
