# Reading: Class 18 (Cryptography)

> [Back to  main](./README.md)
---------------------------
- what is Cryptography
Modern encryption is the key to advanced computer and communication security. This stream of cryptography is completely based on the ideas of mathematics such as number theory and computational complexity theory, as well as concepts of probability.
In this chapter, you will learn about the different elements and characteristics of modern cryptography.

*****************************************************************************
 - Symmetric Key Encryption 
Symmetric key encryption technique uses a straight forward method of encryption. Hence, this is the simpler among these two practices. In the case of symmetric key encryption, the encryption is done through only one secret key, which is known as "Symmetric Key", and this key remains to both the parties.

 - Asymmetric Encryption
is another encryption method that uses two keys: a new and sophisticated encryption technique. This is because it integrates two cryptographic keys for implementing data security. These keys are termed as Public Key and Private Key. The "public key", as the name implies, is accessible to all who want to send an encrypted message. The other is the "private key" that is kept secure by the owner of that public key or the one who is encrypting.

Encryption of information is done through a public key first, with the help of a particular algorithm. Then the private key, which the receiver possesses, will use to decrypt that encrypted information. The same algorithm will be used in both encodings as well as decoding. Examples of asymmetric key encryption algorithms are Diffie-Hellman and RSA algorithm.

******************************************************************************


## Caesar Cipher

One of the earliest encryption techniques is the Caesar Cipher, invented by Julius Caesar more than two thousand years ago to communicate messages to his allies.
The Caesar Cipher is a great introduction to encryption, decryption, and code cracking, thanks to its simplicity.

In cryptography, a Caesar cipher, also known as Caesar's cipher, the shift cipher, Caesar's code or Caesar shift, is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet. For example, with a left shift of 3, D would be replaced by A, E would become B, and so on. The method is named after Julius Caesar, who used it in his private correspondence.
*******************************************************************************

- Example Encrypting a message :
Imagine Caesar wants to send this message:
```
SECRET MEETING AT THE PALACE 
Here's what that might look like encrypted:
YKIXKZ SKKZOTM GZ ZNK VGRGIK

```