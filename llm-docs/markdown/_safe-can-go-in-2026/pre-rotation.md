# pre-rotation

Cryptographic commitment to next rotated key set in previous rotation or [inception event](https://weboftrust.github.io/WOT-terms/docs/glossary/inception-event.md).

The main purpose of [key rotation](https://weboftrust.github.io/WOT-terms/docs/glossary/rotation.md) it to either prevent or recover from a successful compromise of one or more private keys by an exploiter. Given a potentially compromised private key, an exploiter could sign statements and even capture full control over the identifier by rotating the current key pair.

Pre-rotation mitigates successful exploit of a given set of signing private keys. There are several assumptions listed in [chapter Pre-rotation of the KERI white paper](https://github.com/SmithSamuelM/Papers/blob/master/whitepapers/KERI_WP_2.x.web.pdf) about the circumstances under which pre-rotation is able to sustain this mitigation, e.g. it assumes that the private keys remains private until after issuance of the associated identifier.

Pre-rotation is a new invention in KERI. Pre-rotation is a cryptographic commitment (a hash) to the next private/public key in the rotation-scheme.
[Source: chapter Pre-rotation in whitepaper](https://github.com/SmithSamuelM/Papers/blob/master/whitepapers/KERI_WP_2.x.web.pdf)