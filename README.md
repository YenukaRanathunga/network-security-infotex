# InfoTex Training Solutions – Secure Network Design & Implementation

## 📌 Project Overview
This repository contains the complete **Network Security Design, Configuration, and Evaluation project** developed for **InfoTex Training Solutions**.  
The project demonstrates enterprise-level network security planning, implementation, testing, and critical evaluation using **Cisco Packet Tracer**.

The solution follows **defence-in-depth**, **Zero-Trust**, and **least-privilege** principles to protect organisational systems, users, and data.

---

## 🎯 Objectives
- Design a secure and scalable enterprise network
- Implement layered security controls
- Prevent unauthorised access and lateral movement
- Support legal and compliance requirements (GDPR, PCI-DSS)
- Evaluate effectiveness and propose future improvements

---

## 🏗️ Network Architecture Summary
The network is segmented into multiple security zones using **VLANs** and **ACLs**:

| VLAN | Purpose |
|----|--------|
| VLAN 10 | Training Lab PCs |
| VLAN 20 | Student / Wi-Fi Network |
| VLAN 30 | Business / Admin Department |
| VLAN 50 | DMZ – Public Servers |
| VLAN 60 | Development Network |
| VLAN 70 | Internal Server Zone |

Key architectural features:
- VLAN-based segmentation
- Inter-VLAN routing with ACL enforcement
- Perimeter firewall with NAT
- DMZ isolation for public services
- Secure wireless (WPA2/WPA3)
- SSH-only device management
- Centralised logging & monitoring

---

## 🔐 Security Controls Implemented

### Network Security
- VLAN segmentation
- Internal firewalling using ACLs
- Default-deny security model
- DMZ isolation
- NAT for IP address hiding

### Wireless Security
- WPA2/WPA3 encryption
- VLAN-mapped SSIDs
- Guest and student isolation

### Device Management
- SSH-only remote access
- Local user authentication
- Encrypted credentials

### Monitoring & Governance
- Centralised syslog configuration
- Timestamped logs
- Audit and compliance support

---

## 🧪 Testing & Validation
Security controls were tested using **Cisco Packet Tracer**, including:

- Inter-VLAN ping tests (allowed vs denied)
- DMZ access validation
- Wireless isolation verification
- Management access testing (SSH only)
- Default route and firewall behaviour

Results confirmed:
- Unauthorized access was blocked
- Legitimate business access was preserved
- Lateral movement was prevented

---

## 📊 Evaluation & Review
The solution was critically evaluated across:
- Technical effectiveness
- Strengths and weaknesses
- Legal compliance (GDPR / PCI-DSS)
- Ethical responsibility
- Professional best practices

Future improvements include:
- NGFW with deep packet inspection
- IDS/IPS integration
- SIEM-based log correlation
- MFA for admin access
- High-availability firewalls

---

## 🛠️ Tools & Technologies
- Cisco Packet Tracer
- VLANs & ACLs
- Firewall & NAT
- WPA2 / WPA3
- SSH
- Syslog

---

## 📚 Documentation
This repository includes:
- Secure network design explanation
- Device configuration justification
- Testing evidence
- Critical evaluation (Distinction level)
- Final conclusions and references

---

## 👤 Author
**Yenuka Ranathunga**  
Network Engineering Student  
ESOFT Metro Campus – Sri Lanka  

---

## 📄 License
This project is for **educational and portfolio purposes** only.
