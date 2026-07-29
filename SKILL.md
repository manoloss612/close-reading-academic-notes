---
name: close-reading-academic-notes
description: Use when reading, analyzing, annotating, or synthesizing humanities and social-science papers, books, edited volumes, or individual chapters, especially when the user needs close reading, argument reconstruction, conceptual genealogy, evidence auditing, quotations with page numbers, or reusable literature notes.
---

# Close-Reading Academic Notes

## Overview

Produce evidence-grounded academic notes for humanities and social-science literature. Reconstruct what the author argues, how the argument works, which theories and interlocutors matter, and where the reasoning is strong or limited.

**Core rule:** Never fill gaps with plausible scholarship. Separate author statements from analytical inference, and attach page references whenever the source permits.

## Required Workflow

1. **Inspect the source before analyzing.** Determine document type, completeness, readable page range, and whether notes, references, tables, or appendices are available.
2. **Choose the analysis mode:**
   - `paper`: journal article or self-contained essay;
   - `chapter`: one chapter within a larger book;
   - `book`: complete monograph or edited volume;
   - `quick`: compressed research card when the user requests brevity.
3. **Build an evidence ledger while reading.** Record major claims, supporting passages, page numbers, concepts, cited allies/opponents, cases, and unresolved questions.
4. **Reconstruct the argument, not the table of contents.** For each major step use: `claim → evidence → warrant → interim conclusion → remaining question`.
5. **Write the notes using `references/output-template.md`.** Adapt sections to the document type; do not force every section when evidence is absent.
6. **Run the audit in `references/quality-checklist.md` before delivery.**

## Epistemic Labels

Use these labels whenever attribution could be ambiguous:

- `[明示]`: directly stated or explicitly cited by the author;
- `[归纳]`: synthesized from multiple passages;
- `[推断]`: reasonable interpretation by the analyst;
- `[延伸]`: research connection beyond the document;
- `[待核]`: unavailable, illegible, incomplete, or unverified.

Never present `[推断]` or `[延伸]` as the author's own claim.

## Source-Coverage Rules

- State whether the source is complete, partial, or excerpted.
- State the actual pages or chapters read.
- If only an abstract, introduction, preview, or selected pages are available, do not claim to analyze the full work.
- For books, first map the whole-book problem and structure, then analyze chapters, then return to a whole-book synthesis.
- For a chapter, explain its function in the book and its relation to adjacent chapters when that context is available.

## Quotation Rules

- Quote only text actually present in the source.
- Preserve the original language; optional translations must be labeled `自译` or attributed to a published translation.
- Include page numbers. Use `[页码待核]` only when the text is verifiable but pagination is unavailable.
- Never convert a paraphrase into quotation marks.
- Fewer verified quotations are better than invented “golden quotes.”

## Critical-Audit Rules

Critique the argument, not the author's motives. For each material limitation provide:

`problem → textual basis → why it matters → plausible alternative → confidence (high/medium/low) → reason for confidence`

Check especially for unsupported generalization, selection bias, causal overreach, conceptual drift, missing warrants, ignored counterexamples, anachronism, and overinterpretation. Discuss gender, class, race, coloniality, technology, media, geography, or institutional position only when relevant to the work's problem.

## Mode-Specific Requirements

### Paper
Prioritize research problem, intervention, argument chain, evidence, method, contribution, and limitations.

### Chapter
Add chapter function, dependency on earlier chapters, preparation for later chapters, and contribution to the book's central thesis.

### Book
Use two levels:
1. whole-book map: problem, thesis, architecture, conceptual development, genealogy, contribution;
2. chapter notes: function, claim, argument, evidence, quotations, limitations, chapter-to-chapter relation.
Finish by identifying theoretical-core chapters, evidence-heavy chapters, weakly integrated chapters, and whether the conclusion is supported by the whole architecture.

### Quick
Return only: metadata, source coverage, core problem, one-sentence thesis, three-step argument chain, key concepts, strongest evidence, contribution, main limitation, and research relevance.

## Supporting Files

- Full output structure: `references/output-template.md`
- Final verification: `references/quality-checklist.md`
- Pressure scenarios: `tests/scenarios.md`
