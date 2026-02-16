# watcher

an _entity_ or _component_ that keeps a copy of a [KERL](https://weboftrust.github.io/WOT-terms/docs/glossary/kerl.md) for an identifier but that is not designated by the _controller_ of the identifier as one of its witnesses. See annex [watcher](https://weboftrust.github.io/WOT-terms/docs/glossary/watcher.md).
Source: Dr. S.Smith

KERI alternative to total global ordering and consensus protocols is a mechanism called [duplicity](https://weboftrust.github.io/WOT-terms/docs/glossary/duplicity.md) detection. In the [verification](https://weboftrust.github.io/WOT-terms/docs/glossary/verifier.md) and [validation](https://weboftrust.github.io/WOT-terms/docs/glossary/validate.md) **watchers are all that matter**; they guarantee that logs are immutable by one very simple rule: "[first seen](https://weboftrust.github.io/WOT-terms/docs/glossary/first-seen.md) wins".

This would be a set of watchers (that the validators trust) that record any and all copies of key event logs (KEL) that they see. Because these watchers can be anyone and anywhere, any controller of a public identifier is at peril should they choose to publish inconsistent copies of their KEL. This removes the incentive to be duplicitous.