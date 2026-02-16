# self-addressing-identifier

any identifier that is deterministically generated out of the content, or a digest of the content.
Source: Dr. S. Smtih

An identifier that is deterministically generated from and embedded in the content it identifies, making it and its data mutually tamper-evident.

1.  Fully populate the data that the SAID will identify, leaving a placeholder for the value of the SAID itself.
2.  Canonicalize the data, if needed. The result is called the SAID's **identifiable basis**.
3.  Hash the _identifiable basis_. The result is the value of the SAID.
4.  Replace the placeholder in _identifiable basis_ the with the newly generated identifier, so the SAID is embedded in the data it identifies. The result is called the **saidified data.**

1.  Canonicalize the data, if needed. The result is **claimed saidified data**.
2.  In the _claimed saidified data_, replace the SAID value with a placeholder. The result is the **identifiable basis** for the SAID.
3.  Hash the _identifiable basis_.
4.  Compare the hash value to the SAID. If they are equal, then the SAID identifies the _claimed saidified data_.

-   how data is canonicalized
-   which hash algorithm is used
-   which placeholder is used
-   how the bytes produced by the hash algorithm are encoded
-   how the SAID value is formatted

A terse way to describe a SAID and its data is to write an expression that consists of the token `SAID` followed by a token with field names in canonical order, where the field containing the SAID itsef is marked by the suffix `=said`. For example, the saidification of a simple `ContactInfo` data structure might be given as `SAID(name, address, phone, email, id=said)`.