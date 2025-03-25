# RSA Encryption Implementation

A Python implementation of the RSA public-key cryptosystem.

## Features
- Key generation (public/private key pair)
- Message encryption/decryption
- Large prime number generation
- Modular arithmetic operations

## Requirements
- Python 3.x
- sympy (`pip install sympy`)

## Usage
1. Run the script: `python rsa_encryption.py`
2. Enter a message to encrypt when prompted
3. View the encrypted and decrypted results

## Implementation Details
- Uses 1024-bit keys by default
- Implements the complete RSA algorithm including:
  - Key generation
  - Encryption/decryption
  - Extended Euclidean algorithm for modular inverse
