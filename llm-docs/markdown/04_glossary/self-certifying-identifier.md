# Self-certifying identifier

a type of Cryptonym that is uniquely cryptographically derived from the public key of an asymmetric signing keypair (public, private).
Source: Dr. S. Smith

A Self-Certifying Identifier (SCID) cryptographically binds an identifier to one or more public/private key pairs. It is an identifier that can be proven to be the one and only identifier tied to a public key using cryptography alone.

A [controller](https://weboftrust.github.io/WOT-terms/docs/glossary/controller.md) issues an own Identifier by binding a generated public private key pair to an identifier. After this a controller is able to sign the identifier and create a certificate. Also called a _cryptonym_. The simplest form of a self-certifying identifier includes either the public key or a unique fingerprint of the public key as a [prefix](https://weboftrust.github.io/WOT-terms/docs/glossary/prefix.md) in the identifier.

-   Self-contained secure cryptographic [root-of-trust](https://weboftrust.github.io/WOT-terms/docs/glossary/root-of-trust.md)
-   Decentralized control via [private key management](https://weboftrust.github.io/WOT-terms/docs/glossary/PKI.md)
-   Universally unique identifiers

A self-certifying identifier (SCID) is a type of [cryptonym](https://weboftrust.github.io/WOT-terms/docs/glossary/cryptonym.md) that is uniquely cryptographically derived from the public key of an asymmetric non-repudiable signing keypair, (public, private).
It is self-certifying or more precisely **self-authenticating** because it does not rely on a trusted entity. The [authenticity](https://weboftrust.github.io/WOT-terms/docs/glossary/authenticity.md) of a non-repudiable signature made with the private key may be verified by extracting the public key from either the identifier itself or incepting information uniquely associated with the cryptographic derivation process for the identifier. In a _basic SCID_, the mapping between an identifier and its controlling public key is self-contained in the identifier itself. A basic SCID is [ephemeral](https://weboftrust.github.io/WOT-terms/docs/glossary/ephemeral.md) i.e. it does not support [rotation](https://weboftrust.github.io/WOT-terms/docs/glossary/rotation.md) of its keypairs in the event of key weakness or compromise and therefore must be abandoned once the controlling private key becomes weakened or compromised from exposure.