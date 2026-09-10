# Ideas — Scientific Math & Physics Ecosystem

This repository is a persistent design notebook for high-value scientific software ideas, especially mathematics and physics tooling.

The central thesis is that scientific expressions should not remain inert strings rendered by LaTeX/MathJax. A formula should become a semantic object that carries enough structure to be checked, transformed, searched, simulated, compiled, versioned, audited and formally verified.

## Foundation / core

1. [Semantic Scientific Objects](01-semantic-scientific-objects.md)
2. [Equation Debugger / Verifier](02-equation-debugger.md)
3. [Equation-to-Simulation](03-equation-to-simulation.md)
4. [Semantic Equation & Theorem Search](04-semantic-search.md)
5. [PDF-to-Semantic Scientific Document](05-pdf-to-semantic-document.md)
6. [LaTeX-to-Lean / Formal Verification](06-latex-to-lean.md)
7. [Scientific Compiler](07-scientific-compiler.md)
8. [Architecture & Product Roadmap](08-architecture-roadmap.md)

## High-value product ideas

9. [Scientific Model Testbench — unit tests for physics/models](09-scientific-model-testbench.md)
10. [Literature → Executable Model](10-literature-to-executable-model.md)
11. [Inverse Problem Studio — model + measurements → parameters](11-inverse-problem-studio.md)
12. [Uncertainty Propagation Engine](12-uncertainty-propagation-engine.md)
13. [Semantic Math Diff — meaning-aware version control](13-semantic-math-diff.md)
14. [Tensor / Index / Convention Debugger](14-tensor-index-debugger.md)
15. [Governing Equation Discovery](15-governing-equation-discovery.md)
16. [Optimal Experiment Design Engine](16-optimal-experiment-design.md)
17. [Reproducible Research Capsule](17-reproducible-research-capsule.md)
18. [Scientific Provenance Graph](18-scientific-provenance-graph.md)
19. [Scientific Claim Auditor](19-scientific-claim-auditor.md)

## Product strategy

### Fastest painkillers to prototype
- Scientific Model Testbench
- Inverse Problem Studio
- Tensor / Index Debugger
- Semantic Math Diff

### Highest-value B2B opportunities
- Literature → Executable Model
- Optimal Experiment Design
- Inverse Problem Studio
- Scientific Claim Auditor

### Strongest long-term moat
- Semantic Scientific Objects / IR
- Scientific Provenance Graph
- Literature → Executable Model
- Governing Equation Discovery
- Reproducible Research Capsules

## Principle

Existing tools such as LaTeX, MathJax/KaTeX, SymPy/SageMath, Jupyter, SciML/FEniCS/QuTiP, Lean/Mathlib and visualization libraries already solve many isolated layers well. The product opportunity is to connect them through a shared semantic representation and a coherent scientific UX.

Avoid rebuilding commodity components unless necessary. Own the semantic layer, diagnostics, provenance, verification, orchestration and domain-specific workflow intelligence.