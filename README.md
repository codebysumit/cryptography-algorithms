# Cryptography Algorithms

A collection of classic cryptography algorithms implemented in Python notebooks. Each notebook covers the logic, encryption, and decryption steps for that cipher.

## 1. Monoalphabetic Substitution Ciphers

In these ciphers, each letter is replaced by another letter using **one fixed rule**. The same letter always becomes the same new letter, throughout the whole message. This makes them easy to break using frequency analysis.

1. [`caesar_cipher.ipynb`](notebooks/caesar_cipher.ipynb)
2. [`affine_cipher.ipynb`](notebooks/affine_cipher.ipynb)
3. [`multiplicative_cipher.ipynb`](notebooks/multiplicative_cipher.ipynb)

## 2. Polyalphabetic Substitution Ciphers

Here, **more than one substitution rule** is used, and the rule keeps changing as the message goes on, usually based on a keyword. This hides letter patterns better than monoalphabetic ciphers, so they are harder to crack.

1. [`vigenere_cipher.ipynb`](notebooks/vigenere_cipher.ipynb)
2. [`autokey_cipher.ipynb`](notebooks/autokey_cipher.ipynb)
3. [`one_time_pad.ipynb`](notebooks/one_time_pad.ipynb)

## 3. Polygraphic Substitution Ciphers

These ciphers encrypt **groups of letters together** instead of one letter at a time. Playfair works on pairs of letters, and Hill cipher uses matrix multiplication on blocks of letters.

1. [`playfair_cipher_5x5.ipynb`](notebooks/playfair_cipher_5x5.ipynb)
2. [`playfair_cipher_6x6.ipynb`](notebooks/playfair_cipher_6x6.ipynb)
3. [`hill_cipher.ipynb`](notebooks/hill_cipher.ipynb)

## 4. Transposition Ciphers

In these ciphers, the letters themselves do not change. Only their **positions get rearranged** using some pattern or key. Since letters stay the same, frequency analysis alone cannot break these.

1. [`rail_fence_cipher.ipynb`](notebooks/rail_fence_cipher.ipynb)
2. [`columnar_transposition_cipher.ipynb`](notebooks/columnar_transposition_cipher.ipynb)
3. [`columnar_transposition_multi_round.ipynb`](notebooks/columnar_transposition_multi_round.ipynb)

## 5. Key Based / Reference Ciphers

These ciphers do not use a mathematical formula. Instead, they use an outside reference (like a book) as the key. Both sender and receiver must have the exact same reference.

1. [`book_cipher.ipynb`](notebooks/book_cipher.ipynb)
