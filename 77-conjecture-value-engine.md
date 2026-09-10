# Conjecture Value Engine

## Problem
Automated systems can generate thousands of mathematically valid conjectures, but most may be trivial, redundant, ugly, isolated, or strategically unimportant.

## Product
Score conjectures before expensive proof search.

## Signals
- novelty vs known theorem graph
- generality and assumption economy
- number/importance of downstream statements it could unlock
- connection between previously separated areas
- compressibility of many known facts into one result
- counterexample resistance
- estimated proof difficulty
- expert-interest priors
- explanatory/structural value

## Output
A ranked frontier: `prove now`, `interesting but low leverage`, `duplicate`, `likely false`, `foundational candidate`, `high-risk/high-upside`.

## Business
R&D triage for AI-math labs, universities and proprietary theorem/model programs.

## Moat
Historical outcomes create a learned notion of mathematical leverage rather than generic language-model 'interestingness'.
