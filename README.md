# ROT13 Cryptographic Key Algorithm

## Overview

This project implements the ROT13 algorithm, a simple encryption method that shifts each letter of the plaintext by 13 positions in the alphabet. ROT13 stands for "rotate by 13 places" and is a type of Caesar cipher, a classical encryption technique. It is primarily used for obfuscating text—such as spoilers or puzzle solutions—where the main goal is not to secure the data, but to temporarily obscure it.

ROT13 is a symmetric cipher, meaning that applying the algorithm twice restores the original text. It’s considered a basic form of encryption and is widely used in scenarios where the data does not need to be securely protected, but rather hidden from casual viewers. ROT13 is commonly used to hide spoilers, puzzle answers, or other information that should only be revealed when intentionally decrypted.

## How ROT13 Works

- Each letter in the text is replaced by the letter 13 positions ahead in the alphabet.
  - Example: `A → N`
  - Example: `Z → M`
- Non-alphabetical characters (such as spaces, punctuation, and numbers) remain unchanged.
- ROT13 is a self-inverse cipher: applying ROT13 twice results in the original text.

### Example

**Plaintext:**
Hello, World!

csharp
Copy
Edit

**Encrypted with ROT13:**
Uryyb, Jbeyq!

markdown
Copy
Edit

**Decrypted (ROT13 again):**
Hello, World!

markdown
Copy
Edit

## Use Cases

- **Obfuscation**: Frequently used to hide spoilers or sensitive information temporarily.
- **Educational**: A simple example of encryption used to demonstrate how substitution ciphers work.
