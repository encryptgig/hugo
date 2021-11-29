---
date: 2021-04-07T10:58:08-04:00
description: "Biometric authentication is a security process that relies on unique biological characteristics to verify the identity of individuals."
featured_image: "/images/encryptgig_crypto_basics.jpg"
title: "Basics of cryptography keys and about encryptgig algorithm "
---

### Goals of cryptographic keys (CIA triad)?



**Confidentiality**:
Confidentiality ensures that data remains private in three different situations: when it is at rest, when it is in transit, and when it is in use.
**Integrity**:
Integrity ensures that data is not altered without authorization. If integrity mechanisms are in place, the recipient of a message can be certain that the message received is identical to the message that was sent.

**Availability**:
Availability ensures Information is available all time without any alteration or downtime



##### Cryptographic basics #####

Before a message is put into a coded form, it is known as a plaintext message and is represented by the letter P when encryption functions are described. The sender of a message uses a cryptographic algorithm to encrypt the plaintext message and produce a ciphertext message, represented by the letter C. This message is transmitted by some physical or electronic means to the recipient. The recipient then uses a predetermined algorithm to decrypt the ciphertext message and retrieve the plaintext version.

##### Modern Cryptography #####

Modern cryptosystems use complex algorithms via computers and machines, and long cryptographic keys to meet the cryptographic goals of confidentiality, integrity, authentication, and nonrepudiation.


##### Cryptographic Keys #####

Data Encryption Standard (DES) was created in 1975, a 56-bit key was considered sufficient to maintain the security of any data. However, there is now widespread agreement that the 56-bit DES algorithm is no longer secure because of advances in cryptanalysis techniques and supercomputing power.

**Sanity checks while maintaining keys**

Always store secret keys securely and, if you must transmit them over a network, do so in a manner that protects them from unauthorized disclosure.
Select keys using an approach that has as much randomness as possible, taking advantage of the entire key space.
Destroy keys securely when they are no longer needed.


**Symmetric Key Algorithms**

Symmetric key algorithms rely on a “shared secret” encryption key that is distributed to all members who participate in the communications. This key is used by all parties to both encrypt and decrypt messages, so the sender and the receiver both possess a copy of the shared key. The sender encrypts with the shared secret key and the receiver decrypts with it.
Symmetric Key has the advantage of having a speedy operation. On the other side, it comes with key distribution and scalability challenges.

**Asymmetric Key Algorithms**

Asymmetric key algorithms provide a solution to the weaknesses of symmetric key encryption. Public key algorithms are the most common example of asymmetric algorithms. In these systems, each user has two keys: a public key, which is shared with all users, and a private key, which is kept secret and known only to the user. But here's a twist: opposite and related keys must be used in tandem to encrypt and decrypt. Major strengths of asymmetric key cryptography are scalability and ease of key distribution, while disadvantage of it being slow speed of operation.

At **encryptgig**, we use the most advance 256-bit key to encrypt every data. We're built on zero trust model to ensure keys confidentiality, integrity, availability and Non-repudiation. We use both DEK (symmetric) using KEK (asymmetric), hence our customers can enjoy the state of art cyber security.  Interested to know about our products, do reach out at 
 To know more about our product- [encryptgig](https://app.encryptgig.com/EncryptFile) or reach us out: contact@encryptgig.com

