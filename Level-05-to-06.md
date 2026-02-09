# Bandit Level 5 → Level 6 — Searching by File Attributes

## Objective
Find the password stored in a file that matches specific conditions.

---

## Challenge Description
The target file is:
- Human-readable
- Exactly 1033 bytes
- Not executable

---

## Command Used
``bash
find inhere -type f -size 1033c ! -executable



Command Explanation :

 - find searches files recursively
 - -type f limits results to regular files
 - -size 1033c filters by exact file size
 - ! -executable excludes executable files


Concepts Learned :

 - File enumeration using attributes
 - Efficient searching with find
 - Avoiding manual inspection


Security Takeaway :

 - Precise searching is essential during enumeration
 - Filtering by attributes reveals sensitive files quickly.


Real-World Relevance :

 - Credential discovery
 - System auditing
 - Incident response investigations
