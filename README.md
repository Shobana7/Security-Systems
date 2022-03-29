Authentication Security

User authentication is a significant prerequisite for secure transactions and
access to vital information. The user authentication methods fall into three broad categories:

➔ Something the user is (voice recognition, retinal scanners etc)

➔ Something the user has (IDs, smartcards)

➔ Something the user knows (passwords, PINs)

The existing methods make use of cryptographic primitives: encryption, key management and digital signatures individually or in combination. They provide some level of protection but over time, their vulnerabilities have been exploited bringing on serious consequences.

Password-based authentication is frequently the only available method to prove identity to a third party. Communicating the password to a third-party, either in direct or hashed form, increases its risk of exposure to an adversary. Also the insecure wireless networks create threats for both user and the verifier. So, passwords are best protected when they are never revealed.

My line of research will deal with Zero Knowledge Proofs in authentication. “Such an authentication approach is considered to be the most secure way of proving identity”. The user proves that he/she knows the secret without revealing what the secret is. In authentication, the ZKP will be used by the user to prove that he knows the password without sending over the actual password. No password hashes have to be stored on the server.

(Research paper as part of the coursework)
