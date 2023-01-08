# Lamport Signatures (one-time signatures)

Lamport Signatures are a digital signature scheme that uses a one-way function (hash function) to generate a signature. This is a one-time signature scheme, meaning that the same message cannot be signed twice. See [wikipedia](https://en.wikipedia.org/wiki/Lamport_signature) for more information.

They are interesting as they are assumed to be secure against a quantum computer due to only relying on hash functions.

These notebooks are used for my own learning and are not intended to be a complete reference. They are based on the original paper by Lamport.

## **Notebooks**

- [Naive Lamport Signatures](naive_lamport_signature.ipynb): A basic implementation of the original Lamport Signatures paper with uncompressed public and private keys

**References**:

- [Original Lamport Signatures Paper](https://www.microsoft.com/en-us/research/publication/2016/12/Constructing-Digital-Signatures-from-a-One-Way-Function.pdf)
- [Fast Accumulated Hashing Paper](https://link.springer.com/content/pdf/10.1007/3-540-60865-6_45.pdf?pdf=inline%20link)
<!-- TODO: see if Fast Accumulated Hashing Paper is actually useful -->

<!-- @article{lamport1979constructing,
title={Constructing digital signatures from a one way function},
author={Lamport, Leslie},
year={1979}
} -->
