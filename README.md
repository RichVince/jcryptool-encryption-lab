# JCrypTool Lab: Classic and Modern Encryption Algorithms

## Goal
Explore and compare classic and modern encryption methods using JCrypTool, including a Caesar cipher, AES symmetric encryption, and RSA asymmetric encryption.

## Tools Used
- CSE-LABVM
- JCrypTool

## What I Did
- Opened JCrypTool in the lab VM
- Used a Caesar cipher to encrypt a plaintext message with a character-based key
- Decrypted the Caesar ciphertext using the same settings
- Repeated the Caesar activity with a different alphabet setting and shift value
- Used AES to encrypt a text message with a 128-bit custom key
- Decrypted the AES ciphertext using the same symmetric key
- Used RSA to create a new key pair in the keystore
- Encrypted a text message with RSA
- Decrypted the RSA ciphertext using the associated private key and password

## Algorithms Covered

### Caesar Cipher
Used a classic substitution cipher to shift characters in a message and then reverse the process through decryption.

### AES
Used AES as a modern symmetric encryption algorithm with a 128-bit custom key. The same key was required for both encryption and decryption.

### RSA
Used RSA as a modern asymmetric encryption algorithm. A public/private key pair was generated, and the encrypted message was later decrypted with the matching private key and password.

## What I Observed
The Caesar cipher demonstrated how simple substitution-based encryption works, but also showed why classic algorithms are weak compared to modern cryptography.

AES showed how modern symmetric encryption protects data using a shared key. The encrypted output appeared in binary or hexadecimal form and required the exact same key settings for decryption.

RSA demonstrated the difference between symmetric and asymmetric encryption. Instead of one shared key, RSA used a public/private key pair, which is a foundational concept in secure communication and public key infrastructure.

## Why It Matters
This lab helped reinforce several important cybersecurity concepts:

- Classic ciphers are useful for understanding the history of encryption, but they are not secure for modern use
- AES is a strong modern symmetric encryption algorithm used widely to protect sensitive data
- RSA demonstrates how asymmetric encryption works with separate public and private keys
- Understanding the difference between symmetric and asymmetric encryption is essential for security fundamentals, secure communication, and key management

For SOC and cybersecurity work, this matters because analysts need to understand:

- how sensitive data is protected
- the role of encryption in secure systems
- the difference between weak legacy methods and strong modern cryptography
- how encryption concepts connect to authentication, confidentiality, and secure communications

## Key Takeaway
This lab provided hands-on exposure to both classic and modern cryptographic methods and reinforced the practical differences between substitution ciphers, symmetric encryption, and asymmetric encryption.
