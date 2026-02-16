# issuee

a role of an entity to which the claims of an ACDC are asserted.
Source: Dr. S. Smith

An [ACDC](https://weboftrust.github.io/WOT-terms/docs/glossary/authentic-chained-data-container.md) is optionally issued to the Issuee. When present, the Issuee identifier ([AID](https://weboftrust.github.io/WOT-terms/docs/glossary/autonomic-identifier.md)) appears at the top level of the attribute section or in the attribute list at the top level of the attribute aggregate section of the ACDC.

Each ACDC MUST have an [Issuer](https://weboftrust.github.io/WOT-terms/docs/glossary/issuer.md) and MAY have an [Issuee](https://weboftrust.github.io/WOT-terms/docs/glossary/issuee.md). The set of [ACDC](https://weboftrust.github.io/WOT-terms/docs/glossary/ACDC.md)s so disclosed in a presentation exchange MUST be chained. This set of chained ACDCs define a [directed acyclic graph](https://weboftrust.github.io/WOT-terms/docs/glossary/directed-acyclic-graph.md) that MUST have at least one vertex and MAY have zero or more edges pointing to other vertices.