# naive-conversion

Non-CESR Base64 conversion. How people are used to using the Base64 encode and decode. Without [pre-pad](https://weboftrust.github.io/WOT-terms/docs/glossary/pre-pad.md)ding etc all the stuff CESR does to ensure aligns on 24 bit boundaries so [CESR](https://weboftrust.github.io/WOT-terms/docs/glossary/CESR.md) never uses the '=' pad character. But naive [Base64](https://weboftrust.github.io/WOT-terms/docs/glossary/base64.md) will pad if the length is not 24 bit aligned.
Source: Samuel Smith in [issue 34](https://github.com/WebOfTrust/ietf-cesr/issues/34)

Naive conversion is a text to binary conversion or vice versa that doesn't anticipate on either [composability](https://weboftrust.github.io/WOT-terms/docs/glossary/composability.md) and / or on the [concatenation](https://weboftrust.github.io/WOT-terms/docs/glossary/concatenation.md) capability of the result of such an operation.

In the [IETF draft CESR](https://github.com/WebOfTrust/ietf-cesr/blob/main/draft-ssmith-cesr.md#conversions) there's much attention for naive [Base64](https://weboftrust.github.io/WOT-terms/docs/glossary/base64.md) conversions, because it helps explaining the necessity of stable code characters and padding in CESR to achieve:

-   [self-framing](https://weboftrust.github.io/WOT-terms/docs/glossary/self-framing.md)
-   round-robin [composability](https://weboftrust.github.io/WOT-terms/docs/glossary/composability.md)
-   [concatenation](https://weboftrust.github.io/WOT-terms/docs/glossary/concatenation.md) options
-   [pipelined](https://weboftrust.github.io/WOT-terms/docs/glossary/pipelining.md) streaming