This repository contains a Python implementation of the Playfair cipher, a manual symmetric encryption technique that encrypts pairs of letters instead of single letters as in traditional simple substitution ciphers.
The Playfair cipher was invented by Charles Wheatstone in 1854 but was named after Lord Playfair who promoted its use. It was used for tactical communication by British forces in the Boer War and World War I.
Features:

Message Encryption: Convert plaintext to ciphertext using the Playfair algorithm
Message Decryption: Convert ciphertext back to plaintext
Complete Implementation: Handles all Playfair cipher rules including:

Letter pair processing
Same-letter handling (replacing with 'X')
Rectangle, row, and column case encryption/decryption
Proper character normalization (uppercase conversion, J→I substitution)

This problem was included as part of CS 1301's final problem set I took over the summer :)
