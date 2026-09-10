# Literature → Executable Model

## Core idea
Turn papers, books and technical reports into runnable scientific models rather than plain summaries.

Pipeline:
1. extract equations and definitions
2. resolve symbol meanings and units
3. recover assumptions and regimes
4. link equations that belong to the same model
5. identify missing initial/boundary conditions and parameters
6. construct a semantic model graph
7. emit executable code / solver configuration
8. validate against examples or figures in the source

## Example
Input: several papers describing a battery model.
Output: one reconciled model with equations, parameter table, provenance for every term, simulation-ready code and unresolved conflicts highlighted.

## Why it matters
Literature contains models in fragmented human-readable form. Rebuilding them manually is slow and error-prone. Recent research already demonstrates automated physical model construction by combining equations extracted from literature, but there is substantial room for a general product-grade system.

## Buyers
Engineering R&D, pharma/biotech modeling, materials science, energy, aerospace, universities and scientific AI teams.

## Monetization
High-value enterprise SaaS/on-prem product. Charge per workspace, document corpus or model export.

## Strategic value
This can feed the entire ecosystem: Semantic IR, equation search, simulation, verification, provenance and equation discovery.

## Moat
A growing verified equation/model graph with provenance and cross-document symbol resolution.

## MVP
Pick one narrow domain with standardized models, ingest 20-50 papers and reconstruct 5-10 known models end-to-end.