[[Preguntas Falladas]]
1. A system administrator is configuring a site-to-site VPN tunnel. Which of the following should be configured on the VPN concentrator during the IKE phase?
* A. RIPEMD
* B. ECDHE
* C. **Diffie-Hellman**
* D. HTTPS

Internet Key Exchange (IKE) Internet Key Exchange (IKE) is the protocol used to set up a secure, authenticated communications channel between two parties. ... In phase 1, IKE creates an authenticated, secure channel between the two IKE peers. This is done using the Diffie-Hellman key agreement protocol.

2. A security team wants to establish an Incident Response plan. The team has never experienced an incident.
Which of the following would BEST help them establish plans and procedures?
* A. **Table top exercises**
* B. Lessons learned
* C. Escalation procedures
* D. Recovery procedures

Tabletop exercises are discussion-based sessions where team members meet in an informal, classroom setting to discuss their roles during an emergency and their responses to a particular emergency situation. A facilitator guides participants through a discussion of one or more scenarios.


3. An auditor has identified an access control system that can incorrectly accept an access attempt from an unauthorized user. Which of the following authentication systems has the auditor reviewed?

* A. Password-based
* **B. Biometric-based**
* C. Location-based
* D. Certificate-based

Biometrics can be very exact when the technology is implemented accurately. However, there can be cases where the system incorrectly accepts access attempts from unauthorized users, such as when a fingerprint reader fails to recognize a legitimate user's fingerprint due to variations in finger placement or quality of the scan. This is a known limitation of biometric authentication systems.

4. The chief security officer (CSO) has issued a new policy that requires that all internal websites be configured for HTTPS traffic only. The network administrator has been tasked to update all internal sites without incurring additional costs. Which of the following is the best solution for the network administrator to secure each internal website?
Respuesta
* **Use certificates signed by the company CA**
* Use a signing certificate as a wild card certificate
* Use certificates signed by a public CA
* Use a self-signed certificate on each internal server

While using certificates signed by the company's own Certificate Authority (CA) or using a wildcard certificate signed by a public CA are valid options for securing internal websites, they typically involve additional costs and administrative overhead. Self-signed certificates, on the other hand, do not incur any additional costs, and they can provide secure encryption for internal websites.

However, it's important to note that self-signed certificates have some limitations, such as not being automatically trusted by web browsers without manual user acceptance. Users may see security warnings when accessing websites with self-signed certificates, but if the organization's internal users are aware of and trust these certificates, they can proceed to use them securely.

5. An administrator intends to configure an IPSec solution that provides ESP with integrity protection, but not confidentiality protection.
Which of the following AES modes of operation would meet this integrity-only requirement?
* **A. HMAC**
* B. PCBC
* C. CBC
* D. GCM
* E. CFB

6. Which of the following are used to increase the computing time it takes to brute force a password using an offline attack? (Select TWO)
A. XOR
B. PBKDF2
C. bcrypt
D. HMAC
E. RIPEMD
PBKDF2 (Password-Based Key Derivation Function) is a key stretching algorithm. It can be used to hash passwords in a computationally intensive manner, so that dictionary and brute-force attacks are less effective.

bcrypt is designed to be slow and not to allow any shortcut. It takes more effort to brute force attack the password. The slower the algorithm, the less guesses can be made per second.

7. An organization is expanding its network team. Currently, it has local accounts on all network devices, but with growth, it wants to move to centrally managed authentication. Which of the following are the BEST solutions for the organization? (Select TWO)
   * TACACS+
   * CHAP
   * LDAP
   * RADIUS
   * MSCHAPv2

Either RADIUS or TACACS+ for centrally managed authentication, authorization, and accounting (AAA).

8, An attacker captures the encrypted communication between two parties for a week, but is unable to decrypt the messages. The attacker then compromises the session key during one exchange and successfully compromises a single message. The attacker plans to use this key to decrypt previously captured and future communications, but is unable to.
This is because the encryption scheme in use adheres to:
  * Asymmetric encryption
  * Out-of-band key exchange
  * Perfect forward secrecy
  * Secure key escrow

Perfect forward secrecy The term used to describe a system that generates
random public keys (ephemeral key) for each session so that secret key exchange can
occur during the communication.
