# Caesar-cypher
# Caesar Cipher Python Script

This Python script implements a Caesar Cipher, a simple encryption technique where each letter in the message is shifted by a fixed number of positions in the alphabet. The script allows users to both encrypt and decrypt messages using a user-provided key.

## Features

- Encrypts a message by shifting letters according to a user-defined key.
- Decrypts the encrypted message back to its original form using the same key.
- Handles both lowercase and non-alphabetic characters (non-alphabetic characters remain unchanged).

## Prerequisites

- **Python 3.x**: Ensure you have Python installed on your system. You can download it [here](https://www.python.org/downloads/).

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Meelaudn/caesar-cipher-python.git
   cd caesar-cipher-python

   Run the script:
   python caesar_cipher.py

   When prompted, enter your message and key. For example:
   Enter a message: meelaud
   Enter a key: 3

   Output would be:
   Enter a message: meelaud
   Enter a key: 3
   Encrypted message: phhodxg
   Decrypted message: meelaud

How It Works
Encryption
The encryption process shifts each letter in the input message by a fixed number of positions in the alphabet, as specified by the user-provided key. Non-alphabetic characters remain unchanged.

Decryption
The decryption process reverses the encryption by shifting the letters back by the same number of positions using the same key.

Customization
Preserving Case: Currently, the script converts all letters to lowercase. If you need to preserve the case of the original message, you can modify the code to handle both uppercase and lowercase letters.

Handling Non-alphabetic Characters: The script leaves non-alphabetic characters (such as spaces, numbers, and punctuation) unchanged. This can be modified if needed.

   
