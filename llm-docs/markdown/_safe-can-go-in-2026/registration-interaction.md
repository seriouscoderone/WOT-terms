# registration-interaction

Setup/Registration interaction, new AID and authorization to establish access control. You present a ([vLEI](https://weboftrust.github.io/WOT-terms/docs/glossary/vLEI.md)) credential. You don't want that captured and misused. Narrowing the scope to a certain role (e.g. Document Submitter) is a pre-registration via [delegatable](https://weboftrust.github.io/WOT-terms/docs/glossary/delegation.md) authority.

The [Credential](https://weboftrust.github.io/WOT-terms/docs/glossary/verifiable-credential.md) is like a bearer token. Does it matter if the credential was delivered by the [issuee](https://weboftrust.github.io/WOT-terms/docs/glossary/issuee.md)? The token is [proof of the authorization](https://weboftrust.github.io/WOT-terms/docs/glossary/proof-of-authority.md), but does the delivery require the issuee signature? Depends on the context. If it is an idempotent process resubmission has no effect.
Source: Samuel Smith / Daniel Hardman / Lance Byrd - Zoom meeting KERI Suite Jan 16 2024; discussion minute 30-60 min

is important, depending on the context or governance model the issuance itself needs / should / could be signed.

[Access-controlled interaction](https://weboftrust.github.io/WOT-terms/docs/glossary/access-controlled-interaction.md)