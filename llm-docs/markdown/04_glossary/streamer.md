# streamer

A convenience class for supporting stream parsing, including nested (tunneled, encrypted) [CESR](https://weboftrust.github.io/WOT-terms/docs/glossary/CESR.md) streams. Streams can be a mixture/combination of different [primitives](https://weboftrust.github.io/WOT-terms/docs/glossary/primitive.md), including other streams. A stream is a concatenation of primitives. Source: Kent Bull in chat Zoom meeting KERI Aug 6, 2024.

It is akin to a cryptographic primitive yet is not a cryptographic primitive itself.

It supports [ESSR](https://weboftrust.github.io/WOT-terms/docs/glossary/ESSR.md) by making it easier to handle tunneled streams. Source: Kent Bull in chat Zoom meeting KERI Aug 6, 2024.