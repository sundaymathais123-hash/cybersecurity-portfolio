# Data Encryption and Decryption Simulation

## Introduction
This project demonstrates how encryption protects sensitive information from unauthorized access. It focuses on encrypting and decrypting files using the Advanced Encryption Standard (AES) with OpenSSL on Kali Linux.

## Tools and Technologies
- Kali Linux
- OpenSSL
- AES-256-CBC encryption
- SHA-256 hashing

## Practical Activities
- Created a sample text file.
- Encrypted the file using AES-256-CBC.
- Decrypted the encrypted file using the correct password.
- Tested decryption with an incorrect password.
- Compared the SHA-256 hashes of the original and decrypted files to verify file integrity.

## Key Findings
- Encryption converted the readable file into unreadable ciphertext.
- The correct password successfully recovered the original content.
- An incorrect password caused decryption to fail.
- Matching SHA-256 hashes confirmed that the decrypted file matched the original file.

## Conclusion
The practical exercise demonstrated how AES encryption helps protect data confidentiality and how SHA-256 hashing can verify file integrity.