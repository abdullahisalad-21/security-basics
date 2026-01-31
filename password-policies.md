# Password Policies (Windows Security)

## Overview
Password policies protect systems from unauthorized access by enforcing strong authentication rules. These settings are essential for IT support and system administration.

---

## 1. Key Policy Settings

### Minimum Password Length
Defines the shortest allowed password to prevent weak credentials.

### Maximum Password Age
Forces users to change passwords regularly to reduce long-term compromise.

### Password Complexity
Requires:
- Uppercase letters
- Lowercase letters
- Numbers
- Special characters

### Account Lockout Policy
Protects against brute-force attacks by locking accounts after repeated failures.

---

## 2. Commands Practiced

### View password policy
net accounts

### Reset password
net user username NewPass123

### Force password change at next login
net user username /logonpasswordchg:yes

---

## 3. What I Learned
- How password policies strengthen security  
- How to enforce password changes  
- How to reset and manage user passwords  
- Why complexity and lockout rules matter  
