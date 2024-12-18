# Lecture 25 - Assessing Risk in Cybersecurity

## Introduction

The topic of this session is Assessing Risk in Cybersecurity. We'll explore how to identify, measure, and evaluate potential threats to information systems. 

In our increasingly connected world, understanding how to assess and manage cybersecurity risks is becoming as fundamental as knowing how to use technology itself. 

By the end of this lecture, you'll understand how to assess risks using industry-standard methods and make informed decisions about risk management.

### Learning Objectives

By the end of this session, you will be able to:

- Define and identify cybersecurity risks
- Measure risks using standardized scales
- Evaluate both probability and impact components of risks
- Use the Risk Severity Matrix to assess threats
- Make informed decisions about risk prevention based on severity levels

### 1. Understanding Risk in Cybersecurity

Risk in cybersecurity refers to the potential for loss, damage, or compromise of assets or data through a cyber attack or breach. Think of it as the "what could go wrong?" factor in our digital world. Just as we assess risks in everyday life before crossing a street or trying a new activity, we must evaluate risks in our digital interactions.

**Example:**
Consider a school's student database:
- The database contains personal information (names, addresses, grades)
- Multiple users (teachers, administrators) need access to it
- It's connected to the internet for remote access
- Each of these factors introduces potential risks

### 2. Measuring Risk

Risk measurement involves evaluating potential threats on a standardized scale to make informed decisions about protection measures. This standardization helps organizations communicate about risks effectively and allocate resources appropriately.

**Standard Risk Scale:**
- Low: Minimal threat to operations
- Medium: Notable threat requiring attention
- Extreme: Critical threat demanding immediate action

**Example Application:**
Let's measure the risk of using an outdated operating system:
- Security patches unavailable = Extreme risk
- Latest patches missing by 1-2 months = Medium risk
- System fully updated = Low risk

### 3. Risk Assessment Framework

Risk assessment combines two key factors:
1. Probability of occurrence
2. Potential impact

This can be expressed as:
```
Risk Severity = Probability × Impact
```

Think of this like weather forecasting - we consider both how likely it is to rain (probability) and how severe the rain might be (impact) to decide whether to carry an umbrella.

### 4. Measuring Probability Components

#### 4.1 Key Factors in Probability Assessment

When assessing probability, consider:

| Factor | Assessment Questions | Example |
|--------|---------------------|----------|
| Ease of Execution | How technically challenging is the attack? | Simple phishing email vs. Complex network breach |
| Potential Reward | What could attackers gain? | Financial data, personal information |
| Detection Risk | How likely are attackers to be caught? | Traceable vs. Anonymous attacks |
| Vulnerability Awareness | How well-known is the weakness? | Published exploit vs. Zero-day vulnerability |

#### 4.2 Probability Scale

| Level | Description | Example Scenario |
|-------|-------------|------------------|
| Unlikely | Not expected but possible | Zero-day exploit targeting specific system |
| Likely | Expected occasionally | Phishing attempts |
| Very Likely | Will occur frequently | Password attacks |

### 5. Measuring Impact Components

#### 5.1 Impact Assessment Factors

| Factor | Assessment Questions | Example |
|--------|---------------------|----------|
| Data Loss | What volume of data is at risk? | All student records vs. Single file |
| Recovery Time | How long to restore operations? | Hours vs. Days vs. Weeks |
| Data Sensitivity | Is confidential information at risk? | Public website vs. Financial records |
| Financial Impact | What are the monetary consequences? | Hardware replacement vs. Legal penalties |
| Reputation Damage | How will stakeholders be affected? | Minor inconvenience vs. Major breach |

#### 5.2 Impact Scale

| Level | Description | Example Consequences |
|-------|-------------|---------------------|
| Minor | Minimal disruption | Temporary website outage |
| Moderate | Notable disruption | 1-day system downtime |
| Major | Significant harm | Complete data breach |

### 6. Risk Severity Matrix

The Risk Severity Matrix combines probability and impact assessments to determine the overall severity level of a risk:

| Probability / Impact | Minor | Moderate | Major |
|---------------------|-------|----------|-------|
| Very Likely         | Medium| High     | Extreme|
| Likely              | Low   | Medium   | High   |
| Unlikely            | Low   | Low      | Medium |

Using this matrix:
1. Identify the probability level (row)
2. Identify the impact level (column)
3. Find the intersection point to determine severity

**Example Application:**
A weak password policy:
- Probability: Very Likely (easily exploitable)
- Impact: Major (could lead to unauthorized access)
- Severity Rating: Extreme (from matrix intersection)

### 7. Risk Prevention Based on Severity

Risk prevention measures should be proportional to risk severity:

| Severity Level | Recommended Response | Resource Allocation |
|----------------|---------------------|-------------------|
| Low | Basic protection | Minimal cost measures |
| Medium | Enhanced protection | Moderate investment |
| High | Strong protection | Significant investment |
| Extreme | Maximum protection | Major investment |

### Practical Exercise

Let's assess the risk of a school's wireless network:

1. Identify the threat: Unauthorized access to network
2. Assess probability:
   - Easy to attempt (Very Likely)
   - Valuable target (Student/Staff data)
   - Well-known vulnerabilities
3. Assess impact:
   - Potential data theft (Major)
   - Network downtime
   - Reputation damage
4. Use the matrix:
   - Very Likely probability
   - Major impact
   - Result: Extreme risk level

### Conclusion

Understanding risk assessment is crucial in cybersecurity. Remember:
- Always consider both probability and impact
- Use standardized measurements for consistent evaluation
- Apply appropriate prevention measures based on risk severity
- Regularly reassess as threats evolve

### Additional Resources

#### Primary References
1. National Institute of Standards and Technology (NIST). (2023). *Risk Management Framework for Information Systems and Organizations* (SP 800-37r2). U.S. Department of Commerce.

2. International Organization for Standardization. (2022). *ISO/IEC 27005:2022 - Information Security Risk Management*. ISO.

3. ISACA. (2023). *COBIT 2019 Framework: Risk Optimization*. ISACA.

#### Supplementary Materials
4. Center for Internet Security (CIS). (2023). *CIS Controls v8*. 

5. European Union Agency for Cybersecurity (ENISA). (2023). *Risk Management Standards*.

6. Australian Cyber Security Centre. (2023). *Information Security Manual (ISM)*.

#### Educational Resources
7. CompTIA. (2023). *Security+ Certification Materials - Risk Management*.

8. SANS Institute. (2023). *SEC401: Security Essentials - Risk Assessment Module*.

#### Online Tools and Frameworks
- NIST Cybersecurity Framework Online Informative References
- MITRE ATT&CK Framework
- School IT Security Policy Templates
- Open Source Security Testing Methodology Manual (OSSTMM)

### Teaching Notes

This lecture content has been developed by synthesizing current best practices and educational standards from:
- NICE Cybersecurity Workforce Framework
- ACM/IEEE Cybersecurity Curricula 2023
- National Initiative for Cybersecurity Education (NICE)

Methodology for Risk Assessment is aligned with:
- NIST SP 800-30 Rev. 1
- ISO 31000:2018
- FAIR (Factor Analysis of Information Risk) methodology

### Next Steps
- Practice using the Risk Severity Matrix with real-world scenarios
- Apply these concepts to your personal digital security
- Consider how these principles apply to recent cyber incidents
- Explore the additional resources provided for deeper understanding

---
*Note to students: This framework provides a structured approach to risk assessment, but remember that cybersecurity is dynamic, and new threats emerge regularly. Stay informed about current trends and emerging threats.*
