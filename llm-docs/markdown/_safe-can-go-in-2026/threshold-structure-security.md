# threshold-structure-security

A threshold structure for security allows for weaker key management or execution environment infrastructure individually, but achieve greater overall security by multiplying the number of attack surfaces that an attacker must overcome to compromise a system.

With threshold structures, overall security may be greater than the security of any of the individual parts.

In [MFA](https://weboftrust.github.io/WOT-terms/docs/glossary/multi-factor-authentication.md) the combination of two factors, something you have and something you know, may be much more secure than either of the factors by themselves.

Threshold structures may be employed in a complementary manner to trusted execution environments ([TEE](https://weboftrust.github.io/WOT-terms/docs/glossary/trusted-execution-environment.md)) for security. The two types of security are complementary.

This applies to KERI as well. The [witnesses](https://weboftrust.github.io/WOT-terms/docs/glossary/witness.md) and [watchers](https://weboftrust.github.io/WOT-terms/docs/glossary/watcher.md) independently multiply the attack surfaces of the promulgation and the confirmation networks such that each witness or watcher respectively may be relatively insecure but the system as a whole may be highly secure.

Numerous papers discuss how secure a distributed consensus pool may be. But when comparing _apples_ (key management and trusted execution environment (TEE) approach to security) to _oranges_ (distributed consensus approach to security) its hard to say that the security of a distributed consensus algorithm is necessarily less secure than the key management infra-structure root-of-trust of any of its nodes. Although as a general rule, in an apples to apples comparison, _more complex is less secure_.

Source: Universal Identifier Theory by Samuel Smith