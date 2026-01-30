openssl version
openssl enc -aes-256-cbc -salt -in message.txt -out message.enc
openssl enc -aes-256-cbc -d -in message.enc -out decrypted.txt
openssl genrsa -out private.key 2048
openssl rsa -in private.key -pubout -out public.key
openssl dgst -sha256 message.txt these are commands 
# cyber-task-6-cryptography
README.md message.txt message.enc decrypted.txt screenshots/
# Task 6: Introduction to Cryptography

## Tool Used
- OpenSSL
- OS: macOS

## Experiments Performed
- Symmetric encryption using AES
- Asymmetric encryption using RSA
- Digital signature creation and verification
- Hashing using SHA-256

## Observations
- AES is fast and uses same key
- RSA uses public/private keys
- Hash ensures file integrity
- Digital signature verifies authenticity

## Real-World Applications
- HTTPS
- VPN
- Secure file transfer

## Outcome
- Understood cryptography basics
- Hands-on experience with OpenSSL
