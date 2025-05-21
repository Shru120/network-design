🔐 Secure Network Architecture Design

This project demonstrates a multi-layered, defense-in-depth network architecture designed for a financial institution, with a strong focus on segmentation, detection, and regulatory compliance.

📄 [Download Full PDF Summary)

---

🔰 Key Components Overview

🔹 NGFW (Frontend Firewall)
- Deep packet inspection, malware filtering, VPN support.
- First line of defense protecting the DMZ and internal systems.

🔹 DMZ Zone
- Hosts public-facing services like web and mail servers.
- Isolates external traffic from the core network.

🔹 Backend Firewall
- Additional control layer between DMZ and internal network.

🔹 WAF (Web Application Firewall)
- Protects against SQLi, XSS, and DDoS attacks on hosted services.

🔹 NIDS/NIPS
- NIDS alerts unusual traffic; NIPS actively blocks threats.

🔹 VLAN Segmentation
- Restricts attacker movement inside the LAN.
- Logical separation between departments.

🔹 MFA & Encryption
- MFA defends against phishing and stolen credentials.
- Encryption prevents MITM attacks and secures data in transit.

---

🎓 Project Context

Originally developed during my MSc Cybersecurity program, this network design reflects real-world considerations and best practices in enterprise architecture. It's intended to highlight my practical understanding of security layers, design thinking, and compliance needs.

---
