# Bandit Level 10 → Level 11 — Base64 Decoding

## Objective
Decode the Base64-encoded password stored in `data.txt`.

---

## Command Used
``bash
base64 -d data.txt



Command Explanation :

 - base64 is used for encoding and decoding Base64 data
 - -d enables decoding mode
 - The output reveals the original password


Concepts Learned :

 - Encoding vs encryption

 - Base64 format recognition

 - Data transformation in Linux


Security Takeaway :

 - Base64 encoding is not encryption.
 - Encoded data can be easily reversed.


Real-World Relevance :

 - API authentication analysis

 - Configuration file review

 - Investigating encoded credentials
