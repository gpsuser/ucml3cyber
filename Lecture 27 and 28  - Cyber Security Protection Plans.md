# Lecture 27 and 28: Cyber Security Protection Plans


**Note to lecturer**: This content can be split into two separate lectures if needed (lecture 27 and 28).


## Introduction

In today's interconnected digital world, organizations face an ever-growing array of cyber threats that can disrupt operations, compromise sensitive data, and damage reputations. Developing a comprehensive cyber security protection plan is essential for any organization looking to safeguard its assets and maintain the trust of its stakeholders.

In this lecture, we will explore the key components of an effective cyber security protection plan. We'll define what a protection plan is, discuss its structure, and delve into the various protection methods available. We'll also consider important factors like technical and financial constraints, legal responsibilities, system usability, and cost-benefit analysis when designing a protection plan. We'll also cover how to develop a test plan to validate that the protection measures are working as intended.

Finally, we will dive deeper into the different types of protection methods and measures that can be implemented as part of such a plan. We will cover hardware, software, physical, and alternative risk management methods, along with examples for each category.

## Learning Objectives

By the end of this lecture, you should be able to:

1. Define what a cyber security protection plan is and why it's important
2. Describe the typical structure of a protection plan 
3. Identify common protection methods and the threats they address
4. Understand key considerations like constraints, legal duties, usability and ROI
5. Develop a test plan to verify protection measures are effective
6. Apply the concepts to design a complete cyber security protection plan
7. Identify and describe various hardware, software, physical, and alternative risk management protection methods
8. Understand the specific threats each protection method helps mitigate
9. Provide examples for each category of protection methods
10. Recognize the technical, financial, and legal considerations when implementing these measures

---

## 1. Cyber Security Protection Plans 

A cyber security protection plan is a documented strategy for mitigating the cyber risks facing an organization. Its purpose is to translate the threats and vulnerabilities identified during a risk assessment into actionable steps to protect the confidentiality, integrity and availability of an organization's systems and data.

The motivation for creating a protection plan is clear - once threats are identified, we need a systematic way to address them. Without a well-thought-out plan, an organization's response to cyber incidents will be ad-hoc, uncoordinated, and likely ineffective. A good protection plan helps an organization prioritize risks, assign responsibilities, and ensure appropriate controls are in place.

---

## 2. Structure of a Cyber Security Protection Plan

The structure of a cyber security protection plan centers around identifying a range of protection and mitigation controls that comprehensively cover the risks facing an organization. The plan needs to map out how the organization will prevent cyber threats from materializing and impacting operations.

A typical protection plan will include:

- An overview of the assets, systems and data in scope 
- A risk assessment identifying key threats and vulnerabilities
- Prioritization of risks based on likelihood and impact
- Protection measures mapped to each risk 
- Timelines and responsibilities for implementing controls
- Procedures for monitoring, reviewing and updating the plan

The goal is to have a centralised roadmap that directs an organization's cyber security efforts and ensures risks are managed to an acceptable level.

---

## 3. Protection Methods

The heart of any cyber security protection plan is the specific measures put in place to address identified risks. Let's explore some key aspects to consider when selecting and designing protection methods.

### 3.a. Threats Addressed by Protection Measure

Each protection measure in the plan should be tied back to the specific threat(s) it is intended to mitigate. This is typically done by referencing the risk ID from the earlier risk assessment.

| Protection Measure | Threats Addressed |
|--------------------|-------------------|
| Implement MFA for remote access | Risk 3.1 - Unauthorized access from stolen credentials |
| Patch management program | Risk 1.7 - Exploitation of known software vulnerabilities |

Mapping measures to risks creates traceability and helps ensure that all identified threats are covered by the plan.

### 3.b. Actions Taken

For each protection measure, the plan should clearly detail the specific actions that will be taken. This should be descriptive enough that someone else could implement the measure by following the plan.

| Protection Measure | Actions |
|--------------------|--------------------|
| Implement MFA for remote access | - Enforce MFA for all remote access methods (VPN, RDP, etc.)<br>- Use authenticator app or hardware tokens, not SMS<br>- Verify MFA is required for all accounts<br>- Train staff on MFA enrollment and usage |
| Patch management program | - Inventory all software and versions<br>- Subscribe to vendor notifications for patches<br>- Classify patches by severity using CVSS scoring<br>- Establish SLAs for testing and rolling out patches based on severity<br>- Use a patch management tool to streamline process |

Well-defined actions make the plan actionable and auditable - you can track what was done and validate it was done correctly.

### 3.c. Reasoning for Actions  

In addition to describing what will be done, the plan should justify why each measure was selected. This rationale demonstrates that the plan is addressing risks thoughtfully.

| Protection Measure | Reasoning |
|--------------------|-----------|
| Implement MFA for remote access | Remote access is a common intrusion vector, especially if credentials are stolen or guessed. MFA significantly reduces the risk of unauthorized access by requiring an additional verification factor beyond just a password. |
| Patch management program | Unpatched software vulnerabilities are a frequent target for attackers. Implementing a structured program to quickly identify, test and deploy critical patches makes it harder for attackers to exploit known vulnerabilities. |

Documenting the reasoning provides context for the selected measures and helps explain the plan to non-technical stakeholders.

### 3.d. Technical and Financial Constraints

Protection plans must consider the technical and financial constraints that may impact the feasibility of certain measures. 

#### Technical constraints

These relate to limitations in technology or the ability for people to effectively use it. Some examples:

| Constraint | Example |
|------------|---------|
| Difficulties in technical tasks | Configuring a router or firewall correctly requires specialist skills that the IT team may not have. |
| Limitations in security hardware/software | The performance of security monitoring tools may not be sufficient to process the volume of log data generated. |

#### Financial constraints 

These relate to the monetary costs associated with implementing protection measures. For example:

| Constraint | Example |
|------------|---------|
| Cost of staff | Hiring dedicated security personnel or training existing IT staff has a significant financial impact. |
| Cost of equipment | Upgrading firewalls or servers to support new security capabilities may exceed the available budget. |

The protection plan has to work within these constraints and tailor its recommendations accordingly.

### 3.e. Legal Responsibilities

A protection plan does not exist in isolation - it must consider the various legal and regulatory requirements that apply to the organization. Some key laws to be aware of:

| Law | Relevance to Cyber Security |
|-----|----------------------------|
| Data Protection Act & GDPR | Governs how personal data must be collected, processed and secured. Specifies breach notification requirements. |  
| Computer Misuse Act | Makes it an offense to access or modify computer material without authorization. |
| Telecommunications Regulations | Allows employers to monitor communications on their networks under certain conditions (e.g. for crime prevention). |
| Health & Safety at Work Act | Requires employers to provide a safe working environment, which extends to protection from cyber threats. |

As an example, if you implement network monitoring software, you must ensure it complies with the Telecommunications Regulations regarding interception of communications.

Having a good understanding of legal duties helps ensure the protection plan doesn't put the organization at regulatory risk.

### 3.f. Usability of the System

It's important to consider how cyber security measures will impact the usability and performance of an organization's systems. If protection methods make it too difficult for people to do their jobs, they will find ways to circumvent them. 

Some examples of how security can degrade usability:

| Usability Impact | Example |
|------------------|---------|
| Reduced system performance | Anti-malware scans or real-time backup may slow down computers, frustrating users. |
| Limits on staff activities | Firewalls blocking access to certain websites or requiring admin rights for common tasks hampers productivity. |  
| Poor user experience | Forcing complex passwords and frequent changes, or implementing clunky VPN login processes makes systems hard to use. |

Balancing security and usability is an art - the protection plan needs to secure systems while limiting friction in business workflow as much as possible. Soliciting user feedback is important to get this balance right.

### 3.g. Cost-Benefit Analysis

Implementing cyber security measures comes at a cost, both financial and in terms of effort. A key part of the protection plan is weighing these costs against the benefits provided by the security control.

Imagine you are looking to implement anti-malware software:

- Costs: Price of software licenses (let's say $50 per user per year)
- Benefits: Protection against malware infections, which could lead to data loss, system downtime, reputational harm
- Analysis: The potential impact of a malware incident would likely far exceed the cost of prevention, so the benefits outweigh the costs

In essence, the protection plan needs to help the organization get the maximum risk reduction for its available resources. Focus on controls that have the biggest impact in reducing risk exposure.

### 3.h. Test Plan

The final piece of a solid protection plan is a way to validate if the defined security measures are working as intended. This is done through a test plan.

A good test plan has the following components:

| Component | Description | Example |
|-----------|-------------|---------|
| Test ID | A unique identifier for the test case | TC 5.1 |
| Test Procedure | Step-by-step instructions for conducting the test | 1. Take a device without antivirus<br>2. Attempt to install malware<br>3. Verify malware is blocked from installing |  
| Expected Result | The outcome that indicates the control is working correctly | Malware installation is prevented |
| Further Actions | Steps to take if the test fails | Investigate AV configuration, submit ticket with vendor |

Running through the test plan periodically helps identify gaps in the protection measures and drives continuous improvement.

## Worked Example

Let's bring this all together with a worked example of a cyber security protection plan for a mid-sized financial services firm, ACME Investments, that just completed a risk assessment. One of the high-risk items identified was the potential for data breaches via lost or stolen laptops.

To address this, the protection plan defines the following:

| Plan Component | Details |
|----------------|---------|
| Risk ID | ACME-014 |
| Risk Description | Sensitive client data may be exposed if a laptop is lost or stolen | 
| Protection Measure | Implement full disk encryption (FDE) on all company laptops |
| Actions | - Deploy BitLocker on all Windows 10 laptops<br>- Enforce FDE policy via Active Directory<br>- Verify encryption is enabled on all laptops<br>- Train staff on proper handling of laptops |
| Rationale | FDE protects data by making it unreadable if a laptop is lost or stolen. BitLocker is built-in to Windows, making deployment straightforward. |
| Technical Constraints | Some older laptops may not have a TPM chip, requiring use of a USB startup key. |  
| Financial Constraints | $6,000 for deployment services from IT partner. No licensing cost as BitLocker is included in Windows. |
| Legal Considerations | Fulfills GDPR requirement to use encryption to protect personal data. |
| Usability Impact | Negligible - transparent to users after initial setup. May add a few seconds to boot time. |
| Cost-Benefit | Deployment cost is small compared to potential fines and reputational damage from a data breach. Clear benefit. |
| Test Plan | <u>Test Case ID</u>: TC-014-01<br><u>Procedure</u>: Inspect a sample of laptops to verify BitLocker is enabled<br><u>Expected Result</u>: Disk is encrypted, recovery key is backed up, laptop starts up normally<br><u>Failed Test Actions</u>: Enable BitLocker if disabled, escalate if technical issues |

By working through this structured thought process, ACME Investments can have confidence that the protection plan is addressing the laptop risk in an appropriate and effective way. The other identified risks would be handled similarly.

---

## 4. Different Types of Protection Methods/Measures

Cybersecurity protection methods and measures are essential tools in defending against the ever-evolving landscape of cyber threats.

These methods can be broadly categorized into:

- hardware 
- software 
- physical and 
- alternative risk management measures. 

Each category plays a crucial role in protecting an organization's digital assets, and a comprehensive cybersecurity plan should incorporate a combination of these measures based on the organization's specific needs and risk profile.

### 4.a. Hardware Protection Methods

Hardware protection methods involve the use of physical devices to secure a network and its connected devices. These methods help protect against various threats, including unauthorized access, data interception, and denial-of-service (DoS) attacks. 

Some common hardware protection methods include:

1. **Hardware Firewalls**: These devices sit between a network and the internet, filtering traffic and preventing DoS attacks, malware, and hackers from exploiting open ports. They protect all PCs on a network.

2. **Routers**: When paired with a switch, routers can segment a network, providing an additional layer of security. Many routers also have built-in Virtual Private Network (VPN) capabilities, which encrypt data sent over the network, preventing sniffing attacks.

3. **Wireless Access Points**: Proper configuration of wireless access points is crucial for securing a wireless network. This includes using WPA2 encryption, setting complex passwords, turning off WPS, and implementing address filtering. These measures help prevent unauthorized access to the wireless network.

Example:
| Hardware Protection Method | Threat Mitigated                                      |
|----------------------------|--------------------------------------------------------|
| Hardware Firewall          | DoS attacks, malware, unauthorized access via open ports |
| Router with VPN            | Data interception, network segmentation                 |
| Properly configured WAP    | Unauthorized access to wireless network                 |

### 4.b. Software Protection Methods

Software protection methods use programs and applications to secure devices and data from various cyber threats. These methods are essential for maintaining the integrity, confidentiality, and availability of an organization's digital assets. Some common software protection methods include:

1. **Anti-Malware**: Anti-malware software helps prevent the majority of malware attacks by detecting and removing malicious software from devices. However, it requires constant updating to remain effective against new threats.

2. **Software Firewalls**: Unlike hardware firewalls that protect an entire network, software firewalls prevent unauthorized access to individual computers. They monitor and control incoming and outgoing network traffic based on predetermined security rules.

3. **Information Availability Measures**: These measures aim to limit the effects of data loss through techniques such as redundancy, failover, and RAID. Port scanning, a preventative measure, helps identify open ports that can then be closed using a firewall when required.

4. **Access Rights Management**: Controlling user account privileges is crucial for preventing staff from accessing data they shouldn't, limiting the impact of a malicious user gaining access to an account.

Example:
| Software Protection Method | Threat Mitigated                                  |
|----------------------------|---------------------------------------------------|
| Anti-Malware               | Malware attacks (requires constant updating)       |
| Software Firewall          | Unauthorized access to individual computers        |
| Information Availability   | Data loss, unauthorized access via open ports       |
| Access Rights Management   | Unauthorized access, insider threats               |

### 4.c. Physical Protection Methods

Physical protection methods focus on securing the physical environment in which an organization's digital assets are stored and accessed. These methods help prevent unauthorized physical access to sensitive data and equipment, as well as mitigate the impact of physical threats such as theft or damage. Some common physical protection methods include:

1. **Locks on Doors/Cabinets**: Locks make rooms (e.g., server rooms) inaccessible to unauthorized people and prevent access to hardware stored in cabinets. Hardware can also be locked to desks for added security.

2. **CCTV**: While not strictly a preventative measure, CCTV can gather visual evidence if a security breach occurs. Security personnel may be able to catch the perpetrator if they detect the incident in time.

3. **Alarm Systems**: Alarm systems trigger when unauthorized persons access a restricted area, giving the perpetrator less time to damage or steal data or equipment before security arrives.

4. **Backups**: Regular backups protect against any threat that causes harm to data through deletion or modification. Data can be easily recovered, mitigating the impact of a successful attack.

Example:
| Physical Protection Method | Threat Mitigated                                     |
|----------------------------|------------------------------------------------------|
| Locks on Doors/Cabinets    | Unauthorized physical access to sensitive areas/equipment |
| CCTV                       | Provides visual evidence of security breaches          |
| Alarm Systems              | Deters unauthorized access, reduces response time      |
| Backups                    | Data loss due to deletion or modification             |

### 4.d. Alternative Risk Management Measures

In addition to hardware, software, and physical protection methods, organizations can employ alternative risk management measures to mitigate cybersecurity risks. These measures involve strategic decisions that help reduce an organization's exposure to potential threats. Some common alternative risk management measures include:

1. **Risk Transfer to a Third Party**: Outsourcing activities that could lead to vulnerabilities, such as online payment processing (e.g., using PayPal), can help transfer responsibility and risk to a service provider.

2. **Risk Avoidance**: Organizations may choose to stop activities that could lead to vulnerabilities completely. They may start alternative activities that carry less risk.

3. **Risk Acceptance**: Some risks may be too costly to address relative to their potential impact. Often, these risks will be classified as "Low" and accepted by the organization.

Example:
| Alternative Risk Management Measure | Description                                                  |
|-------------------------------------|--------------------------------------------------------------|
| Risk Transfer to a Third Party      | Outsourcing online payment processing to PayPal               |
| Risk Avoidance                      | Stopping high-risk activities and adopting safer alternatives |
| Risk Acceptance                     | Accepting low-impact risks that are too costly to mitigate    |

---

## EXAM NOTES

Please note the following points for the exam:

### Technical and Financial Constraints

- Document any technical or financial constraints you find for each protection method and state how heavily they affect us implementing the measure.

### Legal Responsibilities

- Document how these laws may need to be considered when implementing the protection methods. This could mean: How the legislation could impact the business if a protection measure isn't implemented and the considerations that may limit implementation.

### Cost Benefit

- Explain the costs that may be involved (what the benefits of this cost are, do they benefits outweigh the costs).

### Test Plan

- One protection method will likely need 2/3 more tests.

---

## Conclusion

Developing a robust cyber security protection plan is a critical step in an organization's journey to managing cyber risk. By methodically analyzing risks, designing controls thoughtfully, and continuously validating effectiveness, an organization can build resilience against ever-evolving cyber threats. 

The protection plan serves as the organization's roadmap, guiding decisions and investments in security. But it's a living document - as the threat landscape shifts and new risks emerge, the plan must adapt in lockstep. 

Cyber security is a team sport. Business leaders, IT teams and front-line employees all have a role in implementing the plan and providing feedback for improvement. Fostering a culture of security awareness and responsibility is key.

By diligently executing on a well-crafted cyber security protection plan, organizations can forge ahead with greater confidence that their most valuable assets - their systems, data and reputation - are secured.

This lecture session also explored the various types of protection methods and measures that can be incorporated into a comprehensive cybersecurity protection plan.

- We discussed hardware, software, physical, and alternative risk management measures, along with examples for each category.

It is essential to understand that no single measure can provide complete protection against all cyber threats. A well-rounded cybersecurity plan should include a combination of these methods tailored to an organization's specific needs, risk profile, and regulatory requirements. 

- Always consider the technical, financial, and legal constraints when implementing these measures, and ensure that the benefits outweigh the costs. 
- Regular testing and updating of these protection methods are crucial for maintaining a robust cybersecurity posture in the face of evolving threats.

## References

1. Talabis, M. & Martin, J. (2012). Information Security Risk Assessment Toolkit. Syngress. 
2. International Organization for Standardization. (2013). ISO/IEC 27001 - Information security management.
3. National Institute of Standards and Technology. (2018). Framework for Improving Critical Infrastructure Cybersecurity, Version 1.1.
4. UK Information Commissioner's Office. (n.d.). Guide to the General Data Protection Regulation (GDPR).
5. European Union Agency for Cybersecurity. (2020). Cybersecurity for SMEs: Challenges and Recommendations. https://www.enisa.europa.eu/publications/cybersecurity-for-smes
6. International Organization for Standardization. (2013). ISO/IEC 27001:2013 Information technology — Security techniques — Information security management systems — Requirements. https://www.iso.org/standard/54534.html
7. Gale, A. (2024). Lecture 27 and 28 Cyber Security Protection Plans [PowerPoint slides].Retrieved from [URL](https://teams.microsoft.com/)
