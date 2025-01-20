# Vigenere Cipher - Text Encryption and Decryption

This repository contains a Python implementation of the **Vigenere Cipher**, a classic encryption technique that uses a keyword to encrypt and decrypt text.

## 🔑 Features:
- **Encrypt Text**: Securely encrypt messages using a custom key.
- **Decrypt Text**: Decode encrypted messages back to the original text.
- Handles both alphabetic and non-alphabetic characters, preserving non-letters in the output.

## 🚀 How It Works:
1. **Vigenere Cipher Logic**:
   - Uses a custom key to shift letters in the message based on their position in the alphabet.
   - Non-alphabetic characters are not modified.
   - Supports encryption and decryption using the same key.

2. **Key Functions**:
   - `encrypt(message, key)`: Encrypts the message.
   - `decrypt(message, key)`: Decrypts the encrypted text back to its original form.

## 🛠️ Example:
```python
text = 'mrttaqrhknsw ih puggrur'
custom_key = 'happycoding'

# Encrypt
encrypted_text = encrypt(text, custom_key)
print(f'Encrypted Text: {encrypted_text}')

# Decrypt
decrypted_text = decrypt(encrypted_text, custom_key)
print(f'Decrypted Text: {decrypted_text}')

## Acknowledgments
- This project is inspired by the Scientific Python Certification course from [FreeCodeCamp](https://www.freecodecamp.org/).
