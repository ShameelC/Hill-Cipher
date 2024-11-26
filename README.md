# Hill Cipher Encryption and Decryption Without Libraries

This project implements the Hill Cipher algorithm in Python, which is a classical encryption technique. The Hill Cipher encrypts and decrypts text using a matrix-based system, making it one of the oldest and most well-known cipher methods.

## Features
- **Encryption**: Takes a plaintext message and encrypts it using a 3x3 key matrix.
- **Decryption**: Decrypts the ciphertext back to plaintext using the modular inverse of the key matrix.
- **Padding**: Automatically adds padding ('X') to the plaintext if its length is not divisible by 3.
- **Key Generation**: The key is provided as a string, which is converted into a 3x3 matrix of numbers.

## Requirements

- Python 3.x
- NumPy library

To install NumPy, run the following:
```bash
pip install numpy
