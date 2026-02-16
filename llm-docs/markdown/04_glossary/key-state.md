# key-state

a set of currently authoritative keypairs for an AID and any other information necessary to secure or establish control authority over an AID. This includes current keys, prior next key digests, current thresholds, prior next thresholds, witnesses, witness thresholds, and configurations.

A key state of an AID is first established through an inception event and may be altered by subsequent rotation events.
Source [Sam Smith](https://github.com/WebOfTrust/ietf-keri/blob/main/draft-ssmith-keri.md#basic-terminology)

A set of authoritative keys for an AID and other essential information necessary to establish, evolve, verify, and validate control-signing authority for that AID. This information includes the current public keys and their thresholds (for a multi-signature scheme); pre-rotated key digests and their thresholds; [witness](https://weboftrust.github.io/WOT-terms/docs/glossary/witness.md)es and their thresholds; and configurations. An AID’s key state is first established through its [inception event](https://weboftrust.github.io/WOT-terms/docs/glossary/inception-event.md) and may evolve via subsequent [rotation event](https://weboftrust.github.io/WOT-terms/docs/glossary/rotation-event.md)s. Thus, an AID’s key state is time-dependent.
Source [Sam Smith](https://github.com/WebOfTrust/ietf-keri/blob/main/draft-ssmith-keri.md#basic-terminology)