# Vigen-re-Cipher
IMPLEMENTATION OF Vigenère Cipher UISNG PYTHON

Vigenere Cipher is a method of encrypting alphabetic text. 
It uses a simple form of polyalphabetic substitution. 
A polyalphabetic cipher is any cipher based on substitution, using multiple substitution alphabets.
The encryption of the original text is done using the Vigenère square or Vigenère table.

![VIGENERE CIPHER](https://user-images.githubusercontent.com/79416723/149559930-cab5d712-f50e-4461-9578-e03f006bec0f.jpg)
* I USED DEFAULT VALUE OF KEY AS "TEST" ,
Input : Plaintext :   DARSHAN V
             Keyword :  TEST
Output : Ciphertext :  TESTTEST
For generating key, the given keyword is repeated in a circular manner until it matches the length of the plain text.
The keyword "TEST" generates the key "TESTTEST"

A more easy implementation could be to visualize Vigenère algebraically by converting [A-Z] into numbers [0–25]. 
*Encryption
The plaintext(P) and key(K) are added modulo 26.
Ei = (Pi + Ki) mod 26

*Decryption
Di = (Ei - Ki + 26) mod 26



