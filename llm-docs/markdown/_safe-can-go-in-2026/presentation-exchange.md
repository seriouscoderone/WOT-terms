# presentation-exchange

An exchange that provides disclosure of one or more [ACDC](https://weboftrust.github.io/WOT-terms/docs/glossary/authentic-chained-data-container.md)s between a Discloser and a Disclosee.

A presentation exchange is the process by which [authenticatable](https://weboftrust.github.io/WOT-terms/docs/glossary/authenticity.md) information may be exchanged between two parties, namely, the [Discloser](https://weboftrust.github.io/WOT-terms/docs/glossary/discloser.md) and [Disclosee](https://weboftrust.github.io/WOT-terms/docs/glossary/disclosee.md).

Each ACDC MUST have an [Issuer](https://weboftrust.github.io/WOT-terms/docs/glossary/issuer.md) and MAY have an [Issuee](https://weboftrust.github.io/WOT-terms/docs/glossary/issuee.md). The set of [ACDC](https://weboftrust.github.io/WOT-terms/docs/glossary/ACDC.md)s so disclosed in a presentation exchange MUST be chained. This set of chained ACDCs define a [directed acyclic graph](https://weboftrust.github.io/WOT-terms/docs/glossary/directed-acyclic-graph.md) that MUST have at least one vertex and MAY have zero or more edges pointing to other vertices.