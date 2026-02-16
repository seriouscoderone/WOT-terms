# cesride

is concerned with parsing CESR primitives.

Cesride is built from cryptographic primitives that are named clearly and concisely. There are:

-   [Diger](https://weboftrust.github.io/WOT-terms/docs/glossary/diger.md)
-   [Verfer](https://weboftrust.github.io/WOT-terms/docs/glossary/verfer.md)
-   [Signer](https://weboftrust.github.io/WOT-terms/docs/glossary/signer.md)
-   [Siger](https://weboftrust.github.io/WOT-terms/docs/glossary/siger.md)
-   [Cigar](https://weboftrust.github.io/WOT-terms/docs/glossary/cigar.md)
-   [Salter](https://weboftrust.github.io/WOT-terms/docs/glossary/salter.md)

Each primitive will have methods attached to it that permit one to generate and parse the qualified base2 or [base64](https://weboftrust.github.io/WOT-terms/docs/glossary/base64.md) representation.

Common methods you'll find:

-   `.qb64()` - qualified base-64 representation of cryptographic material as a string
-   `.qb64b()` - qualified base-64 representation of cryptographic material as octets (bytes)
-   `.qb2()` - qualified base-2 representation of cryptographic material as octets (bytes)
-   `.code()` - qualifying code (describes the type of cryptographic material)
-   `.raw()` - raw cryptographic material (unqualified) as octets (bytes)

[Source](https://github.com/WebOfTrust/cesride#terminology) by Jason Colburne

[Parside](https://weboftrust.github.io/WOT-terms/docs/glossary/parside.md)