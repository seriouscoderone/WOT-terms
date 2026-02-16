# security-overlay-properties-trillema

An identifier system has some degree of any combination of the three properties [authenticity](https://weboftrust.github.io/WOT-terms/docs/glossary/authenticity.md), [privacy](https://weboftrust.github.io/WOT-terms/docs/glossary/privacy.md) and [confidentiality](https://weboftrust.github.io/WOT-terms/docs/glossary/confidentiality.md), but not all three completely.

The reason a system may not provide all three completely is that no single cryptographic operation provides all three properties.
As a result any cryptographic system must layer the operations. But layering exposes weaknesses due to the separation between the layers. Because no single layer can exhibit all three properties, one must pick one or two properties for the bottom layer and then layer on top the remaining property or properties on one or more layers.
Source: Universal Identifier Theory by Samuel Smith

![Trilemma of Identifier System Properties](https://github.com/WebOfTrust/WOT-terms/blob/df57ca77aafca255f4c4ddefb099151009d85556/static/img/Trilemma-of-Identifier-System-Properties.png?raw=true)