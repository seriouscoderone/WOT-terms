# judge

A judge is an entity or component that examines the entries of one or more [KERLs](https://weboftrust.github.io/WOT-terms/docs/glossary/key-event-receipt-log.md) and DELs of a given identifier to validate that the event history is from a non-[duplicitous](https://weboftrust.github.io/WOT-terms/docs/glossary/duplicity.md) controller and has been witnessed by a sufficient number of non-duplicitous [witnesses](https://weboftrust.github.io/WOT-terms/docs/glossary/witness.md) such that it may be trusted or conversely not-trusted by a [validator](https://weboftrust.github.io/WOT-terms/docs/glossary/validator.md).

A judge determines current \[authoritative\] key set for identifier from the [key event receipt logs](https://weboftrust.github.io/WOT-terms/docs/glossary/key-event-receipt-log.md) from a set of witnesses. Judges transmit the 'judgement' of watchers concerning duplicity.

Example AT&T vs T-Mobile. The only "fault" that is apparent, is an attack on the KEL. And that can only occur via key compromise. So a successful multi-threshold attack causing [duplicity](https://weboftrust.github.io/WOT-terms/docs/glossary/duplicity.md) is the only thing [watchers](https://weboftrust.github.io/WOT-terms/docs/glossary/watcher.md) are looking for.

So even competitors will want to share across the entire ecosystem. Similar to certificate transparency, all competitors in the internet hosting space share the information with each other because it is in their best interest to eliminate fraud / duplicity.
Paraphrased by @henkvancann based on [source Samuel Smith / Phil Feairheller](https://hackmd.io/-soUScAqQEaSw5MJ71899w?view#2022-09-06)