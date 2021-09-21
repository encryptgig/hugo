---
date: 2017-04-09T10:58:08-04:00
description: "In cryptography, PKCS #11 is one of the Public-Key Cryptography Standards,[1] and also refers to the programming interface to create and manipulate cryptographic tokens (a token where the secret is a cryptographic key)."
featured_image: "/images/post7.jpeg"
title: "PKCS #11"
---

### Detail

The PKCS #11 standard defines a platform-independent API to cryptographic tokens, such as hardware security modules (HSM) and smart cards, and names the API itself "Cryptoki" (from "cryptographic token interface" and pronounced as "crypto-key", although "PKCS #11" is often used to refer to the API as well as the standard that defines it).

The API defines most commonly used cryptographic object types (RSA keys, X.509 certificates, DES/Triple DES keys, etc.) and all the functions needed to use, create/generate, modify and delete those objects.

### Usage

Most commercial certificate authority (CA) software uses PKCS #11 to access the CA signing key[clarification needed] or to enroll user certificates. Cross-platform software that needs to use smart cards uses PKCS #11, such as Mozilla Firefox and OpenSSL (using an extension). It is also used to access smart cards and HSMs. Software written for Microsoft Windows may use the platform specific MS-CAPI API instead. Both Oracle Solaris and Red Hat Enterprise Linux contain implementations for use by applications, as well.

### Relationship to KMIP

The Key Management Interoperability Protocol (KMIP) defines a wire protocol that has similar functionality to the PKCS#11 API.

The two standards were originally developed independently but are now both governed by an OASIS technical committee. It is the stated objective of both the PKCS#11 and KMIP committees to align the standards where practicable. For example, the PKCS#11 Sensitive and Extractable attributes are being added to KMIP version 1.4. There is considerable overlap between members of the two technical committees.
