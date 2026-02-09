# Bandit Level 3 → Level 4 — Hidden Files

## Objective
Find the password stored in a hidden file inside a directory.

---

## Challenge Description
The password is stored in a file that is hidden from normal directory listings.

---

## Commands Used

``bash
cd inhere
ls -la
cat .hidden


Command Explanation :

 - cd inhere moves into the target directory
 - ls -la lists all files, including hidden ones
 - cat .hidden reads the hidden file


Concepts Learned :

 - Hidden files in Linux
 - Full directory enumeration
 - Importance of listing all files


Security Takeaway :

 - Hidden files are not secure.
 - Attackers always enumerate directories fully to find sensitive data.


Real-World Relevance :

 - Discovering leaked credentials
 - Enumerating compromised systems
 - Linux privilege escalation preparation
