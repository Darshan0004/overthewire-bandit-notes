# Bandit Level 9 → Level 10 — Extracting Readable Strings

## Objective
Find the password in `data.txt` among many non-human-readable characters.

---

## Command Used
``bash
strings data.txt | grep ==


Command Explanation :

 - strings extracts printable characters from binary files
 - | pipes output to another command
 - grep == filters lines containing the pattern "=="


Concepts Learned :

 - Binary vs text files
 - Extracting readable strings
 - Combining tools with pipes


Security Takeaway :

 - Binary files can still contain readable and sensitive information.
 - Use string extraction tools before dismissing them.


Real-World Relevance :

 - Malware analysis

 - Reverse engineering preparation

 - Investigating suspicious files
