---
title: "Public Key Encryption Overview"
description: "Explanation of public key encryption and its role in FenixPyre's security model (under 160 characters)."
slug: /02-core-concepts/public-key-encryption
keywords: [fenixpyre, encryption, public-key, security]
last_updated: 2023-10-01
---

Why it matters: Public key encryption enables secure data exchange in FenixPyre, ensuring that only authorized users can decrypt sensitive information.

## What is Public Key Encryption?
Public key encryption, or asymmetric encryption, uses a pair of keys: a public key for encrypting data and a private key for decrypting it.

- The public key can be shared openly.
- The private key must remain secure.

Examples of algorithms include RSA, DSA, and ECC (Elliptic Curve Cryptography).

> **Note:** This method is crucial for secure internet communications, allowing encrypted messages without prior key exchange.

## How FenixPyre Uses It
In FenixPyre, public key encryption supports key management and secure sharing.

## Next Steps / Related Topics
Dive deeper into [Key Management](/02-core-concepts/key-mgmt) or explore [Encryption Model](/02-core-concepts/encryption-model).