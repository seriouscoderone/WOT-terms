# sniffable

A stream is _sniffable_ as soon as it starts with a group code or field map; in fact this is how our parser ([Parside](https://weboftrust.github.io/WOT-terms/docs/glossary/parside.md)) works. and detects if the CESR stream contains a certain datablock. The datablock of CESR binary, CESR Text, JSON, CBOR, MGPK have an Object code or the Group code (binary or text) and it's always a recognizable and unique _three bit combination_.

We have the Cold start problem of a stream: you don't where to start recognizing structured data.

So a stream is either sniffable or not, when it has or has not the fore-mentioned group- or object-codes.
Source: Sam Smith, Zoom Meeting KERI, Dec 5 2023

[Sniffer](https://weboftrust.github.io/WOT-terms/docs/glossary/sniffer.md)