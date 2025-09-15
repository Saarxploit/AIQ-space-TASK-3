# AIQ-space-TASK-3
A multi-level access home cloud architecture 
🏠 Personal Home Cloud with Secure Multi-Level Access


📌 Overview


This project is a secure home-based cloud system that provides role-based, multi-level access to personal and family data. It enables different users (self, parents, siblings, guests) to access customized storage and services with strict security controls. The system is internet-exposed with VPN + HTTPS, allowing safe remote access from anywhere in the world.



⚙️ Features
🔐 Role-Based Access Control (RBAC):

Different users (admin, family, guests) get specific permissions to their data.

🖥️ Home Cloud Server:

Centralized storage with segmented access for individuals and groups.

👨‍👩‍👧‍👦 Guest Access Portal:

Temporary, restricted access for visiting relatives and friends.

🛡️ Network Security:

Checkpoint Firewall for intrusion prevention.

VPN access for secure remote login.

Device authentication for trusted access.

📡 Remote Accessibility:

Secure worldwide access using VPN + HTTPS.

🔎 Monitoring & Alerts:

NIDS (Network Intrusion Detection System) for suspicious activity.

Admin dashboard for real-time logs and alarms.

🗄️ Secure Storage:

Encrypted vault for files.

Strict retrieval controls to prevent misuse.



🖼️ Architecture
Components:
Family LAN → PCs for family members.

Home Cloud → Central storage server.

AD Server → Authentication & role management.

Admin PC → Controls cloud + firewall policies.

NIDS → Network monitoring and alarms.

Checkpoint Firewall → Security enforcement.

Router ISP → Internet access with VPN support.

Clients (Admin VPN, Guest VPN, Internet Users) → Secure external users.



🚀 How It Works
User connects → via LAN or remote VPN.

Authentication → Verified through AD server & RBAC.

Access granted → Based on role (Admin, Family, Guest).

Data transfer → Secured using HTTPS & encryption.

Monitoring → NIDS + Firewall watch for anomalies.

Admin control → Central panel manages policies & sessions.

VLAN - using VLAN we can segregate admin pc from family LAN 



🔧 Future Improvements
Multi-factor authentication (MFA).

Integration with cloud backup (AWS, Azure).

AI-driven anomaly detection.

Mobile app for cloud access.
