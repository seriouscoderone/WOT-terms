# secondary-root-of-trust

In KERI its a [root-of-trust](https://weboftrust.github.io/WOT-terms/docs/glossary/root-of-trust.md) that, for its secure attribution, depends on another verifiable data structure (VDS) which MUST be a [primary root-of-trust](https://weboftrust.github.io/WOT-terms/docs/glossary/primary-root-of-trust.md).
By its nature and cryptographic anchoring via [seals](https://weboftrust.github.io/WOT-terms/docs/glossary/seal.md) to a primary root-of-trust, a secondary root-of-trust still has a high level of trustability and can be automatically verified.