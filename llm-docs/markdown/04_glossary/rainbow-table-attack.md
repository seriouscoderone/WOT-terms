# rainbow-table-attack

A rainbow table attack is a password-cracking method that uses a special table (a “rainbow table”) to crack the password hashes in a database.

Applications don’t store passwords in plaintext, but instead encrypt passwords using [hashes](https://weboftrust.github.io/WOT-terms/docs/glossary/content-addressable-hash.md). After the user enters their password to login, it is converted to hashes, and the result is compared with the stored hashes on the server to look for a match. If they match, the user is [authenticated](https://weboftrust.github.io/WOT-terms/docs/glossary/authenticity.md) and able to log in.

More on [source](https://www.beyondidentity.com/glossary/rainbow-table-attack)