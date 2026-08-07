# Mukosozi Normalization Policy

Linguistic rulings by Christophe Mumaragishyika (native speaker, project lead).
Engineering notes by the build side. Last updated: 2026-08-06.

## Ruled

**1. Sentence capitalization** (UI category: Inyuguti nkuru, blue).
A capital letter is required at the start of a text, after every
sentence-final mark (`.` `!` `?` and the ellipsis), and at the start of a
new line. The engine applies this automatically. *Ruled Aug 2026.*

**2. Terminal punctuation is the writer's tone.**
The engine never converts between `.` `!` `?` `...` and never treats one as
an error for another. Correction pairs that differ only in terminal
punctuation are one entry; the variants are preserved in the attestation
bank. *Ruled Aug 2026.*

**3. Word-bank storage: core forms.**
Headwords are stored as core forms: positional (sentence) capitalization
stripped, terminal punctuation stripped. Intrinsic capitals (proper nouns)
are preserved; every first-letter lowering is listed in the export report
for review. Attestations preserve each observation exactly as written,
tone marks intact. *Ruled Aug 2026.*

## Standing defaults (not yet explicitly ruled; flag to change)

**4. Missing terminal punctuation** at the end of a standalone text is at
most suggestion-level (Igitekerezo, green), never an error. If the engine
proposes a mark, it proposes a period only; it never inserts a tone mark.

**5. Colon and semicolon** are not sentence-final: no capitalization is
triggered after them.

## Engine conformance (v0.1.0, checked 2026-08-06)

Implemented: capitalization at start of text, after `.` `!` `?`
(the punctuation pass normalizes spacing first), and after newlines.

Gap for v0.2: the single-character ellipsis `…` is not yet in the
sentence-end class, so no capital follows it. The typed `...` is covered
because it ends in a dot.
