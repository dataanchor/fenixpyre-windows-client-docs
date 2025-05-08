
## Why it matters
Symmetrical key encryption enables efficient and secure data encryption, forming a core part of FenixPyre's protection against unauthorized access.

Symmetrical key encryption, also known as secret key encryption, uses the same key for both encrypting and decrypting data. This shared secret key must be securely managed.

- It is faster and more efficient than asymmetrical methods but requires secure key transmission.
- Examples include AES, DES, and Blowfish, which FenixPyre leverages for performance.

### Example Code Snippet
```python
# Sample AES encryption in Python
import cryptography
key = b'16-byte secret key!'
# Encrypt data here
```
# Expected output: Encrypted byte string

### Next Steps / Related Topics
Learn more in [Key Management](/02-core-concepts/key-mgmt.md) or [Encryption Model](/02-core-concepts/encryption-model.md).
