# Bandit Level 11 → Level 12 — ROT13 Decoding

## Objective
Decode the ROT13-encoded password stored in `data.txt`.

---

## Command Used
``bash
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'



Command Explanation :

 - cat data.txt outputs file content

 - tr translates characters

 - ROT13 shifts each letter by 13 positions

 - Applying ROT13 again reveals the original text



Concepts Learned :

 - Substitution ciphers

 - ROT13 encoding

 - Character translation in Linux



Security Takeaway :

 - Basic obfuscation techniques are easily reversible.
 - Encoding is not equivalent to encryption.


Real-World Relevance :

 - Analyzing obfuscated scripts

 - Decoding suspicious log entries

 - CTF cryptography challenges
