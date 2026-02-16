# fully-compact

The most compact form of an [ACDC](https://weboftrust.github.io/WOT-terms/docs/glossary/ACDC.md). This is the only signed variant of an ACDC and this signature is anchored in a [transaction event log](https://weboftrust.github.io/WOT-terms/docs/glossary/transaction-event-log.md) (TEL) for the ACDC. This is one valid choice for an ACDC schema.
This form is part of the [graduated disclosure](https://weboftrust.github.io/WOT-terms/docs/glossary/graduated-disclosure.md) mechanism in ACDCs.

The extra a fully compact version has to offer over a [most compact](https://weboftrust.github.io/WOT-terms/docs/glossary/most-compact.md) version is the anchoring to the [Tranaction event log](https://weboftrust.github.io/WOT-terms/docs/glossary/transaction-event-log.md). Here were various proofs ([hashes](https://weboftrust.github.io/WOT-terms/docs/glossary/distributed-hash-table.md)) can be "stored" which are optional in all kind of [ACDC](https://weboftrust.github.io/WOT-terms/docs/glossary/ACDC.md) variants.

[Fully (expanded)](https://weboftrust.github.io/WOT-terms/docs/glossary/fully-expanded.md) version of an ACDC
[Most compact](https://weboftrust.github.io/WOT-terms/docs/glossary/most-compact.md) version of an ACDC.

A fully compact ACDC is like the core of an onion and the fully expanded ACDC is like rest of the outer layers of the onion. Turn this onion inside-out: you only need to sign the core (most compact), and then the whole onion (expanded version) would verify. The complete (expanded) onion is the most user friendly information bulb you can get, and you don't need to peel off all the rings of the onion to securely attribute _all_ the information to the controller of the [SAID](https://weboftrust.github.io/WOT-terms/docs/glossary/SAID.md) that signed the core.

You can present any version of the onion you like: only the core, one partially stripped back, one layer at a time, or the whole thing (fully expanded). This illustrates part of the rational for why ACDCs matter. They offer a layered, graduated disclosure mechanism of verifiable credentials never seen before in the SSI field.