# Nuclear / Fusion Model Change-Impact Auditor

## Problem
Changing material data, a correlation, surrogate, mesh, control parameter or sensor calibration can invalidate downstream evidence.

## Product
A semantic dependency graph that answers: what must be recomputed, revalidated or re-reviewed after this change?

## Output
`change -> affected models -> margins -> scenarios -> reports -> qualification evidence`

## Value
Reduces unnecessary requalification while preventing stale evidence from surviving hidden dependencies.

## MVP
Versioned multiphysics workflow with automated impact report.