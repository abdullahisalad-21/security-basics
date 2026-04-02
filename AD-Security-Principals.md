# Security Concepts from Today’s Session

## 1. Security Principals
- Users, computers, groups, services.
- Identified by SIDs.
- Used in access tokens and ACL evaluation.

## 2. Access Control
- DACLs contain ACEs.
- Access token SIDs are compared to ACEs.
- Permissions are cumulative except explicit deny.

## 3. EFS (Encrypting File System)
- File-level encryption on NTFS.
- Uses FEK encrypted with user’s public key.
- Transparent encryption/decryption.
- Requires recovery agents.
- Only works on NTFS.

## 4. Authentication Security
- Protected Users restrictions.
- Authentication policies and silos.
- NTLM restrictions.
- Kerberos PKInit Freshness.
