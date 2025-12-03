FortiGate–Active Directory Integration Using FSSO

This project demonstrates the integration of FortiGate 300D firewalls with Windows Server 2016 Active Directory using Fortinet Single Sign-On (FSSO).
The setup includes VLAN segmentation, VDOM separation, HA configuration, user authentication, and firewall policy enforcement.

🔧 Project Components

2× FortiGate 300D (HA Pair)

Windows Server 2016 (AD DS + DNS + FSSO Agent)

User PC (Domain joined)

Managed Switch for VLANs

Trunk links between switch and firewalls

🛠️ Key Configurations
Firewall:

VDOM creation and interface allocation

VLAN interfaces for trunking

DHCP services for VLANs

HA (Active–Passive) setup

User-based firewall policies

FSSO connector (Security Fabric → External Connectors)

Windows Server:

AD DS installation and domain creation

DNS configuration

FSSO Collector Agent installation

AD user creation and authentication testing

✅ Features

Real-time user identification via FSSO

Policy enforcement based on AD groups

Segmented network using VLANs

HA redundancy testing

Ping, connectivity, and authentication validation

📂 Repository Includes

Full project documentation

Configuration notes

Screenshots (add yours here)

Troubleshooting steps
