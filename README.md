# Investigating the mathematics behind RSA-based encryption attacks in the form of ransomware
# Introduction
In recent years, decreased physical record-keeping has made the safe storage of digital information paramount. Just as physical documentation is at risk of being stolen, it is important to understand that digital data is also vulnerable to theft via cyberattacks. Such attacks exist in many forms, one of which is ransomware – a type of software that locks users out of their computers until a ransom fee is paid. [1] 

While having existed for over a decade, ransomware attacks have grown exponentially in recent years. [2] Security advisors often describe ransomware campaigns as coordinated operations which rely on one basic principle: the ability to lock users out of their computers using effective encryption algorithms such as the one I will be investigating, known as RSA.

The RSA algorithm, developed in 1977 by Ron Rivest, Adi Shamir, and Leonard Adleman, is a public key encryption algorithm in which the public and private keys used to encrypt and decrypt information, are separate. [20] Their separation allows only the party in control of the private key to decrypt said information. [3]

I have always found the mathematics behind number theory interesting and think it is important for people to understand how the relationships between prime numbers allow us to create effective algorithms that secure our information. Knowledge of the systems and effectiveness of encryption allows us to respond appropriately and safeguard ourselves from these kinds of attacks in the future.
