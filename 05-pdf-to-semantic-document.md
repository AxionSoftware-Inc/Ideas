# PDF-to-Semantic Scientific Document

## Goal

Convert a scientific PDF into a structured machine-understandable scientific document rather than merely extracting text and LaTeX.

## Output objects

A converted document should identify:

- sections and subsections
- definitions
- variables and symbols
- equations
- theorem statements
- lemmas
- proofs
- assumptions
- citations
- figures
- tables
- equation references
- dependencies between equations
- units and dimensions
- concepts and topics

## Example transformation

Instead of:

```text
PDF image -> OCR -> Markdown/LaTeX
```

use:

```text
PDF pages
  -> visual/document understanding
  -> layout structure
  -> formula structure
  -> semantic object extraction
  -> cross-reference resolution
  -> scientific knowledge graph
  -> editable semantic document
```

## Why this matters

The resulting corpus can power:

- scientific search
- high-quality translation
- AI datasets
- theorem/equation retrieval
- automatic verification
- interactive textbooks
- formula-to-simulation links
- reusable datasets for scientific models

## Quality principle

For scientific books, page-image understanding should remain available as a primary signal. An OCR-first pipeline should not be mandatory, especially for difficult formulas and layouts.
