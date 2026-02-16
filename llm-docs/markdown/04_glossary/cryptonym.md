# cryptonym

a cryptographic pseudonymous identifier represented by a string of characters derived from a random or pseudo-random secret seed or salt via a one-way cryptographic function with a sufficiently high degree of cryptographic strength (e.g., 128 bits, see appendix on [cryptographic strength](https://weboftrust.github.io/WOT-terms/docs/glossary/cryptographic-strength.md). A cryptonym is a type of [primitive](https://weboftrust.github.io/WOT-terms/docs/glossary/primitive.md).

Due to the [entropy](https://weboftrust.github.io/WOT-terms/docs/glossary/entropy.md) in its derivation, a cryptonym is a universally unique identifier, and only the [controller](https://weboftrust.github.io/WOT-terms/docs/glossary/controller.md) of the secret [salt](https://weboftrust.github.io/WOT-terms/docs/glossary/salt.md) or [seed](https://weboftrust.github.io/WOT-terms/docs/glossary/seed.md) from which the cryptonym is derived may prove control over the cryptonym. Therefore, the derivation function MUST be associated with the cryptonym and may be encoded as part of the cryptonym itself.
Source [Smith, ietf-keri draft](https://github.com/WebOfTrust/ietf-keri/blob/main/draft-ssmith-keri.md)

A code name, call sign, or cryptonym is a [code word](https://en.wikipedia.org/wiki/Code_word_\(figure_of_speech\)) or name used, sometimes clandestinely, to refer to another name, word, project, or person.
Source [Wikipedia](https://en.wikipedia.org/wiki/Code_name)