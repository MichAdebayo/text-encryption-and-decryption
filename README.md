# Text Encryption and Decryption: Implementing the Caesar Cipher and Columnar Transposition Cipher

## Case Description

Cryptography is a critical problem in programming that has engaged researchers for many decades. With better encryption methods, we can better protect sensitive information—such as passwords and personal data—and ensure secure online communication. Therefore, exploring such methods as the caesar cipher and the transposition cipher would contribute towards effort to maintaining data integrity and confidentiality.

### The Caesar Cipher

The caesar cipher is a simple yet effective way of encrypting a text to render it unreadable to anyone without the key to decrypting/decoding the text. It relies on substituting texts by shifting each letter in the text by a fixed number of places down or up the alphabet. In this project, I implement the caesar cipher by creating a **CaesarCipher class**.

### The Columnar Transposition Cipher

The transposition cipher is another way of encrypting a text in a more secure way than the caesar cipher and also makes a text unreadable to anyone who doesn’t possess the key to decryption. It relies on scrambling the words in plaintext by rearranging its characters. While transposition ciphers come in various forms, each contributing a unique layer of complexity, in this project, I implement the columnar transposition cipher by creating a **TranspositionCipher class**.

In this [Jupyter Notebook](https://nbviewer.org/github/MichAdebayo/Text-Encryption-and-Decryption/blob/main/Encryption%20and%20Decryption%20in%20Python%20Project.ipynb), you will learn how I implemented both ciphers by creating:

* A **constructor function** that accepts the cipher's key as an argument.
  
* A **method** designated for encrypting a message requiring a single parameter—the plaintext message to be encrypted.
  
* A **method** dedicated to decrypting a message that calls for one argument—the previously encrypted message in ciphertext format.

* Example texts to test whether both ciphers work accurately.

## Testing the Caesar Cipher

The following string was passed as text: "The United Kingdom publishes first guidelines for human embryo models grown from stem cells."

<div align="center">
<img width="1143" alt="Screenshot 2024-07-09 at 14 56 52" src="https://github.com/MichAdebayo/Text-Encryption-and-Decryption/assets/92400436/90e4cdce-46a7-434b-805a-92d0315fbfd0">
</div>

## Testing the Columnar Transposition Cipher

The following string was passed as text: "The United Kingdom publishes first guidelines for human embryo models grown from stem cells."

<div align="center">
<img width="1146" alt="Screenshot 2024-07-09 at 14 57 48" src="https://github.com/MichAdebayo/Text-Encryption-and-Decryption/assets/92400436/63c73c09-1c9f-45a3-8480-7118d11d039f">
</div>

## Relevant Links

* [Jupyter Notebook](https://nbviewer.org/github/MichAdebayo/Text-Encryption-and-Decryption/blob/main/Encryption%20and%20Decryption%20in%20Python%20Project.ipynb)
* [LinkedIn](https://www.linkedin.com/in/adebayomichael/)
