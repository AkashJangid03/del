Absolutely. Since Q1 already took you 2 pages, I’ll make Q2–Q15 handwriting-efficient: enough content to look like proper M.Sc. answers, but without sentences that waste your time.

I’ll aim for roughly ¾–1½ pages per normal question, and Q7 will be shorter because it contains multiple short notes.


---

Q2. Explain in detail Biometric Authentication

Definition

Biometric authentication is a method of verifying the identity of a person using their unique physical or behavioral characteristics. It is based on the principle of “something you are.”

Types of Biometrics

1. Fingerprint recognition – uses the unique patterns of fingerprints.


2. Face recognition – identifies a person using facial features.


3. Iris recognition – uses the unique pattern of the iris of the eye.


4. Voice recognition – identifies a person from characteristics of their voice.


5. Signature recognition – analyzes a person's signature and writing behavior.


6. Retina recognition – uses the pattern of blood vessels in the retina.



Working of Biometric Authentication

The main steps are:

1. Enrollment:
The user's biometric characteristic is captured for the first time.

2. Feature Extraction:
Important features are extracted from the captured biometric data.

3. Template Creation:
The extracted features are converted into a digital template and stored securely.

4. Authentication:
When the user tries to access the system, their biometric is captured again.

5. Matching:
The new sample is compared with the stored template.

6. Decision:
If the similarity is sufficient, access is granted; otherwise, access is denied.

Advantages

Easy and convenient to use.

No password needs to be remembered.

Difficult to share with another person.

Provides strong user identification.

Useful in banking, smartphones and access-control systems.


Limitations

Biometric information is sensitive.

A compromised biometric cannot easily be changed.

False acceptance or rejection may occur.

Special hardware may be required.


Conclusion

Biometric authentication provides a convenient method of authentication by using the unique characteristics of an individual.


---

Q3. Explain Applications and Drawbacks of Digital Signatures

Definition

A digital signature is a cryptographic technique used to verify the authenticity, integrity and origin of a digital message or document.

It uses a private key for signing and a corresponding public key for verification.

Applications of Digital Signatures

1. E-Governance:
Used for signing government forms, applications and electronic documents.

2. Online Banking:
Used to authenticate and authorize electronic transactions.

3. E-Commerce:
Used for electronic agreements and transactions.

4. Electronic Documents:
Used to sign contracts, reports, certificates and PDF documents.

5. Software Distribution:
Used to verify that software comes from a trusted source and has not been modified.

6. Business Contracts:
Organizations use digital signatures to approve and sign electronic agreements.

Advantages

Provides authentication.

Ensures data integrity.

Provides non-repudiation.

Reduces paperwork.

Saves time and cost.


Drawbacks

1. Private Key Security:
If the private key is stolen, an attacker may create false signatures.

2. Key Management:
Generating, storing and protecting keys can be difficult.

3. Cost:
Certificates and supporting infrastructure may require additional cost.

4. Technical Requirements:
Users require suitable software and infrastructure.

Conclusion

Digital signatures provide a secure way of signing electronic information and are widely used for authentication, integrity and non-repudiation.


---

Q4. Explain the Following Security Attacks

(i) Distributed Denial of Service (DDoS)

A DDoS attack attempts to make a website, server or network unavailable by sending a very large number of requests or packets from many compromised systems.

Working

1. Attacker compromises many devices.


2. These devices form a botnet.


3. The attacker directs them towards the target.


4. Large amounts of traffic are generated.


5. Target resources become overloaded.


6. Legitimate users cannot access the service.



Effects

Website becomes slow or unavailable.

Network resources are exhausted.

Business operations may stop.

Financial losses may occur.



---

(ii) Trojan Horse

A Trojan horse is malicious software that appears to be a legitimate or useful program but performs harmful activities after execution.

Characteristics

Disguises itself as legitimate software.

Requires the user to execute or install it.

Can steal information.

Can install other malware.

Can provide unauthorized access.



---

(iii) Denial of Service (DoS)

A Denial of Service attack attempts to make a computer, server or network service unavailable to legitimate users.

It can overload system resources or network capacity.

Effects

Service becomes unavailable.

Network traffic increases.

Server resources are exhausted.

Legitimate users are denied access.


Difference: A traditional DoS attack generally comes from one source, while a DDoS attack uses multiple sources.


---

(iv) Man-in-the-Middle (MitM) Attack

A Man-in-the-Middle attack occurs when an attacker secretly places themselves between two communicating parties.

User → Attacker → Server

The attacker may intercept or modify the communication without the users realizing it.

Prevention

Use HTTPS/TLS.

Verify digital certificates.

Use strong authentication.

Avoid untrusted networks.

Use secure communication protocols.



---

Q5. Explain the Steps of RSA Algorithm

Definition

RSA (Rivest-Shamir-Adleman) is an asymmetric-key cryptographic algorithm. It uses a public key and a private key.

Steps of RSA

Step 1: Select two prime numbers

Let:

p = 3, q = 11

Step 2: Calculate n

\[
n=p\times q
\]

\[
n=3\times11=33
\]

Step 3: Calculate Euler's Totient

\[
\phi(n)=(p-1)(q-1)
\]

\[
\phi(33)=2\times10=20
\]

Step 4: Select public key e

Choose e such that it is relatively prime to φ(n).

Let:

e = 3

Step 5: Calculate private key d

Find d such that:

\[
e\times d\equiv1\pmod{\phi(n)}
\]

Here:

\[
3\times7=21\equiv1\pmod{20}
\]

Therefore:

d = 7

Keys

Public Key = (e,n) = (3,33)

Private Key = (d,n) = (7,33)

Encryption

For plaintext M:

\[
C=M^e\mod n
\]

If M = 4:

\[
C=4^3\mod33=31
\]

Therefore ciphertext = 31.

Decryption

\[
M=C^d\mod n
\]

\[
M=31^7\mod33=4
\]

Thus, the original message 4 is obtained.

Conclusion

RSA provides secure communication using a public/private key pair and is based on mathematical properties of prime numbers.


---

Q6. Elaborate on Use of Smart Cards and Passwords for Authentication

Smart Cards

A smart card is a physical card containing an embedded chip that can store information and perform certain cryptographic operations.

Uses

Banking cards.

Identification cards.

Access-control systems.

SIM cards.

Government identification.


Authentication Using Smart Cards

1. User inserts or taps the smart card.


2. The card provides authentication information.


3. The system verifies the information.


4. If verification is successful, access is granted.



A smart card can also be combined with a PIN for stronger security.

Advantages

Portable.

Secure storage of credentials.

Difficult to duplicate when properly protected.

Can support cryptographic operations.



---

Password Authentication

A password is a secret value known by the user and used to prove their identity.

Working

1. User enters username and password.


2. System receives the credentials.


3. System verifies them against stored authentication information.


4. If correct, access is granted.



Advantages

Simple to use.

Cheap to implement.

No special hardware required.


Disadvantages

Passwords can be guessed.

Can be stolen through phishing.

Users may reuse passwords.

Weak passwords provide poor security.


Conclusion

Passwords are simple and widely used, while smart cards provide stronger hardware-based authentication.


---

Q7. Write Short Notes

(a) Digital Certificates

A digital certificate is an electronic document that connects a public key with the identity of an individual, organization or server.

It is normally issued by a trusted Certificate Authority (CA).

It contains information such as:

Owner's identity.

Public key.

Issuer.

Validity period.

CA's digital signature.



---

(b) Packet Filtering Firewalls

A packet filtering firewall examines network packets and allows or blocks them according to predefined rules.

It can check:

Source IP address.

Destination IP address.

Port number.

Protocol.

Direction of traffic.


It is simple and fast but provides limited understanding of application-level traffic.


---

(c) Requirements of a Message Digest

A secure message digest should:

1. Produce a fixed-length output.


2. Be easy to calculate.


3. Be difficult to reverse.


4. Provide preimage resistance.


5. Provide collision resistance.


6. Show a large change in output when input changes slightly.




---

(d) Demilitarized Zone (DMZ)

A DMZ is a separate network placed between the Internet and an organization's internal network.

Public-facing servers such as web, mail and DNS servers can be placed in the DMZ.

It provides an additional security boundary and helps protect the internal network.


---

(e) Applications of Digital Certificates

Digital certificates are used for:

HTTPS websites.

Secure email.

Server authentication.

User authentication.

Digital signatures.

Secure online transactions.



---

(f) Features of AES

AES (Advanced Encryption Standard) is a symmetric block cipher.

Important features:

Block size: 128 bits

Key sizes: 128, 192 and 256 bits

Strong security.

Fast implementation.

Suitable for software and hardware.

Widely used in modern security systems.



---

(g) Ransomware

Ransomware is malware that prevents users from accessing their data, commonly by encrypting files, and demands payment from the victim.

Prevention

Keep regular backups.

Update software.

Avoid suspicious links and attachments.

Use security software.

Apply strong access controls.



---

Q8. Describe Requirements of a Message Digest

A message digest is a fixed-size value generated from a message using a cryptographic hash function. It is mainly used to verify data integrity.

The important requirements are:

1. Fixed-Length Output

A message of any size should produce a digest of a fixed size.

2. Easy to Compute

The digest should be calculated quickly and efficiently.

3. One-Way Property

It should be computationally difficult to obtain the original message from the digest.

4. Preimage Resistance

It should be difficult to find an input that produces a particular digest.

5. Collision Resistance

It should be difficult to find two different messages having the same digest.

6. Avalanche Effect

A small change in the input should produce a significantly different digest.

Conclusion

These properties make message digests useful for detecting unauthorized modification of data.


---

Q9. Differentiate Between MD5 and SHA

Feature	MD5	SHA

Full form	Message Digest 5	Secure Hash Algorithm
Output	128 bits	Depends on SHA version
Security	Insecure for cryptographic use	Modern versions provide stronger security
Collision resistance	Weak	Stronger in modern versions
Current use	Not recommended for security	SHA-2 and SHA-3 are widely used
Type	Hash algorithm	Family of hash algorithms


MD5

MD5 produces a 128-bit hash value. It was widely used earlier, but collision attacks have made it unsuitable for security-sensitive applications.

SHA

SHA is a family of cryptographic hash algorithms. Examples include SHA-1, SHA-256, SHA-512 and SHA-3.

Modern applications generally use SHA-2 or SHA-3.

Conclusion

MD5 is considered obsolete for cryptographic security, while modern SHA variants provide much stronger security.


---

Q10. What is a Substitution Cipher?

Definition

A substitution cipher is an encryption technique in which each plaintext character is replaced by another character according to a predefined rule.

Example: Caesar Cipher

If the shift is 3:

A → D
B → E
C → F

Therefore:

HELLO → KHOOR

Types

1. Caesar cipher.


2. Monoalphabetic substitution cipher.


3. Polyalphabetic substitution cipher.


4. Homophonic substitution cipher.



Advantages

Simple to understand.

Easy to implement.

Useful for learning basic cryptography.


Disadvantage

Simple substitution ciphers can be attacked using frequency analysis because the statistical properties of the language remain.

Conclusion

A substitution cipher replaces plaintext symbols with other symbols according to a fixed or changing substitution rule.


---

Q11. Compare Symmetric and Asymmetric Key Cryptography

Feature	Symmetric	Asymmetric

Keys	One shared secret key	Public and private key
Speed	Faster	Slower
Key distribution	Difficult	Easier
Examples	AES, DES	RSA, ECC
Main use	Data encryption	Key exchange, authentication, signatures
Computation	Lower	Higher


Symmetric Cryptography

In symmetric cryptography, the same secret key is used for encryption and decryption.

Plaintext → Encryption + Secret Key → Ciphertext

The receiver must possess the same secret key.

Asymmetric Cryptography

Asymmetric cryptography uses two related keys:

Public key

Private key


The public key can be shared, while the private key must remain secret.

Conclusion

Symmetric cryptography is faster and suitable for large amounts of data. Asymmetric cryptography is useful for authentication, digital signatures and secure key exchange.


---

Q12. Describe Asymmetric Key Cryptography with an Example

Definition

Asymmetric key cryptography, also called public-key cryptography, uses a pair of mathematically related keys:

1. Public key


2. Private key



The public key can be openly distributed, while the private key must be kept secret.

Working Example

Suppose Alice wants to send a confidential message to Bob.

1. Bob generates a public and private key pair.


2. Bob gives his public key to Alice.


3. Alice encrypts the message using Bob's public key.


4. Alice sends the encrypted message to Bob.


5. Bob uses his private key to decrypt it.



The process is:

Message → Bob's Public Key → Ciphertext → Bob's Private Key → Message

Example: RSA

RSA is a well-known asymmetric cryptographic algorithm.

It generates:

Public Key = (e,n)

Private Key = (d,n)

Advantages

Solves the key-distribution problem.

Supports digital signatures.

Provides authentication.

Public key can be shared openly.


Disadvantage

Asymmetric algorithms are slower than symmetric algorithms.

Conclusion

Asymmetric cryptography is mainly used for secure key exchange, authentication and digital signatures.


---

Q13. Define Steganography. What are its Types? Explain Image Steganography.

Definition

Steganography is the technique of hiding secret information inside another ordinary-looking medium so that the existence of the secret information is concealed.

The original medium is called the cover medium.

Types of Steganography

1. Image steganography


2. Audio steganography


3. Video steganography


4. Text steganography


5. Network steganography



Image Steganography

In image steganography, secret information is hidden inside an image.

One common technique is Least Significant Bit (LSB) substitution.

For example:

10110010

The last bit is the least significant bit:

1011001[0]

This bit can be changed to store secret information while producing only a small change in the pixel value.

Working

Cover Image + Secret Data → Stego Image

The receiver can extract the hidden information:

Stego Image → Extraction → Secret Data

Advantages

Secret information is hidden inside an ordinary image.

The image may look normal to the human eye.

Useful for information hiding.


Disadvantages

Hidden information can be detected using steganalysis.

Image compression or modification may damage hidden data.

Excessive hidden data can affect image quality.


Steganography vs Cryptography

Cryptography: Hides the meaning of the message.

Steganography: Hides the existence of the message.


---

Q14. Differentiate Between AES and DES

Feature	AES	DES

Full form	Advanced Encryption Standard	Data Encryption Standard
Block size	128 bits	64 bits
Key size	128, 192, 256 bits	56 effective bits
Security	Strong	Weak/obsolete
Structure	Substitution-permutation network	Feistel structure
Status	Widely used	Obsolete
Resistance	Strong against modern attacks when properly used	Vulnerable to brute-force attacks


AES

AES is a modern symmetric block cipher. It supports key sizes of 128, 192 and 256 bits and uses a 128-bit block size.

It provides strong security and efficient implementation.

DES

DES is an older symmetric encryption algorithm with a 64-bit block size and an effective key size of 56 bits.

Its small key size makes it vulnerable to brute-force attacks using modern computing power.

Conclusion

AES is much stronger and more suitable for modern security applications, while DES is considered obsolete for protecting sensitive data.


---

Q15. Describe Single-Factor, Two-Factor and Multi-Factor Authentication

Authentication

Authentication is the process of verifying the identity of a user before allowing access to a system.

Common authentication factors are:

Something you know: Password, PIN.

Something you have: Phone, smart card, security token.

Something you are: Fingerprint, face, iris.


1. Single-Factor Authentication

Single-factor authentication uses only one authentication factor.

Example:

Username + Password

Here, the password is the only authentication factor.

Advantage

Simple and easy to implement.


Disadvantage

If the password is stolen, an attacker may gain access.


---

2. Two-Factor Authentication (2FA)

Two-factor authentication uses two different authentication factors.

Example:

Password + OTP

Here:

Password = Something you know.

OTP/phone = Something you have.


Even if the password is compromised, the attacker may still require the second factor.


---

3. Multi-Factor Authentication (MFA)

Multi-factor authentication uses two or more independent authentication factors.

Example:

Password + OTP + Fingerprint

This combines:

Something you know + Something you have + Something you are

Advantages

Provides stronger security.

Reduces dependence on passwords.

Protects accounts if one factor is compromised.


Comparison

Type	Factors	Example

Single-factor	1	Password
Two-factor	2	Password + OTP
Multi-factor	2 or more	Password + OTP + Fingerprint


Conclusion

Single-factor authentication is simple but less secure. Two-factor and multi-factor authentication provide stronger protection by requiring multiple authentication factors.


---

📌 Your writing target

Now that we've compressed these, don't force them to fill a fixed number of pages. Write them naturally with the headings and tables.

A reasonable target for your notebook is:

Q2: ~1–1.25 pages

Q3: ~1–1.25 pages

Q4: ~1.5 pages

Q5: ~1.25–1.5 pages

Q6: ~1–1.25 pages

Q7: ~1.5–2 pages total

Q8: ~¾–1 page

Q9: ~¾–1 page

Q10: ~¾ page

Q11: ~¾–1 page

Q12: ~1 page

Q13: ~1–1.25 pages

Q14: ~¾–1 page

Q15: ~1 page


Since Q1 is already 2 pages, your complete assignment should come out to roughly 17–20 handwritten pages, depending heavily on your handwriting and spacing.

Most important: don't waste time writing every sentence as a paragraph. Use the bold headings, numbered points, tables, formulas, and short explanations exactly as above. That gives you the best balance between marks + presentation + writing time.
