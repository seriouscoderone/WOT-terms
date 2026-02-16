# group-framing-code

special Framing Codes that can be specified to support groups of Primitives which make them pipelinable. Self-framing grouping using Count Codes is one of the primary advantages of composable encoding.
Source: Dr. S. Smith

special framing codes can be specified to support groups of [primitives](https://weboftrust.github.io/WOT-terms/docs/glossary/primitive.md) in [CESR](https://weboftrust.github.io/WOT-terms/docs/glossary/composable-event-streaming-representation.md). Grouping enables [pipelining](https://weboftrust.github.io/WOT-terms/docs/glossary/pipelining.md). Other suitable terms for these special framing codes are _group codes_ or _count codes_ for short. These are suitable terms because these framing codes can be used to count characters, primitives in a group, or groups of primitives in a larger group when parsing and off-loading a stream of CESR primitives.
[Source](https://github.com/WebOfTrust/ietf-cesr/blob/main/draft-ssmith-cesr.md#count-group-or-framing-codes)

One of the primary advantages of composable encoding is that we can use special framing code to support the above mentioned grouping.