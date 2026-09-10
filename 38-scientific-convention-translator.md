# Scientific Convention Translator

## Idea
Translate equations and models between equivalent but incompatible scientific conventions while preserving meaning.

Examples:
- SI ↔ cgs ↔ natural units
- Fourier transform sign/normalization conventions
- metric signature (+---) ↔ (-+++)
- covariant/contravariant tensor conventions
- active ↔ passive rotations
- degrees ↔ radians where metadata is explicit
- different thermodynamic / electromagnetism sign conventions
- notation changes across papers

## Why it matters
Many apparent disagreements in physics are convention mismatches, and copying equations across sources can silently introduce sign/factor errors.

## Material value
Useful in research, simulation integration, textbooks, symbolic workflows and literature-to-model compilation. It is especially valuable when combining equations from multiple sources.

## Strategic value
A convention ontology makes Semantic Search and Literature→Executable Model substantially stronger. It lets the system recognize that differently written equations are semantically equivalent.

## Differentiation
This is not text/LaTeX replacement. Transformation must be typed, global and consistency-checked across the whole model.

## MVP
Start with units, Fourier transform conventions and a small set of vector/tensor coordinate conventions. Emit a transformation map and verify dimensional/numerical equivalence on test cases.