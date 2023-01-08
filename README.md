# Lamport Signatures (one-time signatures)

Lamport Signatures are a digital signature scheme that uses a one-way function (hash function) to generate a signature. This is a one-time signature scheme, meaning that the same message cannot be signed twice. See [wikipedia](https://en.wikipedia.org/wiki/Lamport_signature) for more information.

They are interesting as they are assumed to be secure against a quantum computer due to only relying on hash functions.

**References**:

- [Original Lamport Signatures Paper](https://www.microsoft.com/en-us/research/publication/2016/12/Constructing-Digital-Signatures-from-a-One-Way-Function.pdf)
- [Fast Accumulated Hashing Paper](https://link.springer.com/content/pdf/10.1007/3-540-60865-6_45.pdf?pdf=inline%20link)
<!-- TODO: see if Fast Accumulated Hashing Paper is actually useful -->

<!-- @article{lamport1979constructing,
title={Constructing digital signatures from a one way function},
author={Lamport, Leslie},
year={1979}
} -->
