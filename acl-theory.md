# Access Control Lists (ACL) Theory

## Overview
ACLs define who can access files, folders, and system resources. Understanding ACLs is essential for Windows security and troubleshooting.

---

## 1. Key Concepts

### ACL
A list of Access Control Entries (ACEs) that define permissions.

### ACE
An individual allow/deny rule for a user or group.

### DACL (Discretionary ACL)
Controls access:
- Allow entries
- Deny entries

### SACL (System ACL)
Controls auditing:
- Success logs
- Failure logs

---

## 2. Viewing ACLs
Get-Acl file.txt

---

## 3. How Windows Evaluates Permissions
- Deny ACEs override allow ACEs  
- ACEs are processed in order  
- Effective permissions = user + group permissions combined  

---

## 4. What I Learned
- How ACLs work internally  
- How Windows decides access  
- How to read and interpret ACEs  
