# Cisco Product Lines Overview Guide

**TODO:** A brief overview of Cisco ASA, ISR, Catalyst, and Nexus devices.

#### Table of Contents

1. [ASA, ISR, Catalyst, Nexus: What Each Device is For](#uses)
2. [ASA, ISR, Catalyst, Nexus: A Comparison and Contrast Table](#table)
3. [Popular Models](#models)
4. [Supplemental Resources](#supplemental)

<hr />

## 1. <a name="uses">ASA, ISR, Catalyst, Nexus: What Each Device is For</a>

* **Cisco Adaptive Security Appliances (ASAs):** These are, traditionally, *firewalls*, with more recent models being Next-Generation Firewalls (NGFWs). It is common for networks to pair dedicated ASAs with routers (such as Cisco ISRs), due to the potential of advanced firewall rules and support for VPN connectivity.
* **Cisco Integrated Services Routers (ISRs):** Although these are *routers*, many of these devices are also flexible and powerful all-in-one interfaces, providing such additional mechanisms as VPN termination points and NGFW capabilities.
* **Cisco Catalyst:** These Cisco switches are especially common solutions for *campus networks*, connecting users, interfaces, and Wireless Access Points (WAPs) throughout the enterprises.
* **Cisco Nexus:** These are also Cisco switches, and are especially common solutions for *data centers* where high standards of performance for virtualization, switching, and single-fabric storage are enforced.

Please note that Cisco offers many more product lines than these four, and that some of them may be added to this guide as it expands.
  
<hr />

## 2. <a name="table">ASA, ISR, Catalyst, Nexus: A Comparison and Contrast Table</a>

| Feature | Cisco Adaptive Security Appliance (ASA) | Cisco Integrated Services Router (ISR) | Cisco Catalyst | Cisco Nexus |
| :-----: | :-----: | :-----: | :-----: | :-----: |
| Purpose | Traditionally firewall services, but now offering NGFW functionalities (e.g., VPNs, Network Intrusion Prevention). | Suitable for smaller-to-medium sized organizations, and providing all-in-one service solutions (e.g., routing, switching, security, VoIP). | An industry-standard user access switching solution, with wireless support. | Appropriate for large data center switching needs, with high scalability, massive storage potential, and support for complex virtualized images. |
| Switching and/or Routing | May be able to route/have limited layer 3 functionality. | | |
| OS | Linux-based *ASA Software* OS, using the 'lina' executable. | | |
| Network Placement | Typically deployed on the network's perimeter, guarding the boundaries of the network. | | |
| Security | Provides stateful firewalling and complex traffic inspection functionalities. | | |
| Scalability | Highly scalable, whether for SOHOs or large enterprise networks. | | |

<hr />

## 3. <a name="models">Popular Models</a>

*Popular Models of Cisco Adaptive Security Appliances (ASAs) include:*

* **55 Series:** The *5505* model was intended for smaller organizations, with Power over Ethernet (PoE) ports and in-built switching technology. The *5585-X* is intended for larger data centers.
* **Firepower:** A more contemporary product line, with generally higher level throughput support and additional security mechanisms.

*Popular Models of Cisco Integrated Services Routers (ISRs) include:*

* **4000 Series:** Modular routers suitable for smaller enterprises.
* **1000 Series:** Supports more complex cloud integrations and security components.

*Popular Models of Fixed Configuration Cisco Catalyst Switches include:*

* **Cisco Catalyst 9200 Series:** Stackable (can operate standalone or with other switches) access switches. Layer 2 and 3 devices.
* **Cisco Catalyst 9300 Series:** Stackable access and distribution switches. Layer 2 and 3 devices.
* **Cisco Catalyst 9500 Series:** Stackable core switches. Layer 2 and 3 devices.
* **Cisco Catalyst 1000 Series:** Stackable access switches. Layer 2 devices.
* **Cisco Catalyst 2960-L Series:** Access switches. Layer 2 and 3 devices.
* **Cisco Catalyst 2960-X/XR Series:** Stackable access switches. Layer 2 and 3 devices.
* **Cisco Catalyst 3560CX/2960CX Series:** Smaller, fanless switches. Layer 2 and 3 devices.
* **Cisco Catalyst Digital Building Series:** Smaller, fanless switches. Layer 2 and 3 devices.
* **Cisco Catalyst 3650 Series:** Stackable switches. Layer 2 and 3 devices.
* **Cisco Catalyst 3850 Series:** Stackable access and distribution switches. Layer 2 and 3 devices.

*Popular Models of Modular Cisco Catalyst Switches include:*

* **Cisco Catalyst 4500 Series:** Mid-level modular switches, including a chassis, line cards, service modules, power supplies, and one or more supervisors.
  + The 4500 series includes the 'E-Series' and 'Classic' chassis (which comes in four sizes: three, six, seven, or ten slots).
* **Cisco Catalyst 6500 Series:** Chassis-based switches supporting devices of up to 40 Gigabit Ethernet (in speed and redundant supervisor modules).
* **Cisco Catalyst 6800 Series:** Chassis-based switches supporting devices of up to 40 Gigabit Ethernet (in speed and redundant supervisor modules).
* **Cisco Catalyst 9400 Series:** Chassis-based access and distribution switches supporting devices of up to 40 Gigabit Ethernet (in speed and redundant supervisor modules, fans, and power supplies).
* **Cisco Catalyst 9600 Series:** Chassis-based core switches supporting devices of up to 100 Gigabit Ethernet (in speed and redundant supervisor modules, fans, and power supplies).

*Popular Models of Cisco Nexus switches include:*

* **Cisco Nexus 1000v Virtual Switches:** Supplies a high-security architectural platform for remote/cloud networks (including multi-tenant deployments) and virtualized servers.
* **Cisco Nexus 2000 Fabric Extenders:** Supplies centralized and highly scalable architecture for data center server access/operations and virtualization. 'Extends' parent Nexus switch fabric and, in the process, creates distributed systems that are also modular in nature.
* **Cisco Nexus 3000 Series:** Specializes in low latency for various deployments (such as data centers and cloud environments).
* **Cisco Nexus 4001 IBM (4001I) Blade Center Switches:** Utilized by BladeCenter H and HT chassis, with Fibre Channel over Ethernet (FCoE) capabilities, low latency, high scalability, and support for high performance server virtualization.
* **Cisco Nexus 5000 Series:** Supplies FCoE switching to simplify data center input/output operations.
* **Cisco Nexus 6000 Series:** Highly dense, compact, energy optimizing, and strongly performing. For virtualized servers, remote/cloud, and other deployments (even if space is constrained).
* **Cisco Nexus 7000 Series Catacenter Switches:** Harmonizes well with Cisco NX-OS features, Software-Defined Networking (SDN) utilities, and Unified Fabric solutions for contemporary data centers.
* **Cisco Nexus 9000 Series:** Versatile, whether for entirely automated data centers or traditional data servers, with compatibility for both NX-OS and Application Centric Infrastructure (ACI). Provides low latency, power optimization, compact form factors, and high density and performance.
  
<hr />

## 4. <a name="supplemental">Supplemental Resources</a>

* *[Official Cisco Adapative Security Appliance (ASA) Webpage](https://www.cisco.com/site/us/en/products/security/firewalls/adaptive-security-appliance-asa-software/index.html)*
* *[Official Cisco ISR (Integrated Services Router) 1000 Series Webpage](https://www.cisco.com/site/us/en/products/networking/sdwan-routers/1000-series-integrated-services-routers-isr/index.html)*
* *[Official Cisco Network Switches Webpage](https://www.cisco.com/site/us/en/products/networking/switches/index.html)*
