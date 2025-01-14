# Lecture 29 - Incident Response in Cyber Security

## Introduction

In today's digital landscape, organizations of all sizes are at risk of falling victim to cyber attacks and data breaches. Having a well-defined incident response plan is crucial for minimizing the impact of such incidents and ensuring a rapid recovery. In this lecture, we will delve into the essential components of an effective incident response policy and explore the stages of handling a cyber security incident.

## Learning Objectives

By the end of this lecture, you should be able to:

1. Define what an incident response policy is and explain its significance
2. Identify the key elements that should be included in an incident response policy document
3. Describe and explain the stages of the incident response process
4. Understand the importance of following the incident response stages in the correct order

## What is an Incident Response Policy?

An incident response policy is a set of guidelines that helps IT staff detect, respond to, and recover from network security incidents such as data breaches, malware infections, and denial-of-service attacks. 

The policy outlines an organization's incident response capabilities and provides a roadmap for handling incidents in a way that minimizes damage and aligns with business objectives.

Think of an incident response policy as a fire evacuation plan for your organization's digital assets. 

* Just as a fire evacuation plan lays out clear procedures for safely exiting a building during an emergency, an incident response policy provides a step-by-step guide for dealing with a cyber security crisis. 

* Having this plan in place ensures that everyone knows their role and can act decisively to contain the damage and restore normal operations.

### Key Elements of an Incident Response Policy Document

A comprehensive incident response policy document should include the following elements:

| Element | Description | Example |
|---------|-------------|---------|
| Roles and responsibilities | Define the roles and responsibilities of the incident response team members, including who will lead the team, who will communicate with stakeholders, and who will perform technical tasks. | - Incident Response Manager: Oversees the entire incident response process<br>- Security Analyst: Conducts forensic analysis and containment<br>- Public Relations Specialist: Handles external communications |
| Incident categories and severity levels | Establish a clear categorization scheme for different types of incidents and their corresponding severity levels. This helps prioritize response efforts and allocate resources appropriately. | - Severity 1 (Critical): Data breach exposing sensitive customer information<br>- Severity 2 (High): Ransomware infection on multiple servers<br>- Severity 3 (Medium): Phishing email resulting in compromised user account |
| Detection and analysis standards | Specify the tools, techniques, and thresholds used to detect and analyze potential security incidents. This ensures consistency and thoroughness in the identification process. | - Monitor network traffic for unusual spikes or patterns<br>- Use threat intelligence feeds to identify known malware signatures<br>- Investigate alerts that exceed a certain risk score threshold |
| Containment, eradication, and recovery processes | Document the steps to be taken to contain the spread of an incident, eliminate the root cause, and restore affected systems to normal operation. This provides a clear action plan for the incident response team. | - Isolate infected systems by disconnecting them from the network<br>- Deploy security patches and updates to remove vulnerabilities<br>- Restore clean backups of critical data and systems |
| Evidence gathering and handling guidelines | Establish procedures for collecting, preserving, and documenting evidence related to the incident. This is critical for forensic analysis, legal proceedings, and preventing future incidents. | - Create forensic disk images of affected systems<br>- Store logs and network capture files securely<br>- Document all incident response actions taken in a centralized ticketing system |
| Communication protocols | Define how and when to communicate about the incident, both internally to employees and executives and externally to customers, partners, and media. This helps ensure timely and appropriate information sharing. | - Notify executive team within 1 hour of confirming a severe incident<br>- Provide daily status updates to affected departments<br>- Coordinate public statements with legal and PR teams |
| Post-incident review process | Specify the steps for conducting a thorough review of the incident response process after resolution. This helps identify areas for improvement and update the policy and procedures accordingly. | - Hold a "lessons learned" meeting with all involved parties<br>- Analyze the timeline of events and response actions<br>- Develop an action plan to address any deficiencies identified |

Having these components clearly defined in the incident response policy document provides a solid foundation for an organization to effectively prepare for, detect, and handle security incidents.

## Stages of Incident Response

Now, let's walk through the key stages of responding to a cyber security incident. These stages provide a structured approach to minimize the impact of an incident and prevent future occurrences.

1. **Assembling CSIRT and Initial Assessment**
   - A cross-functional Cyber Security Incident Response Team (CSIRT) should be assembled, including representatives from IT, security, legal, HR, and public relations.
   - Clear incident reporting procedures must be established and communicated to all staff. This includes designating points of contact and specifying the information to be included in incident reports.
   - The CSIRT performs an initial assessment to determine the scope and severity of the incident. This follows a "plan, do, check, act" cycle to ensure a systematic approach.

2. **Containing Damage and Minimizing Risk**
   - The top priority is protecting people's physical safety. If an incident poses any risk to human safety (e.g., a compromised industrial control system), appropriate authorities must be notified immediately.
   - Sensitive data and systems should be isolated to prevent further unauthorized access. This might involve disconnecting affected systems from the network, revoking compromised user accounts, or temporarily shutting down certain services.
   - Steps are taken to preserve evidence that may be needed for forensic analysis or legal action, such as creating disk images and log backups. Care must be taken not to inadvertently modify or destroy evidence in the process.
   - Efforts are made to maintain business continuity and minimize disruption to normal operations. This could involve failover to backup systems, alternate communication channels, or temporary manual processes.

3. **Identifying the Type and Severity of the Compromise**
   - The CSIRT works to determine how the organization's security was breached and the extent of the damage. This involves answering questions such as:
     - What type of attack occurred? Was it malware, social engineering, a denial-of-service attack, or some combination?
     - Where did the attack originate from? Can specific IP addresses, domains, or user accounts be identified as the source?
     - What appears to be the attacker's intent? Are they seeking to steal data, disrupt operations, or damage the organization's reputation?
   - Compromised systems and data must be thoroughly examined, which requires careful log analysis and data inspection. This helps establish the timeline of the incident and identify all affected assets.

4. **Protecting Evidence**
   - To support legal action or prevent similar future incidents, evidence must be carefully preserved. This includes making copies of logs, email, and other relevant records.
   - Forensic copies of affected systems should be created and securely stored, with the original evidence removed from the network to prevent tampering. Industry-standard tools and procedures must be used to ensure the integrity and admissibility of the evidence.
   - Ultimately, compromised systems should be wiped clean and restored from trusted backups to ensure no malicious code or vulnerabilities persist. Simply removing malware is not sufficient, as the system may have been modified in other ways.

5. **Notifying External Agencies**
   - Depending on the nature of the incident, it may be necessary to notify various external parties:
     - Legal representatives can advise on compliance with data breach notification laws and potential legal action.
     - Law enforcement should be engaged if criminal activity is suspected, to aid in investigation and prosecution.
     - External security experts or incident response consultants can provide valuable assistance with forensics, mitigation, and recovery.
     - If the incident may affect customers, partners, or the public, the media may need to be notified in a controlled manner.
   - All external communications should be coordinated through designated spokespeople to ensure a consistent and appropriate message. Employees should be instructed not to discuss the incident outside the organization.

6. **System Recovery**
   - The timing and extent of the incident must be established in order to determine the appropriate recovery approach. If the initial compromise occurred months ago, much more extensive rebuilding may be necessary.
   - Without reliable backups, some systems or data may be permanently lost. Having a comprehensive disaster recovery plan that is regularly tested is crucial.
   - Recovery efforts must be carefully coordinated to avoid reintroducing vulnerabilities or destroying evidence. Clean installations of operating systems and applications are preferable to simply removing malware and hoping for the best.

7. **Compiling and Organizing Evidence**
   - Thorough documentation of the incident and response efforts is essential for legal purposes and future prevention.
   - A clear timeline should be constructed, detailing what actions were taken by the CSIRT, when, and why. This helps provide a coherent narrative for both internal and external stakeholders.
   - All relevant logs, disk images, network captures, and other evidence should be securely archived and documented. Establishing a clear chain of custody for all evidence is also critical to ensure admissibility in legal proceedings.

8. **Reviewing Outcomes**
   - Once the incident is resolved, the response process should be evaluated to identify areas for improvement. This is often done through a formal "lessons learned" meeting with all involved parties.
   - Insights gained should be incorporated into the organization's security awareness training, incident response procedures, and architectural decisions:
     - Were detection mechanisms adequate or do additional tools or logging need to be implemented? 
     - Is additional training needed for employees on topics like phishing or secure password practices?
     - Should certain systems or applications be hardened, isolated, or retired altogether based on the risks they pose?
   - Examining root causes can help prioritize security initiatives and investments to prevent repeat incidents. Vendor relationships, employee access policies, and network segmentation are common areas that may need improvement.

To help visualize these stages, here is a summary table:

| Stage | Key Activities |
|-------|---------------|
| 1. Assembling CSIRT and Initial Assessment | - Form cross-functional team<br>- Establish reporting procedures<br>- Assess scope and severity |
| 2. Containing Damage and Minimizing Risk | - Protect physical safety<br>- Isolate affected systems<br>- Preserve evidence<br>- Maintain business continuity |
| 3. Identifying Type and Severity of Compromise | - Determine attack vector and intent<br>- Analyze logs and data<br>- Establish incident timeline |  
| 4. Protecting Evidence | - Create forensic copies<br>- Secure original evidence<br>- Clean and restore systems |
| 5. Notifying External Agencies | - Engage legal, law enforcement, experts<br>- Comply with reporting requirements<br>- Coordinate crisis communication |
| 6. System Recovery | - Determine recovery approach<br>- Restore from backups<br>- Avoid reintroducing vulnerabilities |
| 7. Compiling and Organizing Evidence | - Document incident and response<br>- Construct clear timeline<br>- Establish chain of custody |  
| 8. Reviewing Outcomes | - Conduct lessons learned exercise<br>- Update training and procedures<br>- Prioritize preventive measures |

## Stages of Incident Response - Example Scenario

Upon detecting unusual network activity, the security monitoring team at the financial institution immediately notifies the Cyber Security Incident Response Team (CSIRT).

### Assembling CSIRT and Initial Assessment

* The CSIRT, consisting of representatives from IT, security, legal, HR, and public relations, is quickly assembled to assess the situation.

* The CSIRT follows established incident reporting procedures, which include documenting the initial signs of the incident and gathering preliminary information about potentially affected systems.

* The team performs an initial assessment to determine the scope and severity of the incident. They discover that several servers have been encrypted with ransomware, impacting critical financial transaction processing systems.


### Containing Damage and Minimizing Risk

* The CSIRT's first priority is to contain the spread of the ransomware. They quickly isolate the infected servers by disconnecting them from the network and halting all financial transactions to prevent further damage.

* The team also takes steps to preserve evidence by creating forensic disk images of the affected systems before beginning any recovery efforts. This will be crucial for later analysis and potential legal action.

* To maintain business continuity, the CSIRT activates the organization's disaster recovery plan, which includes failover to backup systems located in a separate data center. While some services may be temporarily disrupted, this allows the organization to continue processing critical transactions.


### Identifying the Type and Severity of the Compromise

* With the immediate threat contained, the CSIRT begins a deeper investigation into the nature of the attack. They analyze network logs and system data to determine the initial point of entry (in this case, a phishing email that tricked an employee into downloading a malicious attachment).

* The team identifies the specific strain of ransomware used in the attack and researches its known behaviors and potential recovery methods. They also assess the extent of the damage by identifying all systems and data that were encrypted.

* Through careful analysis, the CSIRT determines that the attackers were primarily seeking a quick payout rather than stealing sensitive data. However, they cannot rule out data exfiltration, so they prepare to notify relevant authorities and affected customers.


### Protecting Evidence

* As the investigation progresses, the CSIRT takes great care to protect and preserve all relevant evidence. They create additional backups of system logs, network captures, and disk images, storing them in a secure, isolated environment.

* The team documents all of their actions and findings in a detailed incident report, which will serve as a critical record for both internal learning and potential legal proceedings.

* Once all necessary evidence is collected and preserved, the CSIRT begins the process of cleaning the infected systems. They wipe the affected servers and restore them from clean, pre-incident backups to ensure no trace of the ransomware remains.

### Notifying External Agencies

* Given the severity of the incident and the potential impact on customer data, the financial institution's legal team advises notifying relevant regulatory agencies, such as the Federal Trade Commission (FTC) and the Financial Industry Regulatory Authority (FINRA).

* The CSIRT also contacts law enforcement, including the FBI's Internet Crime Complaint Center (IC3), to report the attack and share evidence that could aid in identifying and prosecuting the attackers.

* To transparently communicate with customers and mitigate reputational damage, the public relations team drafts a statement explaining the incident, the steps taken to contain it, and the measures being implemented to prevent future occurrences. This statement is reviewed by the legal team before being released.


### System Recovery

* With the infected systems cleaned and restored from backups, the CSIRT begins the process of bringing all services back online. They carefully monitor network traffic and system logs for any signs of residual malware or renewed attack.

* The team also implements additional security measures, such as updated firewall rules and endpoint detection and response (EDR) tools, to harden the organization's defenses against future ransomware attempts.

* Throughout the recovery process, the CSIRT provides regular status updates to executive leadership and affected departments to ensure clear communication and coordinate any necessary customer outreach.


### Compiling and Organizing Evidence

* As the incident winds down, the CSIRT collects all relevant documentation, including the initial incident report, forensic analysis results, system recovery logs, and communication records with external agencies.

* The team organizes this evidence into a comprehensive incident timeline, detailing every action taken from initial detection through to full recovery. This timeline will be essential for both internal review and potential legal or regulatory inquiries.

* All physical and digital evidence, including disk images, network captures, and system logs, are securely archived and cataloged to maintain the chain of custody and ensure admissibility in court if necessary.


### Reviewing Outcomes

* Once the incident is fully resolved, the financial institution conducts a thorough post-incident review. The CSIRT, along with representatives from various departments, holds a "lessons learned" meeting to discuss what worked well, what didn't, and what could be improved in future incident response efforts.

* The team identifies several areas for improvement, including the need for more frequent employee security awareness training (particularly around phishing), better network segmentation to limit the spread of malware, and more robust backup and recovery procedures.

* Based on these findings, the CSIRT updates the organization's incident response policy and procedures, incorporating the lessons learned. They also develop a plan to implement the identified security improvements over the coming months, with regular progress check-ins.

---

By working through these stages in order, the financial institution was able to effectively contain the ransomware outbreak, minimize data loss, and restore critical services. While the incident was certainly costly and disruptive, the existence of a well-defined incident response plan and a prepared CSIRT helped the organization weather the storm and emerge stronger.

## The Importance of Sequence

It's crucial to understand that the order in which these incident response stages are executed matters a great deal. Proceeding in the wrong sequence can have serious negative consequences, such as:

- Inadvertently tipping off the attacker, allowing them to cover their tracks or cause additional damage
- Destroying or contaminating crucial forensic evidence that could be used for attribution or prosecution
- Interrupting business operations unnecessarily or prematurely, compounding the financial impact
- Delaying public disclosures, leading to reputational damage and potential legal liability

Think of it like triage in an emergency room - stabilizing the patient (containing damage) always comes before conducting detailed diagnostics (identifying compromise) or planning long-term treatment (recovery and review). While some stages may overlap or happen in parallel, the overall flow from initial assessment through to review and refinement should be maintained as much as possible to ensure an effective response.

## Conclusion

In today's threat landscape, a well-crafted incident response policy and a prepared, coordinated CSIRT are essential for any organization. By methodically working through the stages of incident response in the correct order, organizations can minimize losses, preserve evidence, prevent future incidents, and ultimately emerge stronger and more resilient.

As cyber threats continue to evolve in both sophistication and frequency, building organizational muscle memory around these incident response procedures is one of the best investments any entity can make. Regularly exercising your incident response plan through tabletop simulations and hands-on drills is the key to being truly prepared. Like a well-rehearsed fire drill, practicing your response before an actual emergency can make all the difference.

While prevention is always the first line of defense, no security controls are perfect. When incidents do occur, having a swift, coordinated, and thorough response is the next best thing. By following the guidelines laid out in this lecture and continuously refining your incident response capabilities, you can significantly reduce the impact of security breaches and reinforce customer trust in your organization.


## References

1. NIST Computer Security Incident Handling Guide (https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r2.pdf) 
2. SANS Incident Handler's Handbook (https://www.sans.org/white-papers/33901/)
3. CERT Guide to Coordinated Vulnerability Disclosure (https://resources.sei.cmu.edu/asset_files/SpecialReport/2017_003_001_503340.pdf)