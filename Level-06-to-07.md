# Bandit Level 6 → Level 7 — Searching by Ownership

## Objective
Find the password stored in a file owned by a specific user and group.

---

## Challenge Description
The target file:
- Is owned by user `bandit7`
- Is owned by group `bandit6`
- Has a size of exactly 33 bytes
- Is located somewhere on the system

---

## Command Used
``bash
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null



Command Explanation :

 - / searches the entire filesystem

 - -type f limits results to regular files

 - -user and -group filter by ownership
 
 - -size 33c filters by exact size

 -2>/dev/null hides permission errors


Concepts Learned :

 - System-wide file enumeration
 - Searching by ownership and size
 - Handling permission-denied errors


Security Takeaway :

 - Effective enumeration relies on filtering, not guessing.
 - Ownership-based searches are powerful in large systems.


Real-World Relevance :

 - Credential hunting
 - System auditing
 - Incident response and forensics
