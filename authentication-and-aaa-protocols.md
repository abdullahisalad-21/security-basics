# ⭐ 1. Overview  
Today I expanded my security fundamentals by studying authentication protocols, MFA factors, biometric security, AAA systems, and SSO technologies. I analyzed how confidentiality is protected through strong authentication and how enterprise systems validate identity using Kerberos, RADIUS, TACACS+, and OpenID Connect.

# 🎯 2. Objectives  
- Understand the 5 authentication factors  
- Learn biometric strengths and weaknesses  
- Study physical authentication technologies  
- Compare HOTP vs TOTP  
- Understand AAA protocols (RADIUS, TACACS+)  
- Learn Kerberos ticket‑based authentication  
- Understand SSO and federated identity  

# 🛠️ 3. Tools & Commands Used  
*(Conceptual — no commands executed)*  

### Security Concepts  
- CIA Principle (Confidentiality focus)  
- MFA  
- Biometrics  
- NFC / GPS / IPS  
- AAA protocols  
- SSO protocols  

# 🧩 4. Steps Completed  
## 4.1 Authentication Factors  
- Something you know  
- Something you have  
- Something you are  
- Somewhere you are  
- Something you do  

## 4.2 Biometrics  
- Fingerprint, facial recognition, iris, retina  
- Enrollment vs authentication  
- Spoofing risks  

## 4.3 Physical Authentication  
- NFC (13.56 MHz)  
- GPS geolocation  
- IPS triangulation  
- Geofencing  

## 4.4 HOTP vs TOTP  
- HOTP = counter  
- TOTP = time  
- TOTP more secure  

## 4.5 AAA Protocols  
- RADIUS: network access  
- TACACS+: device admin  
- XTACACS: obsolete  

## 4.6 Kerberos  
- KDC = AS + TGS  
- TGT + Service Tickets  
- Password never sent over network  

## 4.7 SSO  
- Kerberos SSO  
- SAML  
- OAuth2  
- OpenID Connect  

# 🐞 5. Problems & Fixes  
- Clarified biometric security differences  
- Corrected HOTP security misconception  
- Clarified RADIUS encryption limitations  

# 📚 6. What I Learned  
- Authentication is central to confidentiality  
- Biometrics require secure storage and liveness detection  
- RADIUS and TACACS+ solve different problems  
- Kerberos is the backbone of enterprise SSO  
- OIDC is the modern identity layer for the web  

# 📎 7. Related Files  
- This file: `2026-4-15.md`

# 🔜 8. Next Steps  
- Build a lab comparing RADIUS vs TACACS+  
- Create a Kerberos ticket flow diagram  
- Document SAML vs OIDC for portfolio  
