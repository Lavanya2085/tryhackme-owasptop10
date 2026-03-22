1. Sensitive Data Exposure

Sensitive data includes:

Passwords
API keys
Authentication tokens
Credit card details
Personal information (PII)

If this data is stored or transmitted without protection, attackers can intercept or retrieve it.

2. Insecure Data Storage

Applications sometimes store sensitive information improperly.

Examples:

Plaintext passwords in databases
API keys inside source code
Sensitive files publicly accessible

Example (Insecure):

password = "admin123"

Example (Secure):

hashed_password = bcrypt.hash(password)
# tryhackme-owasptop10
This repository documents my learning and practical exercises from the "OWASP Top 10 – Insecure Data Handling" room on TryHackMe. The room focuses on how sensitive data can be exposed due to improper storage, transmission, or handling by applications. 
