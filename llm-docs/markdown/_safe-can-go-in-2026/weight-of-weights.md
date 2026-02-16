# weight-of-weights

There are 2 levels in the multi-sign weighted thresholds of [multi-signatures](https://weboftrust.github.io/WOT-terms/docs/glossary/multisig.md) in [KERI](https://weboftrust.github.io/WOT-terms/docs/glossary/KERI.md) because the solution only needs to focus on _tightly cooperating teams_.

-   An individual using split keys over devices
-   A team of teams

All other use cases can be solved by other means in KERI (e.g. [delegation](https://weboftrust.github.io/WOT-terms/docs/glossary/delegation.md)).

It also gives the advantage that the resulting [CESR](https://weboftrust.github.io/WOT-terms/docs/glossary/CESR.md) is more straightforward. It's hard to implement a recursive weight - of weights in CESR. And because of the alleged lack of use cases, KERI don't need to go beyond two levels.