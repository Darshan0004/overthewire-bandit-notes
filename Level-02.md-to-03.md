# Bandit Level 2 → Level 3 — Filenames with Spaces

## Objective
Read the password stored in a file that contains spaces in its name.

---

## Challenge Description
The filename includes spaces, which causes the shell to split it into multiple arguments if not handled correctly.

---

## Command Used
``bash
cat ./--spaces\ in\ this\ filename--


Command Explanation :

 - Spaces separate arguments in the shell
 - Quoting forces the shell to treat the filename as a single argument
 - Prevents parsing errors


Concepts Learned :

 - Shell argument parsing
 - Handling filenames with spaces
 - Safe command-line practices


Security Takeaway :

 - Unquoted filenames or variables can lead to broken scripts or security issues.
 - Proper quoting is essential in shell scripting.


Real-World Relevance :

 - Secure bash scripting
 - Handling user-generated files
 - Linux file analysis

