# ⭐ Overview
In this session, I deepened my understanding of cryptographic hashing, PKI, certificates, VPN protocols, and real‑world security vulnerabilities. This material is part of Module 2 of my Google IT Support Security course.

# 🎯 Objectives
- Learn how hash functions behave and why they are used  
- Compare SHA‑1 and MD5  
- Understand X.509 certificates and RFC 5280  
- Study PGP’s origins and purpose  
- Compare L2TP/IPsec vs OpenVPN  
- Analyze a real‑world TPM/BitLocker attack  

# 🛠️ Tools & Commands Used
- `md5sum`  
- `sha1sum`  
- RFC 5280 (X.509)  
- RFC 3193 (L2TP/IPsec)  
- PGP documentation  
- Security analysis resources  

# 🧩 Steps Completed
- Reviewed hashing properties: determinism, avalanche effect, collision resistance  
- Compared MD5 vs SHA‑1 and why both are insecure  
- Studied X.509 certificate structure: subject, issuer, SAN, key usage, extensions  
- Read Phil Zimmermann’s essay explaining why he created PGP  
- Compared VPN technologies: L2TP/IPsec vs OpenVPN  
- Analyzed a TPM bus‑sniffing attack that bypassed BitLocker  

# 🐞 Problems & Fixes
No technical errors, but I clarified conceptual differences between hashing, encryption, and tunneling.

# 📚 What I Learned
- Hash functions are one‑way and sensitive to tiny input changes  
- MD5 and SHA‑1 are vulnerable to collisions  
- X.509 certificates rely on trust chains, extensions, and revocation  
- PGP was created to protect privacy and resist surveillance  
- L2TP needs IPsec for encryption; OpenVPN uses TLS and is more flexible  
- Physical access can undermine cryptographic protections  

# 📎 Related Files
- 2026-4-12.md (Daily Practice repo)

# 🔜 Next Steps
- Complete Module 2 challenge  
- Begin Module 3 (AAA)  
- Practice certificate validation and VPN configuration scenarios  
