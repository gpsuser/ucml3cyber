# Lecture Content on Network Topologies

## Introduction

- Overview of network topologies.
- Importance of understanding network topologies.

## Features of Well-Known Network Topologies

### 1. Bus Topology

- **Description:** All devices share a single communication line or bus.
- **Diagram:**
  - Devices are connected to a central cable.
  - Data is transmitted in both directions.
  - A terminator is used at each end to prevent signal reflection.
![Bus Topology](/img/img17_1.png)

#### Pros and Cons:

| Pros | Cons |
|------|------|
| Easy to implement | Difficult to troubleshoot |
| Less cable required | A break in the bus stops all communication |
| Cost-effective for small networks | Limited cable length and number of devices |

### 2. Star Topology

- **Description:** All devices are connected to a central hub.
- **Diagram:**
    - Devices are connected to a central hub or switch.
    - Data is transmitted through the hub.
    - Failure of one device does not affect others.
![Star Topology](img/img17_2.png)

#### Pros and Cons


| Pros | Cons |
|------|------|
| Easy to add new devices | Expensive due to the central hub |
| Centralized management | Hub represents a single point of failure |
| Failure of one device does not affect others | More cable required than bus topology |

### 3. Ring Topology

- **Description:** Devices are connected in a circular fashion.
- **Diagram:**
    - Each device is connected to two other devices.
    - Data packets travel in one direction around the ring.
    - A break in the ring can disable the network.
![Ring Topology](img/img17_3.png)

#### Pros and Cons

| Pros | Cons |
|------|------|
| Data packets travel at high speed | A break in the ring can disable the network |
| No collisions | More difficult to configure and troubleshoot |
| Suitable for large networks | Limited scalability |

### 4. Mesh Topology

- **Description:** Each device is connected to every other device.
- **Diagram:**
![Mesh Topology](img/img17_4.png)

#### Pros and Cons

| Pros | Cons |
|------|------|
| Highly reliable | Expensive due to high cabling cost |
| No single point of failure | Complex to install and configure |
| Data can be transmitted simultaneously | Maintenance can be challenging |

### 5. Logical Network Topology

- **Description:** The arrangement of network devices and how data is transmitted logically through the network.
- **Examples:**
  - Logical Bus Topology
  - Logical Ring Topology

- **Diagram:**
  - Logical Bus Topology: Devices are connected to a central bus virtually.
  - Logical Ring Topology: Devices are connected in a ring virtually.
![Logical Network Topology](img/img17_5.png)
reference: <https://www.edrawsoft.com/logical-network.html>

#### Pros and Cons

| Pros | Cons |
|------|------|
| Flexibility in design | Complex to manage and troubleshoot |
| Can be implemented over different physical topologies | More difficult to secure |
| Easier to monitor and troubleshoot logically | Requires sophisticated management tools |

## Evaluation of Network Topologies

### Security Implications

- **Bus Topology:** Vulnerable to data collisions and security breaches as all devices share the same communication line.
- **Star Topology:** More secure as devices connect to a central hub, allowing for better control and monitoring.
- **Ring Topology:** Data can be intercepted easily if physical access to the ring is obtained.
- **Mesh Topology:** Highly secure as it supports multiple paths for data transmission, reducing the risk of interception.
- **Logical Network Topology:** Security depends on the physical implementation and management tools used.

### Implementation Considerations at the Organizational Level

- **Scalability:** How easily can new devices be added?
- **Cost:** What are the costs associated with implementing and maintaining the topology?
- **Maintenance:** How easy is it to troubleshoot and maintain the network?
- **Performance:** Does the topology support the required speed and reliability?

