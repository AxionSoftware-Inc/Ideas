# Theory Dependency Graph

## Thesis
Represent scientific theories as dependency graphs rather than flat textbook chapters.

A node may be a definition, assumption, law, theorem, approximation, constitutive relation or empirical fit. Edges encode derivation and dependency.

Example:
```text
Continuum assumption
  -> Navier-Stokes
     -> incompressible approximation
        -> Stokes flow
```

## Capabilities
- show exactly which assumptions a result depends on
- compare two theories structurally
- identify the minimal assumptions needed for a result
- detect when a user combines incompatible approximations
- trace downstream impact when one relation changes

## Strategic value
This can become the semantic skeleton behind scientific education, formal verification, model selection and AI reasoning.