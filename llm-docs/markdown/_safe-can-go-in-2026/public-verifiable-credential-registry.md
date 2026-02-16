# public-verifiable-credential-registry

is a form of a [Verifiable Data Registry](https://github.com/trustoverip/toip/wiki/credential-registry) that tracks the issuance/revocation state of credentials issued by the controller of the [KEL](https://weboftrust.github.io/WOT-terms/docs/glossary/key-event-log.md). Two types of TELs will be used for this purpose: [management TEL](https://weboftrust.github.io/WOT-terms/docs/glossary/management-transaction-event-log.md) and [VC TEL](https://weboftrust.github.io/WOT-terms/docs/glossary/virtual-credential-transaction-event-log.md).

The first type of [TEL](https://weboftrust.github.io/WOT-terms/docs/glossary/transaction-event-log.md) is the _management TEL_ and will signal the creation of the Registry and track the list of Registrars that will act as [Backers](https://weboftrust.github.io/WOT-terms/docs/glossary/backer.md) for the individual TELs for each [VC](https://weboftrust.github.io/WOT-terms/docs/glossary/verifiable-credential.md). The second type of TEL is the _VC TEL_, which will track the issued or revoked state of each VC and will contain a reference to its corresponding management TEL.

| TBW | prio2