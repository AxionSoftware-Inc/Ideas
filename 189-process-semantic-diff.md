# Process Semantic Diff

## Core idea
A meaning-aware diff for manufacturing/process recipes that distinguishes harmless formatting/value representation changes from changes that alter physical process behavior or qualification status.

## Product
Compare recipe versions and report changes in energy input, material state, timing sequence, control logic, thermal history, machine capability assumptions and validation coverage. Propagate impact to affected products/tests.

## Buyers
Manufacturing engineering, process industries, quality/regulatory teams and equipment vendors.

## Value
Version control is weak when a parameter file change silently changes physical behavior. Semantic diff can become the review gate before production recipe updates.

## Synergy
Semantic Math Diff + Scientific Change-Impact Analyzer + Process Window Compiler.