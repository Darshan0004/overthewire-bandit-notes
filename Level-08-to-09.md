# Bandit Level 8 → Level 9 — Finding Unique Lines

## Objective
Find the password in `data.txt` that appears only once.

---

## Command Used
``bash
sort data.txt | uniq -u


 
Command Explanation :

 - sort arranges lines alphabetically
 - | pipes output to another command
 - uniq -u prints lines that occur only once
 - Sorting is required before using uniq


Concepts Learned :

 - Data sorting
 - Removing duplicates
 - Using pipes for command chaining


Security Takeaway :

 - Filtering and analyzing large datasets is crucial for identifying anomalies.


Real-World Relevance :

 - Log analysis
 - Detecting rare attack patterns
 - Security monitoring and investigation
