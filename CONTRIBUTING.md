# Contributing to Mukosozi

Thank you for your interest in Mukosozi. This project welcomes contributions, especially from:

- **Native Kinyarwanda speakers** with linguistic intuition or formal training
- **Linguists** working on Bantu or morphologically rich languages
- **NLP researchers and engineers** building tools for low-resource languages
- **Developers** willing to help with tooling, infrastructure, or UI

This project moves slowly and deliberately. Linguistic accuracy matters more than speed; missing rules are better than wrong ones.

---

## Before you contribute

By submitting a contribution (issue, pull request, discussion comment, or other), you agree that:

1. Your contribution is original work or properly attributed.
2. You license your contribution under the project's terms:
   - Source code contributions → **AGPL-3.0** (see [`LICENSE`](LICENSE))
   - Linguistic data contributions → **CC BY-NC-SA 4.0** (see [`LICENSE-DATA`](LICENSE-DATA))
3. The maintainer may edit, restructure, or decline contributions to keep the project linguistically accurate and architecturally coherent.
4. You understand the project may be commercialized in the future under separate terms (see [`NOTICE`](NOTICE)) and that contributions become part of a dual-licensed body of work.

---

## Ways to contribute

### Reporting bugs

Open a [GitHub Issue](https://github.com/mukosozi/mukosozi/issues) with:

- **Input** — the exact text you entered
- **Expected output** — what should have happened
- **Actual output** — what the app produced
- **Environment** — browser and OS (e.g. "Chrome 128 on macOS Sonoma")

### Proposing new linguistic rules or corrections

This is the **highest-value type of contribution**. Open an issue with the `linguistic-rule` label and include:

- **The rule** stated clearly in plain language
- **Examples** — at least three correct uses and three incorrect uses
- **Source** — your own native-speaker judgment, a published grammar reference, or another linguistic authority
- **Category** — punctuation, spacing, morphology, lexical exception, neologism, etc.

The maintainer will review and discuss before any rule is merged. Native-speaker validation is required for all linguistic changes.

### Proposing neologisms

New Kinyarwanda terminology for modern concepts requires extra rigor. Open an issue with the `neologism` label and include:

- **Proposed word**
- **Definition** in both Kinyarwanda and English
- **Morphological analysis** — break the word into morphemes and explain the construction
- **Rationale** — why this construction, and what alternatives were considered
- **Existing alternatives** (loanwords, competing proposals, etc.)

Neologisms are reviewed against criteria including morphological soundness, semantic clarity, and consistency with existing Kinyarwanda word-formation patterns.

### Code contributions

For code changes:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-change`
3. Make focused, well-explained commits
4. Open a pull request describing what changed and why
5. Reference any related issue with `Fixes #N` or `Refs #N`

Keep PRs focused: one rule, one feature, or one fix per PR.

### Discussion

For broader questions, design ideas, or research collaboration, open a [Discussion](https://github.com/mukosozi/mukosozi/discussions) rather than an Issue. Discussions are for *talking through ideas*; issues are for *tracked, actionable items*.

---

## What the maintainer prioritizes

In rough order:

1. **Linguistic accuracy** — incorrect rules are worse than missing rules.
2. **Native-speaker authority** — proposals from native speakers carry more weight on linguistic questions, especially around nuance, idiom, and acceptability.
3. **Documentation** — every correction should be traceable to a documented rule with a clear explanation. No "magic" corrections.
4. **Architectural stability** — backwards compatibility within a major version, sustainable structure, no over-engineering.
5. **Tone** — the project serves the Kinyarwanda-speaking community. Contributions that would harm, misrepresent, or condescend to that community will not be accepted.

---

## Code of conduct

Be respectful, be patient, and assume good faith. Disagree about the work, not about people.

---

## Questions

For questions about contributing that don't fit into an issue or discussion:

**Christophe Mumaragishyika**
`mukosozi.rw@gmail.com`

*Murakoze cyane* — thank you very much.
