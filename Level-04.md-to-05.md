# Bandit Level 4 → Level 5 — Identifying Human-Readable Files

## Objective
Find the password stored in the only human-readable file among multiple files.

---

## Challenge Description
The directory contains several files, but only one contains readable text.

---

## Commands Used
``bash
cd inhere
file ./*
cat ./-file07


Command Explanation :

 - file ./* determines the type of each file
 - ASCII text indicates human-readable content
 - cat is used to read the identified file


Concepts Learned :

 - File type identification
 - Difference between text and binary files
 - Efficient file enumeration


Security Takeaway :

 - Always identify file types before reading them.
 - This prevents errors and focuses attention on meaningful data.


Real-World Relevance :

 - Configuration file discovery
 - Malware and binary analysis preparation
 - Linux system enumeration
