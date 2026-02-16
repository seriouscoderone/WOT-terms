# keri-event-stream

A stream of verifiable KERI data, consisting of the [key event log](https://weboftrust.github.io/WOT-terms/docs/glossary/key-event-log.md) and other data such as a [transaction event log](https://weboftrust.github.io/WOT-terms/docs/glossary/transaction-event-log.md). This data is a CESR event stream (TODO: link to IANA application/cesr media type) and may be serialized in a file using [CESR](https://weboftrust.github.io/WOT-terms/docs/glossary/composable-event-streaming-representation.md) encoding. We refer to these _CESR stream resources_ as KERI event streams to simplify the vocabulary.

Source `did:webs` [ToIP specification](https://trustoverip.github.io/tswg-did-method-webs-specification/index.html)