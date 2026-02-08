# Bandit Level 0 → Level 1 — Reading Files

## Objective
Find the password for the next level stored in the `readme` file.

---

## Commands Used
``bash
ls
cat readme

---------------------------------------------------------------------------------------------------------

Command Explanation

ls lists files in the current directory

cat readme prints the contents of the file to the terminal

Concepts Learned

Basic file enumeration

Reading file contents

Locating stored credentials

Security Takeaway

Storing passwords in readable files is dangerous.
If an attacker gains access, secrets can be exposed instantly.

Real-World Relevance

Configuration file analysis

Credential leaks on servers

Initial enumeration during penetration testing
