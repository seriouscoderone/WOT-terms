# revocation-event

An event that revokes [control authority](https://weboftrust.github.io/WOT-terms/docs/glossary/control-authority.md) over an [identifier](https://weboftrust.github.io/WOT-terms/docs/glossary/identifier.md). From that point in time the authoritative key-pairs at hand are not valid anymore.

The time stamp of a revocation is useful but not for security purposes, it can be gamed by an attacker. KERI should be fitted in a way so that it's _not possible_ to rewrite history. The tool we have is the ordering of the events in a [KEL](https://weboftrust.github.io/WOT-terms/docs/glossary/KEL.md).

[Revocation](https://weboftrust.github.io/WOT-terms/docs/glossary/revocation.md)

A temporary revocation of a grant or privilege is called a suspension. We don't have this type of state or event in KERI.