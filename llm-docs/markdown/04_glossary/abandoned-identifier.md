# abandoned identifier

An [AID](https://weboftrust.github.io/WOT-terms/docs/glossary/AID.md) is abandoned when either the [Inception](https://weboftrust.github.io/WOT-terms/docs/glossary/inception-event.md) or a subsequent [Rotation event](https://weboftrust.github.io/WOT-terms/docs/glossary/rotation-event.md) rotates to an empty next key digest list (which means the next threshold must also be 0).

When an AID is abandoned, `ndigers` is zero (empty next key digest list ), so any event after the event that made it nontransferable is not accepted.

So more on the [Keripy github discussion page](https://github.com/WebOfTrust/keripy/discussions/821)