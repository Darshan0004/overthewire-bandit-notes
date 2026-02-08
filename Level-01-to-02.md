# Bandit Level 1 → Level 2 — Filenames Starting with Dash

## Objective
Read the password stored in a file named `-`.

---

## Challenge Description
The filename starts with a dash (`-`), which is normally interpreted as a command-line option.

---

## Command Used
``bash
cat ./-


Command Explanation :

- Filenames beginning with - can be mistaken for options
- ./- explicitly references the file in the current directory
- This prevents incorrect option parsing


Concepts Learned :
 
 - Command-line option parsing
 - Handling special filenames
 - Safe file access techniques


Security Takeaway :

 - Improper handling of filenames can break scripts or introduce vulnerabilities.
 - Explicit file referencing is a best practice.


Real-World Relevance :

 - Secure shell scripting
 - Handling attacker-controlled files
 - Linux system enumeration
