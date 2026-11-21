# Bible App add-ons

Optional downloads for the Bible App. The app fetches them from this repository's releases on request, so the base app stays small. This repository holds only these files, not the app's code.

## Later Fathers (`later-fathers-v1`)

`later_fathers_v1.db.gz`: the Nicene and Post-Nicene Fathers, First and Second Series (28 volumes), as a SQLite database, gzipped (25 MB, 91 MB unpacked).

- Contents: 231 works, about 55,000 paragraphs, with the Fathers' own words only. The editors' footnotes, introductions, prefaces, summaries and indexes are left out.
- Source: the Christian Classics Ethereal Library (ccel.org) editions of Philip Schaff and Henry Wace (eds.), *Nicene and Post-Nicene Fathers* (1886–1900). The text is in the public domain.
- SHA-256 of the download: `6f98edee0cc9abe6bcd0affe68b614fe2ecfbd3ce5810da981d6d4f36ba70b66`
- Author dates link to their Wikipedia articles (CC BY-SA 4.0).

## Topic search (`topics-v1`)

`topics_v1.pack.gz`: the search model and fingerprints for searching the early church writings by topic or question, on the device (53 MB, 64 MB unpacked).

- Contents: the model bge-small-en-v1.5 (BAAI, MIT licence; the licence text is inside the pack), its word list, and a fingerprint (384 numbers) for each stretch of the Ante-Nicene writings and the Later Fathers above. The fingerprints were made from the texts described above; they hold no text themselves.
- SHA-256 of the download: `861fbd87d73ce0d0b9ed4497b36dff12c850090eb713c0e9315cdeab10846227`
- Model: https://huggingface.co/BAAI/bge-small-en-v1.5
