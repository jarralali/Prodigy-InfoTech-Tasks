# Task 1: Implement Caesar Cipher
# Description
This repository contains a Python implementation of the Caesar cipher, a classic encryption technique used in cryptography. The Caesar cipher is one of the simplest and most well-known encryption methods. It works by shifting each letter in the plaintext by a fixed number of positions down or up the alphabet. This method is named after Julius Caesar, who is reputed to have used it to communicate with his military commanders.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Features
Encryption: Convert plaintext into ciphertext by shifting each letter by a specified number of positions.
Decryption: Revert ciphertext back to plaintext by shifting in the opposite direction of the encryption.
Flexible Shifting: Support for both positive and negative shift values, allowing for versatile encryption and decryption.
Handling Non-Alphabetic Characters: Preserve non-alphabetic characters (e.g., numbers, punctuation) without modification.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# How It Works
Encryption Function: Takes a message and a shift amount as inputs. It processes each letter in the message, shifts it by the specified amount, and constructs the encrypted message.
Decryption Function: Utilizes the encryption function with the negative of the shift amount to return the original message from the encrypted text.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Usage
To use the Caesar cipher functions, run the following commands:

# Import the functions
from caesar_cipher import encrypt, decrypt

# Example usage
message = input("Enter the message to encrypt or decrypt: ")
shift_value = int(input("Please enter the shift value: "))

# Encrypt the message
encrypted_message = encrypt(message, shift_value)
print(f"Encrypted message: {encrypted_message}")

# Decrypt the message
decrypted_message = decrypt(encrypted_message, shift_value)
print(f"Decrypted message: {decrypted_message}")
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Requirements
Python 3.x
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Installation
Clone this repository and run the Python script directly:

git clone <repository_url>
cd <repository_directory>
python caesar_cipher.py
