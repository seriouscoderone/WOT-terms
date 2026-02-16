# hierarchical-composition

Encoding protocol that is composable in a hierarchy and enables [pipelining](https://weboftrust.github.io/WOT-terms/docs/glossary/pipelining.md) (multiplexing and de-multiplexing) of complex streams in either text or compact binary. This allows management at scale for high-bandwidth applications.

| TBW prio2 |

Because of [count codes](https://weboftrust.github.io/WOT-terms/docs/glossary/count-code.md) and the [composability](https://weboftrust.github.io/WOT-terms/docs/glossary/composability.md) - and [concatenation](https://weboftrust.github.io/WOT-terms/docs/glossary/concatenation.md) property in CESR, [pipelining](https://weboftrust.github.io/WOT-terms/docs/glossary/pipelining.md) is possible, which then uses [multiplexing](https://weboftrust.github.io/WOT-terms/docs/glossary/multiplexing.md) (combining [self-framing](https://weboftrust.github.io/WOT-terms/docs/glossary/self-framing.md) primitives) and _de-multiplexing_ (unravelling self-framing [primitives](https://weboftrust.github.io/WOT-terms/docs/glossary/primitive.md)).