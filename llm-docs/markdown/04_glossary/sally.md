# sally

is an implementation of a verification service and acting as a reporting server. It is purpose-built software for the vLEI ecosystem to allow participants in the vLEI ecosystem present credentials, so the [GLEIF](https://weboftrust.github.io/WOT-terms/docs/glossary/GLEIF.md) Reporting API can show what [vLEIs](https://weboftrust.github.io/WOT-terms/docs/glossary/vLEI.md) are; issued to [Legal Entities](https://weboftrust.github.io/WOT-terms/docs/glossary/legal-entity.md).

The Sally [vLEI](https://weboftrust.github.io/WOT-terms/docs/glossary/vLEI.md) Audit Reporting Agent _receives presentations of credentials_ and notices of [revocation](https://weboftrust.github.io/WOT-terms/docs/glossary/revocation-event.md), verifies the structure and cryptographic integrity of the credential or revocation event and performs a POST to the configured webhook [URL](https://weboftrust.github.io/WOT-terms/docs/glossary/URL.md)
[Source](https://github.com/GLEIF-IT/sally)