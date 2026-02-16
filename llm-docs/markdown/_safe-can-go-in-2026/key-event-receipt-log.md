# key-event-receipt-log

a key event receipt log is a [KEL](https://weboftrust.github.io/WOT-terms/docs/glossary/kel.md) that also includes all the consistent key event receipt [Message](https://weboftrust.github.io/WOT-terms/docs/glossary/message.md)s created by the associated set of witnesses. See annex [Key event receipt log](https://weboftrust.github.io/WOT-terms/docs/glossary/key-event-receipt-log.md).
Source: Dr. S.Smith

Signed Key Events, keeping track of establishment events. To begin with the inception event and any number of rotation events. We call that the establishment subsequence. The Key Event Receipt Logs are built from receipts of events signed by the witnesses of those events (these are called commitments); these are also append-only but not hash-chained. (@henkvancann)

![](https://github.com/WebOfTrust/keri/blob/main/images/inception-rotation.png)