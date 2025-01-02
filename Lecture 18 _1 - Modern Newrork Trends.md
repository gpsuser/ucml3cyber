# Lecture 18_1 - Computer Networks - Architectures and Modern Trends

## Learning Aims

By the end of the session, students will be able to:

* List the architectures of modern network technologies and related features.
* List modern network trends.

---

## Network Architectures

### Peer-to-Peer (P2P)

- **Definition**: A decentralized network where each device (peer) has equal status and can act as both client and server.
- **Features**:
  - No central authority.
  - High redundancy and resilience.
  - Examples: File-sharing networks (BitTorrent).
- **Security Implications**:
  - Difficult to control access and data.
  - Increased vulnerability to malware and unauthorized access.

### Client-Server

- **Definition**: A centralized network where client devices request resources and services from centralized servers.
- **Features**:
  - Centralized control and resource management.
  - Easier to manage and secure.
  - Examples: Web services, email servers.
- **Security Implications**:
  - Central point of failure.
  - Easier to implement security measures like firewalls and access control.

### Thin Client

- **Definition**: A network architecture where the client performs minimal processing and relies on a central server for processing and storage.
- **Features**:
  - Reduced client hardware costs.
  - Centralized data and application management.
  - Examples: Virtual desktops.
- **Security Implications**:
  - Centralized security management.
  - Dependence on network reliability.



---

## Modern Network Trends

### Virtualization

- **Definition**: Creating virtual versions of physical hardware to optimize resource utilization.
- **Examples**: Virtual machines, virtual networks.
- **Security Implications**:
  - Isolation between virtual instances.
  - Risk of hypervisor attacks.

### Cloud Computing

- **Definition**: Delivering computing services over the internet.
- **Examples**: AWS, Google Cloud, Microsoft Azure.
- **Security Implications**:
  - Data privacy and compliance.
  - Reliance on third-party security measures.

### Bring Your Own Device (BYOD)

- **Definition**: Policy allowing employees to use personal devices for work purposes.
- **Security Implications**:
  - Increased risk of data breaches.
  - Need for robust mobile device management (MDM) solutions.

### Software Defined Networking (SDN)

- **Definition**: Approach to network management that allows programmatically efficient network configuration to improve performance and monitoring.
- **Security Implications**:
  - Centralized control can be a target for attacks.
  - Enhanced network monitoring capabilities.

### Internet of Things (IoT)

- **Definition**: Network of interconnected devices capable of collecting and exchanging data.
- **Examples**: Smart homes, industrial IoT.
- **Security Implications**:
  - Large attack surface.
  - Challenges in device authentication and encryption.

### Additional Trends

- **Edge Computing**:
  - **Definition**: Processing data near the source rather than in a centralized data-processing warehouse.
  - **Examples**: IoT devices, content delivery networks.
  - **Security Implications**:
    - Improved data processing speed and security.
    - Security challenges in distributed architecture.

---

## Diagrams and Tables

### Network Architectures Comparison Table

| Architecture      | Definition                      | Features                                   | Security Implications                  |
|-------------------|---------------------------------|--------------------------------------------|----------------------------------------|
| Peer-to-Peer (P2P)| Decentralized network           | High redundancy, no central authority      | Hard to control access, malware risks  |
| Client-Server     | Centralized network             | Central management, easier to secure       | Single point of failure, manageable    |
| Thin Client       | Minimal client processing       | Centralized data, reduced client costs     | Centralized security, network reliance |


### Modern Network Trends Comparison Table

| Trend                   | Definition                                 | Examples                                | Security Implications                  |
|-------------------------|--------------------------------------------|-----------------------------------------|----------------------------------------|
| Virtualization          | Creating virtual versions of hardware      | Virtual machines, virtual networks      | Isolation, hypervisor attacks          |
| Cloud Computing         | Delivering services over the internet      | AWS, Google Cloud, Azure                | Data privacy, third-party reliance     |
| Bring Your Own Device   | Allowing personal devices for work         | -                                       | Data breaches, need for MDM            |
| Software Defined Networking | Programmatically efficient network control | -                                       | Central control target, network monitoring |
| Internet of Things      | Interconnected devices exchanging data     | Smart homes, industrial IoT             | Large attack surface, device security  |
| Edge Computing          | Processing data near the source            | IoT devices, content delivery networks  | Improved speed, distributed challenges |

## References

1. Gale, A. (2024). Lecture 18_1 Modern Network Trends [PowerPoint slides].Retrieved from [URL](https://teams.microsoft.com/)