# Lecture 25 - Assessing Risk

## Lecture Overview

### Introduction

Today's lecture considers `Assessing Risk in Cybersecurity`. 

In our interconnected digital world, understanding how to identify, measure, and manage risks is crucial for protecting our information systems. 

This session will equip you with the fundamental concepts and practical tools needed to assess cybersecurity risks.

### Learning Objectives

By the end of this lecture, you will be able to:

- Define and identify cybersecurity risks
- Understand different approaches to measuring risk
- Calculate risk probability and impact
- Use risk severity matrices for assessment
- Develop basic risk prevention strategies

---

### 1. Understanding Risk in Cybersecurity

#### What is Risk?

Risk in cybersecurity refers to the potential for loss, damage, or compromise of assets or data due to threats exploiting vulnerabilities in an information system.

**Key Components of Risk:**

- `Threats`: Potential dangers to your system
- `Vulnerabilities`: Weaknesses that can be exploited
- `Impact`: The consequence of a risk being realized
- `Likelihood`: The probability of a risk occurring

**Example:**

```
Scenario: School Database System
- Threat: Unauthorized access to student records
- Vulnerability: Weak password policy
- Impact: Privacy breach, legal consequences
- Likelihood: High (if no security measures are in place)
```

---

### 2. Measuring Risk - Basic Concepts

Risk measurement helps us quantify potential threats and make informed decisions about security measures.

**Risk Measurement Formula:**

```
Risk = Probability of Occurrence × Potential Impact
`

**Key Factors in Risk Measurement:**

- Frequency of potential threats
- Value of assets
- Cost of security measures
- Regulatory requirements
- Reputation damage

---

### 3. Probability Approach to Risk Measurement

#### Understanding Probability in Cybersecurity Context

**Probability Scale:**

| Level | Probability | Description |
|-------|-------------|-------------|
| 5 | Very High | 80-100% chance |
| 4 | High | 60-79% chance |
| 3 | Medium | 40-59% chance |
| 2 | Low | 20-39% chance |
| 1 | Very Low | 0-19% chance |

**Example Assessment:**

```
Calculating Probability:
1. Review historical data
2. Analyze threat intelligence
3. Consider current controls
4. Evaluate vulnerability exposure
```

**Practice Scenario:**

Assessing the probability of a phishing attack:

- Multiple attempts detected monthly
- Staff lacking security training
- No email filtering
- Probability Rating: 4 (High)

---

### 4. Impact Assessment

#### Measuring Value of Loss

**Impact Categories:**

- Financial Loss
- Data Breach
- Service Disruption
- Reputation Damage
- Legal Consequences

**Impact Scale:**

| Level | Severity | Financial Impact | Operational Impact |
|-------|----------|------------------|-------------------|
| 5 | Critical | >$100,000 | Complete shutdown |
| 4 | Major | $50,000-$100,000 | Significant disruption |
| 3 | Moderate | $10,000-$49,999 | Partial disruption |
| 2 | Minor | $1,000-$9,999 | Minor disruption |
| 1 | Negligible | <$1,000 | Minimal impact |

---

### 5. Risk Severity Matrix

The Risk Severity Matrix combines probability and impact assessments to prioritize risks.

```
Risk Severity Matrix:

Impact →
5 │ M H H E E
4 │ M M H H E
3 │ L M M H H
2 │ L L M M H
1 │ L L L M M
  └─────────────
    1 2 3 4 5
    Probability →

Legend:
E = Extreme Risk
H = High Risk
M = Medium Risk
L = Low Risk
```

**How to Use the Matrix:**

1. Determine probability (1-5)
2. Determine impact (1-5)
3. Find the intersection point
4. Identify risk level

**Example:**
```
Scenario: Malware infection
Probability: 4 (High)
Impact: 3 (Moderate)
Result: High Risk (intersection shows 'H')
```

---

### 6. Risk Prevention Matrix

#### Developing Prevention Strategies

**Prevention Framework:**
| Risk Level | Response | Actions Required |
|------------|----------|------------------|
| Extreme | Immediate | Implement controls immediately; may need to halt activities |
| High | Urgent | Develop specific action plan within 24 hours |
| Medium | Planned | Develop specific action plan within 1 week |
| Low | Monitored | Review during regular security assessments |

**Prevention Strategies by Risk Level:**

**Extreme Risk:**

- Immediate security patches
- System isolation if necessary
- Incident response team activation
- Management notification

**High Risk:**

- Security control implementation
- Enhanced monitoring
- Staff training
- Regular testing

**Medium Risk:**

- Documented procedures
- Regular updates
- Basic training
- Periodic reviews

**Low Risk:**

- Standard security measures
- Basic monitoring
- Annual reviews
- Documentation maintenance

---

### Practical Exercise

Let's assess a real-world scenario:

**Scenario: School Network File Share**

1. Identify potential threats
2. Rate probability
3. Assess impact
4. Use severity matrix
5. Determine prevention strategy

**Group Activity:**

Break into teams and analyze different aspects:

- Team 1: Network access threats
- Team 2: Data security
- Team 3: User behavior risks
- Team 4: System vulnerabilities

---

### Conclusion

Today we've covered the fundamental aspects of risk assessment in cybersecurity:

- Understanding risk components
- Measuring probability and impact
- Using risk matrices
- Developing prevention strategies

Remember: Risk assessment is an ongoing process, not a one-time activity. Regular reviews and updates are essential for maintaining effective security.

### Additional Resources

- NIST Cybersecurity Framework
- School IT Security Policy
- Cyber Risk Assessment Tools
- Educational Security Guidelines

---

### Next Steps

- Review the risk assessment tools provided
- Practice using the risk severity matrix
- Begin identifying risks in your own digital environment
- Prepare questions for next session's Q&A

